---
title: "Azure Batch-Bibliotheken für .NET"
description: "Referenz für Azure Batch-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Batch
author: camsoper
ms.author: casoper
manager: douge
ms.date: 08/01/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 753721d430de0577c0bc1dd3774d728783a3bfee
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-batch-libraries-for-net"></a><span data-ttu-id="41c23-104">Azure Batch-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="41c23-104">Azure Batch libraries for .NET</span></span>

<span data-ttu-id="41c23-105">Bei Azure Batch handelt es sich um eine Plattform zum Ausführen umfangreicher paralleler und leistungsstarker Anwendungen (High Performance Computing, HPC) in der Cloud.</span><span class="sxs-lookup"><span data-stu-id="41c23-105">Azure Batch is a platform service for running large-scale parallel and high-performance computing (HPC) applications efficiently in the cloud.</span></span> <span data-ttu-id="41c23-106">Azure Batch plant die Ausführung rechenintensiver Aufgaben auf einer verwalteten Sammlung virtueller Computer und kann Computeressourcen automatisch skalieren, um den Anforderungen Ihrer Aufträge gerecht zu werden.</span><span class="sxs-lookup"><span data-stu-id="41c23-106">Azure Batch schedules compute-intensive work to run on a managed collection of virtual machines, and can automatically scale compute resources to meet the needs of your jobs.</span></span>

<span data-ttu-id="41c23-107">Mit Azure Batch definieren Sie mühelos Azure-Computeressourcen für die parallele und bedarfsorientierte Ausführung Ihrer Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="41c23-107">With Azure Batch, you can easily define Azure compute resources to execute your applications in parallel, and at scale.</span></span> <span data-ttu-id="41c23-108">Es ist keine manuelle Erstellung, Konfiguration und Verwaltung eines HPC-Clusters, einzelner virtueller Computer, virtueller Netzwerke oder einer komplexen Infrastruktur für die Auftrags- und Aufgabenplanung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="41c23-108">There's no need to manually create, configure, and manage an HPC cluster, individual virtual machines, virtual networks, or a complex job and task scheduling infrastructure.</span></span> <span data-ttu-id="41c23-109">Azure Batch automatisiert oder vereinfacht diese Aufgaben für Sie.</span><span class="sxs-lookup"><span data-stu-id="41c23-109">Azure Batch automates or simplifies these tasks for you.</span></span>

<span data-ttu-id="41c23-110">Weitere Informationen finden Sie unter [Ausführen intrinsisch paralleler Workloads mit Batch](/azure/batch/batch-technical-overview).</span><span class="sxs-lookup"><span data-stu-id="41c23-110">Read more about how to [run intrinsically parallel workloads with Batch](/azure/batch/batch-technical-overview).</span></span> <span data-ttu-id="41c23-111">Sie können sich auch über [Erste Schritte zum Erstellen von Lösungen mit der Batch-Clientbibliothek für .NET](/azure/batch/batch-dotnet-get-started) informieren.</span><span class="sxs-lookup"><span data-stu-id="41c23-111">You can also learn how to [get started building solutions with the Batch client library for .NET](/azure/batch/batch-dotnet-get-started).</span></span> <span data-ttu-id="41c23-112">Lernen Sie auch das [Verwalten von Batch-Konten und -Kontingenten mit der Batch Management-Clientbibliothek für .NET](/azure/batch/batch-management-dotnet) kennen.</span><span class="sxs-lookup"><span data-stu-id="41c23-112">Discover how to [manage Batch accounts and quotas with the Batch Management library for .NET](/azure/batch/batch-management-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="41c23-113">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="41c23-113">Client library</span></span>

<span data-ttu-id="41c23-114">Verwenden Sie die Clientbibliothek zur Ausführung paralleler Workloads mit Batch.</span><span class="sxs-lookup"><span data-stu-id="41c23-114">Use the client library to run parallel workloads with Batch.</span></span>

<span data-ttu-id="41c23-115">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Azure.Batch) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="41c23-115">Install the [NuGet package](https://www.nuget.org/packages/Azure.Batch) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="41c23-116">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="41c23-116">Visual Studio Package Manager</span></span>

```powershell
Install-Package Azure.Batch
```

#### <a name="net-core-cli"></a><span data-ttu-id="41c23-117">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="41c23-117">.NET Core CLI</span></span>

```bash
dotnet add package Azure.Batch
```

### <a name="example"></a><span data-ttu-id="41c23-118">Beispiel</span><span class="sxs-lookup"><span data-stu-id="41c23-118">Example</span></span>

<span data-ttu-id="41c23-119">Im folgenden Beispiel wird das Client-SDK zum Erstellen eines Auftrags in Azure Batch ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="41c23-119">The following example uses the client SDK to create a job to run in Azure Batch.</span></span>

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
> [<span data-ttu-id="41c23-120">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="41c23-120">Explore the client APIs</span></span>](/dotnet/api/overview/azure/batch/client)

## <a name="management-library"></a><span data-ttu-id="41c23-121">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="41c23-121">Management library</span></span>

<span data-ttu-id="41c23-122">Verwenden Sie die Verwaltungsbibliothek, um Batch-Konten, Kontingente und Anwendungspakete programmgesteuert zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="41c23-122">Use the management library to programmatically manage Batch accounts, quotas, and application packages.</span></span>

<span data-ttu-id="41c23-123">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="41c23-123">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="41c23-124">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="41c23-124">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Batch
```

#### <a name="net-core-cli"></a><span data-ttu-id="41c23-125">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="41c23-125">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Batch
```

### <a name="example"></a><span data-ttu-id="41c23-126">Beispiel</span><span class="sxs-lookup"><span data-stu-id="41c23-126">Example</span></span>

<span data-ttu-id="41c23-127">Im folgenden Beispiel wird das Kontingent für das Abonnement abgerufen, ein Konto erstellt und ein neuer primärer Kontoschlüssel generiert.</span><span class="sxs-lookup"><span data-stu-id="41c23-127">The following example retrieves the quota for the subscription, creates an account, and regenerates the primary account key.</span></span>

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
> [<span data-ttu-id="41c23-128">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="41c23-128">Explore the management APIs</span></span>](/dotnet/api/overview/azure/batch/management)

## <a name="samples"></a><span data-ttu-id="41c23-129">Beispiele</span><span class="sxs-lookup"><span data-stu-id="41c23-129">Samples</span></span>

* [<span data-ttu-id="41c23-130">Azure Batch-Client- und Verwaltungs-SDK für .NET-Beispiele</span><span class="sxs-lookup"><span data-stu-id="41c23-130">Azure Batch Client and Management SDK for .NET Samples</span></span>](https://github.com/Azure/azure-batch-samples/tree/master/CSharp)

<span data-ttu-id="41c23-131">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="41c23-131">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
