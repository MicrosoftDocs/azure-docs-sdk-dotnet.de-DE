---
title: Azure-Verwaltungsbibliotheken für .NET – Konzepte und Muster für die Verwendung
description: ''
ms.date: 10/19/2017
ms.openlocfilehash: 0a6ae94046680b81f1222c3c2acc6df9871bff4a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190603"
---
# <a name="azure-management-library-for-net-fluent-concepts"></a>Azure-Verwaltungsbibliothek für .NET Fluent-Konzepte

In diesem Artikel wird erläutert, wie Sie die Fluent-Oberfläche in den Azure-Verwaltungsbibliotheken für .NET effektiv einsetzen.

## <a name="building-resources-using-a-fluent-interface"></a>Erstellen von Ressourcen mithilfe einer Fluent-Oberfläche

Eine Fluent-Benutzeroberfläche ist eine bestimmte Form des Generatormusters, mit dem Objekte mithilfe einer Methodenkette erstellt werden, die die ordnungsgemäße Konfiguration einer Ressource erzwingt. Das Azure-Einstiegspunktobjekt wird beispielsweise mithilfe einer Fluent-Oberfläche erstellt:

```csharp
var azure = Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

## <a name="resource-collections"></a>Ressourcensammlungen

Das oben gezeigte `Microsoft.Azure.Management.Fluent.Azure`-Objekt ist der Einstiegspunkt für die gesamte Ressourcenerstellung in den Fluent-Verwaltungsbibliotheken. Wählen Sie mithilfe der Ressourcensammlungen im Objekt `Azure` aus, mit welcher Art von Ressourcen Sie arbeiten möchten. Beispiel für SQL-Datenbank:

```csharp
var sql = azure.SqlServers.Define(sqlServerName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithAdministratorLogin(administratorLogin)
    .WithAdministratorPassword(administratorPassword)
    .Create();
```

Wie oben gezeigt, beginnen die meisten Fluent-Konversationen, die Sie mit der API haben, durch Auswählen der entsprechenden Ressourcensammlung für die Azure-Ressourcen, mit denen Sie arbeiten müssen.  IntelliSense in Visual Studio führt Sie durch die Konversation. 

![Abbildung von Intellisense in Visual Studio und einer Fluent-Konversation](media/dotnet-sdk-azure-concepts/vs-fluent.gif)   

## <a name="lists-and-iterations"></a>Listen und Iterationen

Jede Ressourcensammlung verfügt über eine `List()`Methode, um jede Instanz der Ressource in Ihrem aktuellen Abonnement zurückzugeben. `Azure.SqlServers.List()` gibt beispielsweise alle SQL Server-Instanzen im Abonnement zurück.

Verwenden Sie die `ListByResourceGroup()`-Methode, um die zurückgegebene Liste auf eine bestimmte [Azure-Ressourcengruppe](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups) einzugrenzen.  

Die zurückgegebene Sammlung kann genau wie ein normales Element des Typs `List<T>` durchlaufen werden:

```csharp
var vmList = azure.VirtualMachines.List();
foreach(var vm in vmList)
{
    Console.WriteLine("VM Name: {0}", vm.Name);
}
```   

## <a name="actionable-verbs"></a>Handlungsrelevante Verben

Ressourcensammlungsmethoden, deren Name ein Verb enthält, haben das sofortige Ausführen einer Aktion in Azure zur Folge. Diese Methoden werden synchron ausgeführt und blockieren bis zu ihrem Abschluss die Ausführung im aktuellen Thread. 

| Verb   |  Beispielverwendung |
|--------|---------------|
| Erstellen | `azure.VirtualMachines.Create(listOfVMCreatables)` |
| Anwenden  | `virtualMachineScaleSet.Update().WithCapacity(6).Apply()` |
| Löschen | `azure.Disks.DeleteById(id)` | 
| Auflisten   | `azure.SqlServers.List()` | 
| Get    | `var vm  = azure.VirtualMachines.GetByResourceGroup(group, vmName)` |

>[!NOTE]
> `Define()` und `Update()` sind zwar Verben, blockieren den Ablauf aber nur, wenn im Anschluss `Create()` oder `Apply()` folgt.
 
Bestimmte Ressourcenobjekte weisen Verben auf, die den Zustand der Ressource in Azure ändern. Beispiel: 

```csharp
var vmToRestart = azure.VirtualMachines.GetById(id);
vmToRestart.Restart();
```

Für die meisten der in diesem Abschnitt beschriebenen Methoden gibt es auch eine asynchrone Version, die durch das Suffix `Async` gekennzeichnet wird.

```csharp
Task restartTask = azure.VirtualMachines.GetById(id).RestartAsync();
```

## <a name="lazy-resource-creation"></a>Verzögerte Ressourcenerstellung

Eine Herausforderung beim Erstellen von Azure-Ressourcen ergibt sich, wenn eine neue Ressource von einer anderen Ressource abhängt, die noch nicht vorhanden ist. Ein Beispiel ist das Reservieren einer öffentlichen IP-Adresse und Einrichten eines Datenträgers beim Erstellen eines neuen virtuellen Computers. Sie möchten die Reservierung der Adresse oder Erstellung des Datenträgers nicht überprüfen, sondern bloß den virtuellen Computer mit diesen Ressourcen konfigurieren.

Verwenden Sie erstellbare Objekte, um Azure-Ressourcen für die Verwendung im Code zu definieren, aber nur bei Bedarf in Azure zu erstellen. Mithilfe von Code mit erstellbaren Objekten wird das Erstellen von Ressourcen in der Azure-Umgebung an die Verwaltungs-API ausgelagert, wodurch die Leistung erheblich gesteigert wird. 

Generieren Sie erstellbare Objekte über das Verb `Define()` der Ressourcensammlungen ohne das Verb `Create()`:

```csharp
// Init a creatable Public IP Address
var publicIpAddressCreatable = azure.PublicIPAddresses.Define("publicIPAddressName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName);
```

Die vom erstellbaren Objekt definierte Azure-Ressource ist noch nicht in Ihrem Azure-Abonnement vorhanden. Ein erstellbares Objekt ist eine lokale Darstellung einer Ressource, die die Verwaltungs-API bei Bedarf erstellt (durch Aufruf von `.Create()`). Verwenden Sie dieses erstellbare Objekt in der Definition anderer Azure-Ressourcen, die diese Ressource benötigen. 

```csharp
// Init a creatable VM using the creatable Public IP Address
var vmCreatable = azure.VirtualMachines.Define("creatableVM")
    // ...
    .withNewPrimaryPublicIPAddress(publicIPAddressCreatable)
    // ...
```

Erstellen Sie die Ressourcen in Ihrem Azure-Abonnement mithilfe der `Create()`-Methode für die Ressourcensammlung. 

```csharp
// Create the VM and its Public IP Address
var virtualMachine = azure.VirtualMachines.Create(vmCreatable);
```

Durch die Übergabe erstellbarer Objekte an `Create()` wird ein `ICreatedResources`-Objekt anstelle eines einzelnen Ressourcenobjekts zurückgegeben.  Das `CreatedRelatedResource`-Objekt ermöglicht den Zugriff auf alle Ressourcen, die durch den Aufruf von `Create()` erstellt wurden (nicht bloß auf den Typ in der Ressourcensammlung). So greifen Sie auf die in Azure erstellte öffentliche IP-Adresse für den virtuellen Computer zu, der im obigen Beispiel erstellt wurde

```csharp
var pip = virtualMachine.CreatedRelatedResource(publicIPAddressCreatable.Key()) as PublicIPAddress;;
```    

## <a name="exception-handling"></a>Ausnahmebehandlung

Die Verwaltungs-API definiert Ausnahmeklassen, mit denen `Microsoft.Rest.RestException` erweitert wird. Fangen Sie von der Verwaltungs-API generierte Ausnahmen mit einem Block des Typs `catch (RestException exception)` nach der entsprechenden `try`-Anweisung ab.

## <a name="logs-and-tracing"></a>Protokollierung und Ablaufverfolgung

Für die Protokollierung in den Azure-Fluent-Verwaltungsbibliotheken für .NET wird die zugrunde liegende Clientablaufverfolgung des [AutoRest](https://github.com/Azure/AutoRest)-Diensts genutzt.

Erstellen Sie eine Klasse, die `Microsoft.Rest.IServiceClientTracingInterceptor` implementiert.  Diese Klasse ist zuständig für das Abfangen von Protokollmeldungen und deren Übergabe an den verwendeten Protokollierungsmechanismus.  In diesem Beispiel geben wir bloß Meldungen an die Konsole aus. Sie können diese aber auch an Log4Net, `Microsoft.Extensions.Logging` oder ein anderes Protokollierungsframework übergeben.

```csharp
class ConsoleTracer : IServiceClientTracingInterceptor
{
    public void Information(string message)
    {
        Console.WriteLine(message);
    }

    public void TraceError(string invocationId, Exception exception)
    {
        Console.WriteLine("Exception in {0}: {1}", invocationId, exception);
    }

    public void ReceiveResponse(string invocationId, HttpResponseMessage response) { }

    public void SendRequest(string invocationId, HttpRequestMessage request) { }

    public void Configuration(string source, string name, string value) { }

    public void EnterMethod(string invocationId, object instance, string method, IDictionary<string, object> parameters) { }

    public void ExitMethod(string invocationId, object returnValue) { }
}
```

Initialisieren Sie vor dem Erstellen des `Microsoft.Azure.Management.Fluent.Azure`-Objekts den `IServiceClientTracingInterceptor`, den Sie zuvor erstellt haben, indem Sie `ServiceClientTracing.AddTracingInterceptor()` aufrufen und `ServiceClientTracing.IsEnabled` auf *true* festlegen.  Fügen Sie beim Erstellen des `Azure`-Objekts die Methoden `.WithDelegatingHandler()` und `.WithLogLevel()` hinzu, um den Client für die Clientablaufverfolgung des AutoRest-Diensts einzurichten.

```csharp
ServiceClientTracing.AddTracingInterceptor(new ConsoleTracer());
ServiceClientTracing.IsEnabled = true;

var azure = Azure
    .Configure()
    .WithDelegatingHandler(new HttpLoggingDelegatingHandler())
    .WithLogLevel(HttpLoggingDelegatingHandler.Level.Basic)
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

Die Protokollebenen von `HttpLoggingDelegatingHandler` sind wie folgt definiert:

| Ablaufverfolgungsebene | Protokollierung aktiviert 
| ------------ | ---------------
| HttpLoggingDelegatingHandler.Level.None | Keine Ausgabe
| HttpLoggingDelegatingHandler.Level.Basic | Protokolliert die URLs für zugrunde liegende REST-Aufrufe, Antwortcodes und Zeiten
| HttpLoggingDelegatingHandler.Level.Body | Alles in „Basic“ plus Abfrage- und Antworttext für die REST-Aufrufe
| HttpLoggingDelegatingHandler.Level.Headers | Alles in „Basic“ plus Abfrage- und Antwortheader der REST-Aufrufe
| HttpLoggingDelegatingHandler.Level.BodyAndHeaders | Alles auf den Protokollierungsebenen „Body“ und „Headers“
