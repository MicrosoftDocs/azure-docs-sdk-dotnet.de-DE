---
title: "Azure Service Fabric-Bibliotheken für .NET"
description: "Referenz für Azure Service Fabric-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Service Fabric
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: service-fabric
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f4b54933d31a4e1fc4c390baa57469cc1c02783a
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-service-fabric-libraries-for-net"></a><span data-ttu-id="91376-104">Azure Service Fabric-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="91376-104">Azure Service Fabric libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="91376-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="91376-105">Overview</span></span>

<span data-ttu-id="91376-106">Azure Service Fabric ist eine Plattform für verteilte Systeme, die das Packen, Bereitstellen und Verwalten skalierbarer und zuverlässiger Microservices und Container vereinfacht.</span><span class="sxs-lookup"><span data-stu-id="91376-106">Azure Service Fabric is a distributed systems platform that makes it easy to package, deploy, and manage scalable and reliable microservices and containers.</span></span>  <span data-ttu-id="91376-107">Weitere Informationen finden Sie in der [Dokumentation zu Azure Service Fabric](/azure/service-fabric/).</span><span class="sxs-lookup"><span data-stu-id="91376-107">For more information, see the [Azure Service Fabric Documentation](/azure/service-fabric/).</span></span>

## <a name="client-library"></a><span data-ttu-id="91376-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="91376-108">Client library</span></span>

<span data-ttu-id="91376-109">Verwenden Sie für die Interaktion mit einem vorhandenen Service Fabric-Cluster die Service Fabric-Clientbibliothek.</span><span class="sxs-lookup"><span data-stu-id="91376-109">Use the Service Fabric client library to interact with an existing Service Fabric cluster.</span></span>  <span data-ttu-id="91376-110">Die Bibliothek enthält drei Kategorien von APIs:</span><span class="sxs-lookup"><span data-stu-id="91376-110">The library contains three categories of APIs:</span></span>

* <span data-ttu-id="91376-111">**Client**-APIs werden zum Verwalten, Skalieren und Wiederverwenden des Clusters sowie zum Bereitstellen von Anwendungspaketen verwendet.</span><span class="sxs-lookup"><span data-stu-id="91376-111">**Client** APIs are used to manage, scale, and recycle the cluster, as well as deploy application packages.</span></span>
* <span data-ttu-id="91376-112">**Runtime**-APIs werden für die Interaktion der ausgeführten Anwendung mit ihrem Hostcluster verwendet.</span><span class="sxs-lookup"><span data-stu-id="91376-112">**Runtime** APIs are used for the running application to interact with its hosting cluster.</span></span>
* <span data-ttu-id="91376-113">**Allgemeine** APIs enthalten Typen, die sowohl in **Client**- als auch in **Runtime**-APIs verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="91376-113">**Common** APIs contain types used in both **client** and **runtime** APIs.</span></span>

<span data-ttu-id="91376-114">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.ServiceFabric) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="91376-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ServiceFabric) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="91376-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="91376-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ServiceFabric
```

```bash
dotnet add package Microsoft.ServiceFabric
```

### <a name="code-examples"></a><span data-ttu-id="91376-116">Codebeispiele</span><span class="sxs-lookup"><span data-stu-id="91376-116">Code Examples</span></span>

<span data-ttu-id="91376-117">Im folgenden Beispiel wird mithilfe der **Client**-APIs von Service Fabric ein Anwendungspaket in den Imagespeicher kopiert, der Anwendungstyp bereitgestellt und eine Instanz der Anwendung erstellt.</span><span class="sxs-lookup"><span data-stu-id="91376-117">The following example uses the Service Fabric **client** APIs to copy an application package to the image store, provisions the application type, and create an application instance.</span></span>

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
> [<span data-ttu-id="91376-118">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="91376-118">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicefabric/client)

<span data-ttu-id="91376-119">In diesem Beispiel werden die **Runtime**-APIs und die **allgemeinen** APIs von Service Fabric in einer gehosteten Anwendung verwendet, um zur Laufzeit eine [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="91376-119">This example uses the Service Fabric **runtime** and **common** APIs from within a hosted application to update a [Reliable Collection](/azure/service-fabric/service-fabric-reliable-services-reliable-collections) at runtime.</span></span>

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
> [<span data-ttu-id="91376-120">Erkunden der Runtime-APIs</span><span class="sxs-lookup"><span data-stu-id="91376-120">Explore the runtime APIs</span></span>](/dotnet/api/overview/azure/servicefabric/runtime)

> [!div class="nextstepaction"]
> [<span data-ttu-id="91376-121">Erkunden der allgemeinen APIs</span><span class="sxs-lookup"><span data-stu-id="91376-121">Explore the common APIs</span></span>](/dotnet/api/overview/azure/servicefabric/common)

## <a name="management-library"></a><span data-ttu-id="91376-122">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="91376-122">Management Library</span></span>

<span data-ttu-id="91376-123">Die Verwaltungsbibliothek wird zum Erstellen, Aktualisieren und Löschen von Service Fabric-Clustern verwendet.</span><span class="sxs-lookup"><span data-stu-id="91376-123">The management library is used to create, update, and delete Service Fabric clusters.</span></span>

<span data-ttu-id="91376-124">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="91376-124">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceFabric) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="91376-125">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="91376-125">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceFabric
```

```bash
dotnet add package Microsoft.Azure.Management.ServiceFabric
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="91376-126">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="91376-126">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicefabric/management)

## <a name="samples"></a><span data-ttu-id="91376-127">Beispiele</span><span class="sxs-lookup"><span data-stu-id="91376-127">Samples</span></span>

* [<span data-ttu-id="91376-128">Bereitstellen und Entfernen von Anwendungen mithilfe von FabricClient</span><span class="sxs-lookup"><span data-stu-id="91376-128">Deploy and remove applications using FabricClient</span></span>](/azure/service-fabric/service-fabric-deploy-remove-applications-fabricclient)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
