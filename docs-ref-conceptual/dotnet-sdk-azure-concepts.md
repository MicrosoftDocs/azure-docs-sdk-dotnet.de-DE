---
title: Azure-Verwaltungsbibliotheken für .NET – Konzepte und Muster für die Verwendung
description: ''
keywords: Azure, .NET, SDK, API, Muster, Konzepte, Fluent, Protokollierung
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: b817216e114e5ab3ff22c1c5adb0f892c7874147
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2018
ms.locfileid: "29752862"
---
# <a name="azure-management-library-for-net-fluent-concepts"></a><span data-ttu-id="a035a-103">Azure-Verwaltungsbibliothek für .NET Fluent-Konzepte</span><span class="sxs-lookup"><span data-stu-id="a035a-103">Azure management library for .NET fluent concepts</span></span>

<span data-ttu-id="a035a-104">In diesem Artikel wird erläutert, wie Sie die Fluent-Oberfläche in den Azure-Verwaltungsbibliotheken für .NET effektiv einsetzen.</span><span class="sxs-lookup"><span data-stu-id="a035a-104">This article will help you understand how to effectively use the fluent interface in the Azure management libraries for .NET.</span></span>

## <a name="building-resources-using-a-fluent-interface"></a><span data-ttu-id="a035a-105">Erstellen von Ressourcen mithilfe einer Fluent-Oberfläche</span><span class="sxs-lookup"><span data-stu-id="a035a-105">Building resources using a fluent interface</span></span>

<span data-ttu-id="a035a-106">Eine Fluent-Benutzeroberfläche ist eine bestimmte Form des Generatormusters, mit dem Objekte mithilfe einer Methodenkette erstellt werden, die die ordnungsgemäße Konfiguration einer Ressource erzwingt.</span><span class="sxs-lookup"><span data-stu-id="a035a-106">A fluent interface is a specific form of the builder pattern that creates objects through a method chain that enforces correct configuration of a resource.</span></span> <span data-ttu-id="a035a-107">Das Azure-Einstiegspunktobjekt wird beispielsweise mithilfe einer Fluent-Oberfläche erstellt:</span><span class="sxs-lookup"><span data-stu-id="a035a-107">For example, the entry-point Azure object is created using a fluent interface:</span></span>

```csharp
var azure = Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

## <a name="resource-collections"></a><span data-ttu-id="a035a-108">Ressourcensammlungen</span><span class="sxs-lookup"><span data-stu-id="a035a-108">Resource collections</span></span>

<span data-ttu-id="a035a-109">Das oben gezeigte `Microsoft.Azure.Management.Fluent.Azure`-Objekt ist der Einstiegspunkt für die gesamte Ressourcenerstellung in den Fluent-Verwaltungsbibliotheken.</span><span class="sxs-lookup"><span data-stu-id="a035a-109">The `Microsoft.Azure.Management.Fluent.Azure` object shown above is the entry point for all resource creation in the fluent management libraries.</span></span> <span data-ttu-id="a035a-110">Wählen Sie mithilfe der Ressourcensammlungen im Objekt `Azure` aus, mit welcher Art von Ressourcen Sie arbeiten möchten.</span><span class="sxs-lookup"><span data-stu-id="a035a-110">Select which type of resources to work with using the resource collections in the `Azure` object.</span></span> <span data-ttu-id="a035a-111">Beispiel für SQL-Datenbank:</span><span class="sxs-lookup"><span data-stu-id="a035a-111">For example, for SQL Database:</span></span>

```csharp
var sql = azure.SqlServers.Define(sqlServerName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithAdministratorLogin(administratorLogin)
    .WithAdministratorPassword(administratorPassword)
    .Create();
```

<span data-ttu-id="a035a-112">Wie oben gezeigt, beginnen die meisten Fluent-Konversationen, die Sie mit der API haben, durch Auswählen der entsprechenden Ressourcensammlung für die Azure-Ressourcen, mit denen Sie arbeiten müssen.</span><span class="sxs-lookup"><span data-stu-id="a035a-112">As seen above, most fluent "conversations" you have with the API start with selecting the appropriate resource collection for the Azure resources you need to work with.</span></span>  <span data-ttu-id="a035a-113">IntelliSense in Visual Studio führt Sie durch die Konversation.</span><span class="sxs-lookup"><span data-stu-id="a035a-113">Intellisense in Visual Studio then guides you through the conversation.</span></span> 

![Abbildung von Intellisense in Visual Studio und einer Fluent-Konversation](media/dotnet-sdk-azure-concepts/vs-fluent.gif)   

## <a name="lists-and-iterations"></a><span data-ttu-id="a035a-115">Listen und Iterationen</span><span class="sxs-lookup"><span data-stu-id="a035a-115">Lists and iterations</span></span>

<span data-ttu-id="a035a-116">Jede Ressourcensammlung verfügt über eine `List()`Methode, um jede Instanz der Ressource in Ihrem aktuellen Abonnement zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="a035a-116">Every resource collection has a `List()` method to return every instance of that resource in your current subscription.</span></span> <span data-ttu-id="a035a-117">`Azure.SqlServers.List()` gibt beispielsweise alle SQL Server-Instanzen im Abonnement zurück.</span><span class="sxs-lookup"><span data-stu-id="a035a-117">For example, `Azure.SqlServers.List()` returns all SQL servers in the subscription.</span></span>

<span data-ttu-id="a035a-118">Verwenden Sie die `ListByResourceGroup()`-Methode, um die zurückgegebene Liste auf eine bestimmte [Azure-Ressourcengruppe](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups) einzugrenzen.</span><span class="sxs-lookup"><span data-stu-id="a035a-118">Use the `ListByResourceGroup()` method to scope the returned List to a specific [Azure resource group](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview#resource-groups).</span></span>  

<span data-ttu-id="a035a-119">Die zurückgegebene Sammlung kann genau wie ein normales Element des Typs `List<T>` durchlaufen werden:</span><span class="sxs-lookup"><span data-stu-id="a035a-119">Iterate over the returned collection just as you would a normal `List<T>`:</span></span>

```csharp
var vmList = azure.VirtualMachines.List();
foreach(var vm in vmList)
{
    Console.WriteLine("VM Name: {0}", vm.Name);
}
```   

## <a name="actionable-verbs"></a><span data-ttu-id="a035a-120">Handlungsrelevante Verben</span><span class="sxs-lookup"><span data-stu-id="a035a-120">Actionable verbs</span></span>

<span data-ttu-id="a035a-121">Ressourcensammlungsmethoden, deren Name ein Verb enthält, haben das sofortige Ausführen einer Aktion in Azure zur Folge.</span><span class="sxs-lookup"><span data-stu-id="a035a-121">Resource collection methods with verbs in their names take immediate action in Azure.</span></span> <span data-ttu-id="a035a-122">Diese Methoden werden synchron ausgeführt und blockieren bis zu ihrem Abschluss die Ausführung im aktuellen Thread.</span><span class="sxs-lookup"><span data-stu-id="a035a-122">These methods work synchronously and block execution in the current thread until they complete.</span></span> 

| <span data-ttu-id="a035a-123">Verb</span><span class="sxs-lookup"><span data-stu-id="a035a-123">Verb</span></span>   |  <span data-ttu-id="a035a-124">Beispielverwendung</span><span class="sxs-lookup"><span data-stu-id="a035a-124">Sample usage</span></span> |
|--------|---------------|
| <span data-ttu-id="a035a-125">Erstellen</span><span class="sxs-lookup"><span data-stu-id="a035a-125">Create</span></span> | `azure.VirtualMachines.Create(listOfVMCreatables)` |
| <span data-ttu-id="a035a-126">Anwenden</span><span class="sxs-lookup"><span data-stu-id="a035a-126">Apply</span></span>  | `virtualMachineScaleSet.Update().WithCapacity(6).Apply()` |
| <span data-ttu-id="a035a-127">Löschen</span><span class="sxs-lookup"><span data-stu-id="a035a-127">Delete</span></span> | `azure.Disks.DeleteById(id)` | 
| <span data-ttu-id="a035a-128">Auflisten</span><span class="sxs-lookup"><span data-stu-id="a035a-128">List</span></span>   | `azure.SqlServers.List()` | 
| <span data-ttu-id="a035a-129">Get</span><span class="sxs-lookup"><span data-stu-id="a035a-129">Get</span></span>    | `var vm  = azure.VirtualMachines.GetByResourceGroup(group, vmName)` |

>[!NOTE]
> <span data-ttu-id="a035a-130">`Define()` und `Update()` sind zwar Verben, blockieren den Ablauf aber nur, wenn im Anschluss `Create()` oder `Apply()` folgt.</span><span class="sxs-lookup"><span data-stu-id="a035a-130">`Define()` and `Update()` are verbs but do not block unless followed by a `Create()` or `Apply()`.</span></span>
 
<span data-ttu-id="a035a-131">Bestimmte Ressourcenobjekte weisen Verben auf, die den Zustand der Ressource in Azure ändern.</span><span class="sxs-lookup"><span data-stu-id="a035a-131">Specific resource objects have verbs that change the state of the resource in Azure.</span></span> <span data-ttu-id="a035a-132">Beispiel: </span><span class="sxs-lookup"><span data-stu-id="a035a-132">For example:</span></span>

```csharp
var vmToRestart = azure.VirtualMachines.GetById(id);
vmToRestart.Restart();
```

<span data-ttu-id="a035a-133">Für die meisten der in diesem Abschnitt beschriebenen Methoden gibt es auch eine asynchrone Version, die durch das Suffix `Async` gekennzeichnet wird.</span><span class="sxs-lookup"><span data-stu-id="a035a-133">Most of the methods described in this section have an asynchronous version as well, denoted by the suffix `Async`.</span></span>

```csharp
Task restartTask = azure.VirtualMachines.GetById(id).RestartAsync();
```

## <a name="lazy-resource-creation"></a><span data-ttu-id="a035a-134">Verzögerte Ressourcenerstellung</span><span class="sxs-lookup"><span data-stu-id="a035a-134">Lazy resource creation</span></span>

<span data-ttu-id="a035a-135">Eine Herausforderung beim Erstellen von Azure-Ressourcen ergibt sich, wenn eine neue Ressource von einer anderen Ressource abhängt, die noch nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a035a-135">A challenge when creating Azure resources arises when a new resource depends on another resource that doesn't yet exist.</span></span> <span data-ttu-id="a035a-136">Ein Beispiel ist das Reservieren einer öffentlichen IP-Adresse und Einrichten eines Datenträgers beim Erstellen eines neuen virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="a035a-136">An example is reserving a public IP address and setting up a disk when creating a new virtual machine.</span></span> <span data-ttu-id="a035a-137">Sie möchten die Reservierung der Adresse oder Erstellung des Datenträgers nicht überprüfen, sondern bloß den virtuellen Computer mit diesen Ressourcen konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="a035a-137">You don't want to verify reserving the address or the creating the disk, you just want to configure the virtual machine with those resources.</span></span>

<span data-ttu-id="a035a-138">Verwenden Sie erstellbare Objekte, um Azure-Ressourcen für die Verwendung im Code zu definieren, aber nur bei Bedarf in Azure zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="a035a-138">Use creatable objects to define Azure resources for use in your code but only create them when needed in Azure.</span></span> <span data-ttu-id="a035a-139">Mithilfe von Code mit erstellbaren Objekten wird das Erstellen von Ressourcen in der Azure-Umgebung an die Verwaltungs-API ausgelagert, wodurch die Leistung erheblich gesteigert wird.</span><span class="sxs-lookup"><span data-stu-id="a035a-139">Code written with creatable objects offloads resource creation in the Azure environment to the management API, boosting performance.</span></span> 

<span data-ttu-id="a035a-140">Generieren Sie erstellbare Objekte über das Verb `Define()` der Ressourcensammlungen ohne das Verb `Create()`:</span><span class="sxs-lookup"><span data-stu-id="a035a-140">Generate creatable objects through the resource collections' `Define()` verb without a `Create()` verb:</span></span>

```csharp
// Init a creatable Public IP Address
var publicIpAddressCreatable = azure.PublicIPAddresses.Define("publicIPAddressName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName);
```

<span data-ttu-id="a035a-141">Die vom erstellbaren Objekt definierte Azure-Ressource ist noch nicht in Ihrem Azure-Abonnement vorhanden.</span><span class="sxs-lookup"><span data-stu-id="a035a-141">The Azure resource defined by the creatable object does not yet exist in your subscription.</span></span> <span data-ttu-id="a035a-142">Ein erstellbares Objekt ist eine lokale Darstellung einer Ressource, die die Verwaltungs-API bei Bedarf erstellt (durch Aufruf von `.Create()`).</span><span class="sxs-lookup"><span data-stu-id="a035a-142">A creatable object is a local representation of a resource that the management API will create when it's needed (when `.Create()` is called).</span></span> <span data-ttu-id="a035a-143">Verwenden Sie dieses erstellbare Objekt in der Definition anderer Azure-Ressourcen, die diese Ressource benötigen.</span><span class="sxs-lookup"><span data-stu-id="a035a-143">Use this creatable object in the definition of other Azure resources that need this resource.</span></span> 

```csharp
// Init a creatable VM using the creatable Public IP Address
var vmCreatable = azure.VirtualMachines.Define("creatableVM")
    // ...
    .withNewPrimaryPublicIPAddress(publicIPAddressCreatable)
    // ...
```

<span data-ttu-id="a035a-144">Erstellen Sie die Ressourcen in Ihrem Azure-Abonnement mithilfe der `Create()`-Methode für die Ressourcensammlung.</span><span class="sxs-lookup"><span data-stu-id="a035a-144">Create the resources in your Azure subscription using the `Create()` method for the resource collection.</span></span> 

```csharp
// Create the VM and its Public IP Address
var virtualMachine = azure.VirtualMachines.Create(vmCreatable);
```

<span data-ttu-id="a035a-145">Durch die Übergabe erstellbarer Objekte an `Create()` wird ein `ICreatedResources`-Objekt anstelle eines einzelnen Ressourcenobjekts zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="a035a-145">Passing creatable objects to `Create()` returns a `ICreatedResources` object instead of a single resource object.</span></span>  <span data-ttu-id="a035a-146">Das `CreatedRelatedResource`-Objekt ermöglicht den Zugriff auf alle Ressourcen, die durch den Aufruf von `Create()` erstellt wurden (nicht bloß auf den Typ in der Ressourcensammlung).</span><span class="sxs-lookup"><span data-stu-id="a035a-146">The `CreatedRelatedResource` object lets you access all resources created by the `Create()` call, not just the type from the resource collection.</span></span> <span data-ttu-id="a035a-147">So greifen Sie auf die in Azure erstellte öffentliche IP-Adresse für den virtuellen Computer zu, der im obigen Beispiel erstellt wurde</span><span class="sxs-lookup"><span data-stu-id="a035a-147">To access the public IP address created in Azure for the virtual machine created in the above example:</span></span>

```csharp
var pip = virtualMachine.CreatedRelatedResource(publicIPAddressCreatable.Key()) as PublicIPAddress;;
```    

## <a name="exception-handling"></a><span data-ttu-id="a035a-148">Ausnahmebehandlung</span><span class="sxs-lookup"><span data-stu-id="a035a-148">Exception handling</span></span>

<span data-ttu-id="a035a-149">Die Verwaltungs-API definiert Ausnahmeklassen, mit denen `Microsoft.Rest.RestException` erweitert wird.</span><span class="sxs-lookup"><span data-stu-id="a035a-149">The management API defines exception classes that extend `Microsoft.Rest.RestException`.</span></span> <span data-ttu-id="a035a-150">Fangen Sie von der Verwaltungs-API generierte Ausnahmen mit einem Block des Typs `catch (RestException exception)` nach der entsprechenden `try`-Anweisung ab.</span><span class="sxs-lookup"><span data-stu-id="a035a-150">Catch exceptions generated by management API, with a `catch (RestException exception)` block after the relevant `try` statement.</span></span>

## <a name="logs-and-tracing"></a><span data-ttu-id="a035a-151">Protokollierung und Ablaufverfolgung</span><span class="sxs-lookup"><span data-stu-id="a035a-151">Logs and tracing</span></span>

<span data-ttu-id="a035a-152">Für die Protokollierung in den Azure-Fluent-Verwaltungsbibliotheken für .NET wird die zugrunde liegende Clientablaufverfolgung des [AutoRest](https://github.com/Azure/AutoRest)-Diensts genutzt.</span><span class="sxs-lookup"><span data-stu-id="a035a-152">Logging in the fluent Azure management libraries for .NET leverages the underlying [AutoRest](https://github.com/Azure/AutoRest) service client tracing.</span></span>

<span data-ttu-id="a035a-153">Erstellen Sie eine Klasse, die `Microsoft.Rest.IServiceClientTracingInterceptor` implementiert.</span><span class="sxs-lookup"><span data-stu-id="a035a-153">Create a class that implements `Microsoft.Rest.IServiceClientTracingInterceptor`.</span></span>  <span data-ttu-id="a035a-154">Diese Klasse ist zuständig für das Abfangen von Protokollmeldungen und deren Übergabe an den verwendeten Protokollierungsmechanismus.</span><span class="sxs-lookup"><span data-stu-id="a035a-154">This class will be responsible for intercepting log messages and passing them to whatever logging mechanism you're using.</span></span>  <span data-ttu-id="a035a-155">In diesem Beispiel geben wir bloß Meldungen an die Konsole aus. Sie können diese aber auch an Log4Net, `Microsoft.Extensions.Logging` oder ein anderes Protokollierungsframework übergeben.</span><span class="sxs-lookup"><span data-stu-id="a035a-155">In this example, we're just writing messages to the console, but you could also pass them to Log4Net, `Microsoft.Extensions.Logging`, or any other logging framework.</span></span>

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

<span data-ttu-id="a035a-156">Initialisieren Sie vor dem Erstellen des `Microsoft.Azure.Management.Fluent.Azure`-Objekts den `IServiceClientTracingInterceptor`, den Sie zuvor erstellt haben, indem Sie `ServiceClientTracing.AddTracingInterceptor()` aufrufen und `ServiceClientTracing.IsEnabled` auf *true* festlegen.</span><span class="sxs-lookup"><span data-stu-id="a035a-156">Before creating the `Microsoft.Azure.Management.Fluent.Azure` object, initialize the `IServiceClientTracingInterceptor` you created above by calling `ServiceClientTracing.AddTracingInterceptor()` and set `ServiceClientTracing.IsEnabled` to *true*.</span></span>  <span data-ttu-id="a035a-157">Fügen Sie beim Erstellen des `Azure`-Objekts die Methoden `.WithDelegatingHandler()` und `.WithLogLevel()` hinzu, um den Client für die Clientablaufverfolgung des AutoRest-Diensts einzurichten.</span><span class="sxs-lookup"><span data-stu-id="a035a-157">When you create the `Azure` object, include the `.WithDelegatingHandler()` and `.WithLogLevel()` methods to wire up the client to AutoRest's service client tracing.</span></span>

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

<span data-ttu-id="a035a-158">Die Protokollebenen von `HttpLoggingDelegatingHandler` sind wie folgt definiert:</span><span class="sxs-lookup"><span data-stu-id="a035a-158">The `HttpLoggingDelegatingHandler` log levels are defined as follows:</span></span>

| <span data-ttu-id="a035a-159">Ablaufverfolgungsebene</span><span class="sxs-lookup"><span data-stu-id="a035a-159">Trace level</span></span> | <span data-ttu-id="a035a-160">Protokollierung aktiviert</span><span class="sxs-lookup"><span data-stu-id="a035a-160">Logging enabled</span></span> 
| ------------ | ---------------
| <span data-ttu-id="a035a-161">HttpLoggingDelegatingHandler.Level.None</span><span class="sxs-lookup"><span data-stu-id="a035a-161">HttpLoggingDelegatingHandler.Level.None</span></span> | <span data-ttu-id="a035a-162">Keine Ausgabe</span><span class="sxs-lookup"><span data-stu-id="a035a-162">No output</span></span>
| <span data-ttu-id="a035a-163">HttpLoggingDelegatingHandler.Level.Basic</span><span class="sxs-lookup"><span data-stu-id="a035a-163">HttpLoggingDelegatingHandler.Level.Basic</span></span> | <span data-ttu-id="a035a-164">Protokolliert die URLs für zugrunde liegende REST-Aufrufe, Antwortcodes und Zeiten</span><span class="sxs-lookup"><span data-stu-id="a035a-164">Logs the URLs to underlying REST calls, response codes and times</span></span>
| <span data-ttu-id="a035a-165">HttpLoggingDelegatingHandler.Level.Body</span><span class="sxs-lookup"><span data-stu-id="a035a-165">HttpLoggingDelegatingHandler.Level.Body</span></span> | <span data-ttu-id="a035a-166">Alles in „Basic“ plus Abfrage- und Antworttext für die REST-Aufrufe</span><span class="sxs-lookup"><span data-stu-id="a035a-166">Everything in Basic plus request and response bodies for the REST calls</span></span>
| <span data-ttu-id="a035a-167">HttpLoggingDelegatingHandler.Level.Headers</span><span class="sxs-lookup"><span data-stu-id="a035a-167">HttpLoggingDelegatingHandler.Level.Headers</span></span> | <span data-ttu-id="a035a-168">Alles in „Basic“ plus Abfrage- und Antwortheader der REST-Aufrufe</span><span class="sxs-lookup"><span data-stu-id="a035a-168">Everything in Basic plus the request and response headers REST calls</span></span>
| <span data-ttu-id="a035a-169">HttpLoggingDelegatingHandler.Level.BodyAndHeaders</span><span class="sxs-lookup"><span data-stu-id="a035a-169">HttpLoggingDelegatingHandler.Level.BodyAndHeaders</span></span> | <span data-ttu-id="a035a-170">Alles auf den Protokollierungsebenen „Body“ und „Headers“</span><span class="sxs-lookup"><span data-stu-id="a035a-170">Everything in both Body and Headers log level</span></span>
