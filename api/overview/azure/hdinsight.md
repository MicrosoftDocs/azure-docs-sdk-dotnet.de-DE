---
title: Azure HD Insight-Bibliotheken für .NET
description: Referenz für HD Insight-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, HDInsight
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: hd-insight
ms.custom: devcenter, svc-overview
ms.openlocfilehash: da9023ab4e6106754d48acb31cda58cdb358f5cb
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
ms.locfileid: "23486953"
---
# <a name="azure-hdinsight-libraries-for-net"></a><span data-ttu-id="d65b0-104">Azure HD Insight-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="d65b0-104">Azure HDInsight libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="d65b0-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="d65b0-105">Overview</span></span>

<span data-ttu-id="d65b0-106">Das HDInsight-Dienst-.NET-SDK bietet Klassen, die sich auf Erstellung, Konfiguration, Übermittlung und Überwachung von Hadoop-Aufträgen beziehen, die von einem Azure HDInsight-Dienst verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="d65b0-106">The HDInsight Service .NET SDK provides classes that relate to the creation, configuration, submission, and monitoring of Hadoop jobs managed by an Azure HDInsight Service.</span></span> <span data-ttu-id="d65b0-107">Darüber hinaus bietet sie Klassen zum Verwalten von Azure-Abonnements mithilfe des HDInsight-Diensts, und zum Konfigurieren der Cluster, Speicherkonten und sonstigen Ressourcen, die den HDInsight-Clustern zugeordnet sind, die von einem Azure-Abonnement verwaltet werden.</span><span class="sxs-lookup"><span data-stu-id="d65b0-107">In addition, it provides classes to manage Azure subscriptions using the HDInsight Service and to configure the clusters, storage accounts, and other assets associated with the HDInsight clusters that are managed by an Azure subscription.</span></span>

## <a name="management-libraries"></a><span data-ttu-id="d65b0-108">Verwaltungsbibliotheken</span><span class="sxs-lookup"><span data-stu-id="d65b0-108">Management libraries</span></span>

### <a name="jobs"></a><span data-ttu-id="d65b0-109">Aufträge</span><span class="sxs-lookup"><span data-stu-id="d65b0-109">Jobs</span></span>

<span data-ttu-id="d65b0-110">Verwenden Sie das Azure HDInsight-Client-SDK zum Erstellen, verwalten und Überwachen von Aufträgen in einem Hadoop-Cluster.</span><span class="sxs-lookup"><span data-stu-id="d65b0-110">Use the Azure HDInsight client SDK to create, manage, and monitor jobs on a Hadoop cluster.</span></span> 

<span data-ttu-id="d65b0-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="d65b0-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="d65b0-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="d65b0-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

#### <a name="code-example"></a><span data-ttu-id="d65b0-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="d65b0-113">Code Example</span></span>

<span data-ttu-id="d65b0-114">In diesem Beispiel wird ein Hive-Auftrag in einem Hadoop-Cluster ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="d65b0-114">This example runs a Hive job in a Hadoop cluster.</span></span>

```csharp
HDInsightJobManagementClient managementClient = new HDInsightJobManagementClient(clusterUri, credentials);

Dictionary<string, string> defines = new Dictionary<string, string> {
    { "hive.execution.engine", "tez" },
    { "hive.exec.reducers.max", "1" }
};
List<string> arguments = new List<string> { { "argA" }, { "argB" } };
HiveJobSubmissionParameters parameters = new HiveJobSubmissionParameters
{
    Query = "SHOW TABLES",
    Defines = defines,
    Arguments = arguments
};

JobSubmissionResponse jobResponse = managementClient.JobManagement.SubmitHiveJob(parameters);
```

### <a name="hdinsight"></a><span data-ttu-id="d65b0-115">HDInsight</span><span class="sxs-lookup"><span data-stu-id="d65b0-115">HDInsight</span></span>

<span data-ttu-id="d65b0-116">Verwenden Sie das Azure HDInsight-Verwaltungs-SDK zum Erstellen, Verwalten, Starten, Beenden und Skalieren von Hadoop-Clustern.</span><span class="sxs-lookup"><span data-stu-id="d65b0-116">Use the Azure HDInsight management SDK to create, manage, start, stop, and scale Hadoop clusters.</span></span>

<span data-ttu-id="d65b0-117">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="d65b0-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="d65b0-118">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="d65b0-118">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
```

#### <a name="code-example"></a><span data-ttu-id="d65b0-119">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="d65b0-119">Code Example</span></span>

<span data-ttu-id="d65b0-120">In diesem Beispiel wird ein HDInsight-Linux-Hadoop-Cluster mit zwei Knoten mit einem vorhandenen Azure Blob Storage erstellt.</span><span class="sxs-lookup"><span data-stu-id="d65b0-120">This example creates an HDInsight two node Linux Hadoop cluster with an existing Azure Blob Storage.</span></span>

```csharp
HDInsightManagementClient managementClient = new HDInsightManagementClient(authToken);
// Set parameters for the new cluster
ClusterCreateParameters parameters = new ClusterCreateParameters
{
    ClusterSizeInNodes = 2,
    UserName = "admin",
    Password = "<Enter HTTP User Password>",
    ClusterType = "Hadoop",
    OSType = OSType.Linux,
    Version = "3.5",
    // Use an Azure storage account as the default storage
    DefaultStorageInfo = new AzureStorageInfo("<StorageAccount>", "<StorageKey>", "<BlobContainerName>"),
    Location = "EAST US 2",
    SshUserName = "sshuser",
    SshPassword = "<Enter SSH User Password>",
};

// Create the cluster
managementClient.Clusters.Create("<ExistingResourceGroupName>", "<NewClusterName>", parameters);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="d65b0-121">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="d65b0-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/hdinsights/management)


## <a name="samples"></a><span data-ttu-id="d65b0-122">Beispiele</span><span class="sxs-lookup"><span data-stu-id="d65b0-122">Samples</span></span>

- [<span data-ttu-id="d65b0-123">Erstellen von Linux-basierten Clustern in HDInsight mit dem .NET-SDK</span><span class="sxs-lookup"><span data-stu-id="d65b0-123">Cluster creation</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-dotnet-sdk)
- [<span data-ttu-id="d65b0-124">Verwalten von Hadoop-Clustern in HDInsight mit .NET-SDK</span><span class="sxs-lookup"><span data-stu-id="d65b0-124">Cluster management</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-administer-use-dotnet-sdk)
- [<span data-ttu-id="d65b0-125">Ausführen von Hive-Abfragen per HDInsight .NET-SDK</span><span class="sxs-lookup"><span data-stu-id="d65b0-125">Run Hive jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [<span data-ttu-id="d65b0-126">Ausführen von Pig-Aufträgen mithilfe des .NET-SDK für Hadoop in HDInsight</span><span class="sxs-lookup"><span data-stu-id="d65b0-126">Run Pig jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [<span data-ttu-id="d65b0-127">Übermitteln von Hadoop-Aufträgen in HDInsight</span><span class="sxs-lookup"><span data-stu-id="d65b0-127">More jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)

<span data-ttu-id="d65b0-128">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight) von Beispielen für Azure SQL-Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="d65b0-128">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight) of Azure SQL Database samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
