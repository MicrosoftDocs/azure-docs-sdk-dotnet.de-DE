---
title: Azure Batch-Bibliotheken für .NET
description: Referenz für Azure Batch-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: batch
ms.openlocfilehash: 4220faacc9b8cbe394f98eaccd1e71aaf4ab8f0d
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190113"
---
# <a name="azure-batch-libraries-for-net"></a><span data-ttu-id="50073-103">Azure Batch-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="50073-103">Azure Batch libraries for .NET</span></span>

<span data-ttu-id="50073-104">Bei Azure Batch handelt es sich um eine Plattform zum Ausführen umfangreicher paralleler und leistungsstarker Anwendungen (High Performance Computing, HPC) in der Cloud.</span><span class="sxs-lookup"><span data-stu-id="50073-104">Azure Batch is a platform service for running large-scale parallel and high-performance computing (HPC) applications efficiently in the cloud.</span></span> <span data-ttu-id="50073-105">Azure Batch plant die Ausführung rechenintensiver Aufgaben auf einer verwalteten Sammlung virtueller Computer und kann Computeressourcen automatisch skalieren, um den Anforderungen Ihrer Aufträge gerecht zu werden.</span><span class="sxs-lookup"><span data-stu-id="50073-105">Azure Batch schedules compute-intensive work to run on a managed collection of virtual machines, and can automatically scale compute resources to meet the needs of your jobs.</span></span>

<span data-ttu-id="50073-106">Mit Azure Batch definieren Sie mühelos Azure-Computeressourcen für die parallele und bedarfsorientierte Ausführung Ihrer Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="50073-106">With Azure Batch, you can easily define Azure compute resources to execute your applications in parallel, and at scale.</span></span> <span data-ttu-id="50073-107">Es ist keine manuelle Erstellung, Konfiguration und Verwaltung eines HPC-Clusters, einzelner virtueller Computer, virtueller Netzwerke oder einer komplexen Infrastruktur für die Auftrags- und Aufgabenplanung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="50073-107">There's no need to manually create, configure, and manage an HPC cluster, individual virtual machines, virtual networks, or a complex job and task scheduling infrastructure.</span></span> <span data-ttu-id="50073-108">Azure Batch automatisiert oder vereinfacht diese Aufgaben für Sie.</span><span class="sxs-lookup"><span data-stu-id="50073-108">Azure Batch automates or simplifies these tasks for you.</span></span>

<span data-ttu-id="50073-109">Weitere Informationen finden Sie unter [Ausführen intrinsisch paralleler Workloads mit Batch](/azure/batch/batch-technical-overview).</span><span class="sxs-lookup"><span data-stu-id="50073-109">Read more about how to [run intrinsically parallel workloads with Batch](/azure/batch/batch-technical-overview).</span></span> <span data-ttu-id="50073-110">Sie können sich auch über [Erste Schritte zum Erstellen von Lösungen mit der Batch-Clientbibliothek für .NET](/azure/batch/batch-dotnet-get-started) informieren.</span><span class="sxs-lookup"><span data-stu-id="50073-110">You can also learn how to [get started building solutions with the Batch client library for .NET](/azure/batch/batch-dotnet-get-started).</span></span> <span data-ttu-id="50073-111">Lernen Sie auch das [Verwalten von Batch-Konten und -Kontingenten mit der Batch Management-Clientbibliothek für .NET](/azure/batch/batch-management-dotnet) kennen.</span><span class="sxs-lookup"><span data-stu-id="50073-111">Discover how to [manage Batch accounts and quotas with the Batch Management library for .NET](/azure/batch/batch-management-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="50073-112">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="50073-112">Client library</span></span>

<span data-ttu-id="50073-113">Verwenden Sie die Clientbibliothek zur Ausführung paralleler Workloads mit Batch.</span><span class="sxs-lookup"><span data-stu-id="50073-113">Use the client library to run parallel workloads with Batch.</span></span>

<span data-ttu-id="50073-114">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Azure.Batch) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="50073-114">Install the [NuGet package](https://www.nuget.org/packages/Azure.Batch) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="50073-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="50073-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Azure.Batch
```

#### <a name="net-core-cli"></a><span data-ttu-id="50073-116">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="50073-116">.NET Core CLI</span></span>

```bash
dotnet add package Azure.Batch
```

### <a name="example"></a><span data-ttu-id="50073-117">Beispiel</span><span class="sxs-lookup"><span data-stu-id="50073-117">Example</span></span>

<span data-ttu-id="50073-118">Im folgenden Beispiel wird das Client-SDK zum Erstellen eines Auftrags in Azure Batch ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="50073-118">The following example uses the client SDK to create a job to run in Azure Batch.</span></span>

```csharp
/*
using Microsoft.Azure.Batch.Auth;
using Microsoft.Azure.Batch;
*/
BatchSharedKeyCredentials credentials = new BatchSharedKeyCredentials(batchUrl, accountName, accountKey);
using (BatchClient batchClient = await BatchClient.OpenAsync(credentials))
{
    //set up pool specification and information along with resource files here
    JobManagerTask jobManagerTask = new JobManagerTask()
    {
        ResourceFiles = jobManagerResourceFiles,
        CommandLine = Constants.JobManagerExecutable,

        //Determines if the job should terminate when the job manager process exits.
        KillJobOnCompletion = true,
        Id = jobManagerTaskId
    };

    string jobId = Environment.GetEnvironmentVariable("USERNAME") + DateTime.UtcNow.ToString("yyyyMMdd-HHmmss");

    CloudJob unboundJob = batchClient.JobOperations.CreateJob(jobId, poolInformation);
    unboundJob.JobManagerTask = jobManagerTask;

    // now interact with the job ...
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="50073-119">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="50073-119">Explore the client APIs</span></span>](/dotnet/api/overview/azure/batch/client)

## <a name="management-library"></a><span data-ttu-id="50073-120">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="50073-120">Management library</span></span>

<span data-ttu-id="50073-121">Verwenden Sie die Verwaltungsbibliothek, um Batch-Konten, Kontingente und Anwendungspakete programmgesteuert zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="50073-121">Use the management library to programmatically manage Batch accounts, quotas, and application packages.</span></span>

<span data-ttu-id="50073-122">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="50073-122">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="50073-123">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="50073-123">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Batch
```

#### <a name="net-core-cli"></a><span data-ttu-id="50073-124">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="50073-124">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Batch
```

### <a name="example"></a><span data-ttu-id="50073-125">Beispiel</span><span class="sxs-lookup"><span data-stu-id="50073-125">Example</span></span>

<span data-ttu-id="50073-126">Im folgenden Beispiel wird das Kontingent für das Abonnement abgerufen, ein Konto erstellt und ein neuer primärer Kontoschlüssel generiert.</span><span class="sxs-lookup"><span data-stu-id="50073-126">The following example retrieves the quota for the subscription, creates an account, and regenerates the primary account key.</span></span>

```csharp
/*
using Microsoft.Azure.Management.Batch;
using Microsoft.Azure.Management.Batch.Models;
using Microsoft.Rest;
*/
using (BatchManagementClient batchManagementClient = new BatchManagementClient(new TokenCredentials(accessToken)))
{
    batchManagementClient.SubscriptionId = subscriptionId;

    // Get the account quota for the subscription
    BatchLocationQuota quotaResponse = await batchManagementClient.Location.GetQuotasAsync(location);
    Console.WriteLine("Your subscription can create {0} account(s) in the {1} region.", quotaResponse.AccountQuota, location);

    // Create account
    await batchManagementClient.BatchAccount.CreateAsync(ResourceGroupName, accountName, 
        new BatchAccountCreateParameters() { Location = location });

    // Regenerate primary account key
    BatchAccountKeys newKeys = await batchManagementClient.BatchAccount.RegenerateKeyAsync(
        ResourceGroupName, account.Name, AccountKeyType.Primary);
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="50073-127">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="50073-127">Explore the management APIs</span></span>](/dotnet/api/overview/azure/batch/management)

## <a name="samples"></a><span data-ttu-id="50073-128">Beispiele</span><span class="sxs-lookup"><span data-stu-id="50073-128">Samples</span></span>

* [<span data-ttu-id="50073-129">Azure Batch-Client- und Verwaltungs-SDK für .NET-Beispiele</span><span class="sxs-lookup"><span data-stu-id="50073-129">Azure Batch Client and Management SDK for .NET Samples</span></span>](https://github.com/Azure/azure-batch-samples/tree/master/CSharp)

<span data-ttu-id="50073-130">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="50073-130">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
