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
# <a name="azure-service-fabric-libraries-for-net"></a><span data-ttu-id="7dff4-103">Azure Service Fabric-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="7dff4-103">Azure Service Fabric libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="7dff4-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="7dff4-104">Overview</span></span>

<span data-ttu-id="7dff4-105">Azure Service Fabric ist eine Plattform für verteilte Systeme, die das Packen, Bereitstellen und Verwalten skalierbarer und zuverlässiger Microservices und Container vereinfacht.</span><span class="sxs-lookup"><span data-stu-id="7dff4-105">Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers.</span></span>  <span data-ttu-id="7dff4-106">Weitere Informationen finden Sie in der [Dokumentation zu Azure Service Fabric](/azure/service-fabric/).</span><span class="sxs-lookup"><span data-stu-id="7dff4-106">For more information, see the [Azure Service Fabric Documentation](/azure/service-fabric/).</span></span>

## <a name="client-library"></a><span data-ttu-id="7dff4-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="7dff4-107">Client library</span></span>

<span data-ttu-id="7dff4-108">Verwenden Sie für die Interaktion mit einem vorhandenen Service Fabric-Cluster die Service Fabric-Clientbibliothek.</span><span class="sxs-lookup"><span data-stu-id="7dff4-108">Use the Service Fabric client library to interact with an existing Service Fabric cluster.</span></span>  <span data-ttu-id="7dff4-109">Die Bibliothek enthält drei Kategorien von APIs:</span><span class="sxs-lookup"><span data-stu-id="7dff4-109">The library contains three categories of APIs:</span></span>

* <span data-ttu-id="7dff4-110">**Client**-APIs werden zum Verwalten, Skalieren und Wiederverwenden des Clusters sowie zum Bereitstellen von Anwendungspaketen verwendet.</span><span class="sxs-lookup"><span data-stu-id="7dff4-110">**Client** APIs are used to manage, scale, and recycle the cluster, as well as deploy application packages.</span></span>
* <span data-ttu-id="7dff4-111">**Runtime**-APIs werden für die Interaktion der ausgeführten Anwendung mit ihrem Hostcluster verwendet.</span><span class="sxs-lookup"><span data-stu-id="7dff4-111">**Runtime** APIs are used for the running application to interact with its hosting cluster.</span></span>
* <span data-ttu-id="7dff4-112">**Allgemeine** APIs enthalten Typen, die sowohl in **Client**- als auch in **Runtime**-APIs verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="7dff4-112">**Common** APIs contain types used in both **client** and **runtime** APIs.</span></span>

<span data-ttu-id="7dff4-113">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.ServiceFabric) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="7dff4-113">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ServiceFabric) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="7dff4-114">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="7dff4-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ServiceFabric
```

```bash
dotnet add package Microsoft.ServiceFabric
```

### <a name="code-examples"></a><span data-ttu-id="7dff4-115">Codebeispiele</span><span class="sxs-lookup"><span data-stu-id="7dff4-115">Code Examples</span></span>

<span data-ttu-id="7dff4-116">Im folgenden Beispiel wird mithilfe der **Client**-APIs von Service Fabric ein Anwendungspaket in den Imagespeicher kopiert, der Anwendungstyp bereitgestellt und eine Instanz der Anwendung erstellt.</span><span class="sxs-lookup"><span data-stu-id="7dff4-116">The following example uses the Service Fabric **client** APIs to copy an application package to the image store, provisions the application type, and create an application instance.</span></span>

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
> [<span data-ttu-id="7dff4-117">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="7dff4-117">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicefabric/client)

<span data-ttu-id="7dff4-118">In diesem Beispiel werden die **Runtime**-APIs und die **allgemeinen** APIs von Service Fabric in einer gehosteten Anwendung verwendet, um zur Laufzeit eine [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7dff4-118">This example uses the Service Fabric **runtime** and **common** APIs from within a hosted application to update a [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) at runtime.</span></span>

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
> [<span data-ttu-id="7dff4-119">Erkunden der Runtime-APIs</span><span class="sxs-lookup"><span data-stu-id="7dff4-119">Explore the runtime APIs</span></span>](/dotnet/api/overview/azure/servicefabric/runtime)

> [!div class="nextstepaction"]
> [<span data-ttu-id="7dff4-120">Erkunden der allgemeinen APIs</span><span class="sxs-lookup"><span data-stu-id="7dff4-120">Explore the common APIs</span></span>](/dotnet/api/overview/azure/servicefabric/common)

## <a name="management-library"></a><span data-ttu-id="7dff4-121">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="7dff4-121">Management Library</span></span>

<span data-ttu-id="7dff4-122">Die Verwaltungsbibliothek wird zum Erstellen, Aktualisieren und Löschen von Service Fabric-Clustern verwendet.</span><span class="sxs-lookup"><span data-stu-id="7dff4-122">The management library is used to create, update, and delete Service Fabric clusters.</span></span>

<span data-ttu-id="7dff4-123">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="7dff4-123">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="7dff4-124">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="7dff4-124">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceFabric
```

```bash
dotnet add package Microsoft.Azure.Management.ServiceFabric
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="7dff4-125">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="7dff4-125">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicefabric/management)

## <a name="samples"></a><span data-ttu-id="7dff4-126">Beispiele</span><span class="sxs-lookup"><span data-stu-id="7dff4-126">Samples</span></span>

* [<span data-ttu-id="7dff4-127">Bereitstellen und Entfernen von Anwendungen mithilfe von FabricClient</span><span class="sxs-lookup"><span data-stu-id="7dff4-127">Deploy and remove applications using FabricClient</span></span>](/azure/service-fabric/service-fabric-deploy-remove-applications-fabricclient)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
