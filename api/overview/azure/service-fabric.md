---
title: Azure Service Fabric-Bibliotheken für .NET
description: Referenz für Azure Service Fabric-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-fabric
ms.openlocfilehash: 064f95a4eae3182c4ac5b31779a5d22b592a75b2
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190763"
---
# <a name="azure-service-fabric-libraries-for-net"></a>Azure Service Fabric-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Service Fabric ist eine Plattform für verteilte Systeme, die das Packen, Bereitstellen und Verwalten skalierbarer und zuverlässiger Microservices und Container vereinfacht.  Weitere Informationen finden Sie in der [Dokumentation zu Azure Service Fabric](/azure/service-fabric/).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie für die Interaktion mit einem vorhandenen Service Fabric-Cluster die Service Fabric-Clientbibliothek.  Die Bibliothek enthält drei Kategorien von APIs:

* **Client**-APIs werden zum Verwalten, Skalieren und Wiederverwenden des Clusters sowie zum Bereitstellen von Anwendungspaketen verwendet.
* **Runtime**-APIs werden für die Interaktion der ausgeführten Anwendung mit ihrem Hostcluster verwendet.
* **Allgemeine** APIs enthalten Typen, die sowohl in **Client**- als auch in **Runtime**-APIs verwendet werden.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.ServiceFabric) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.ServiceFabric
```

```bash
dotnet add package Microsoft.ServiceFabric
```

### <a name="code-examples"></a>Codebeispiele

Im folgenden Beispiel wird mithilfe der **Client**-APIs von Service Fabric ein Anwendungspaket in den Imagespeicher kopiert, der Anwendungstyp bereitgestellt und eine Instanz der Anwendung erstellt.

```csharp
/* Include these dependencies
using System.Fabric;
using System.Fabric.Description;
*/

// Connect to the cluster.
FabricClient fabricClient = new FabricClient(clusterConnection);

// Copy the application package to a location in the image store
fabricClient.ApplicationManager.CopyApplicationPackage(imageStoreConnectionString, packagePath, packagePathInImageStore);

// Provision the application.
fabricClient.ApplicationManager.ProvisionApplicationAsync(packagePathInImageStore).Wait();

//  Create the application instance.
ApplicationDescription appDesc = new ApplicationDescription(new Uri(appName), appType, appVersion);
fabricClient.ApplicationManager.CreateApplicationAsync(appDesc).Wait();
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/servicefabric/client)

In diesem Beispiel werden die **Runtime**-APIs und die **allgemeinen** APIs von Service Fabric in einer gehosteten Anwendung verwendet, um zur Laufzeit eine [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) zu aktualisieren.

```csharp
using System.Fabric;
using Microsoft.ServiceFabric.Data.Collections;
using Microsoft.ServiceFabric.Services.Communication.Runtime;
using Microsoft.ServiceFabric.Services.Runtime;

/// <summary>
/// This is the main entry point for your service replica.
/// This method executes when this replica of your service becomes primary and has write status.
/// </summary>
/// <param name="cancellationToken">Canceled when Service Fabric needs to shut down this service replica.</param>
protected override async Task RunAsync(CancellationToken cancellationToken)
{
    var myDictionary = await this.StateManager.GetOrAddAsync<IReliableDictionary<string, long>>("myDictionary");
    while (true)
    {
        cancellationToken.ThrowIfCancellationRequested();
        using (var tx = this.StateManager.CreateTransaction())
        {
            var result = await myDictionary.TryGetValueAsync(tx, "Counter");
            await myDictionary.AddOrUpdateAsync(tx, "Counter", 0, (key, value) => ++value);

            // If an exception is thrown before calling CommitAsync, the transaction aborts, all changes are
            // discarded, and nothing is saved to the secondary replicas.
            await tx.CommitAsync();
        }
        await Task.Delay(TimeSpan.FromSeconds(1), cancellationToken);
    }
}
```

> [!div class="nextstepaction"]
> [Erkunden der Runtime-APIs](/dotnet/api/overview/azure/servicefabric/runtime)

> [!div class="nextstepaction"]
> [Erkunden der allgemeinen APIs](/dotnet/api/overview/azure/servicefabric/common)

## <a name="management-library"></a>Verwaltungsbibliothek

Die Verwaltungsbibliothek wird zum Erstellen, Aktualisieren und Löschen von Service Fabric-Clustern verwendet.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.ServiceFabric
```

```bash
dotnet add package Microsoft.Azure.Management.ServiceFabric
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/servicefabric/management)

## <a name="samples"></a>Beispiele

* [Bereitstellen und Entfernen von Anwendungen mithilfe von FabricClient](/azure/service-fabric/service-fabric-deploy-remove-applications-fabricclient)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
