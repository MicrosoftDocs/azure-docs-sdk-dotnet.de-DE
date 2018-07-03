---
title: Azure HD Insight-Bibliotheken für .NET
description: Referenz für HD Insight-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, HDInsight
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: hd-insight
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2cdb080b4d224a77a36318cefd13ebfae2e3e2e1
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065810"
---
# <a name="azure-hdinsight-libraries-for-net"></a>Azure HD Insight-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Das HDInsight-Dienst-.NET-SDK bietet Klassen, die sich auf Erstellung, Konfiguration, Übermittlung und Überwachung von Hadoop-Aufträgen beziehen, die von einem Azure HDInsight-Dienst verwaltet werden. Darüber hinaus bietet sie Klassen zum Verwalten von Azure-Abonnements mithilfe des HDInsight-Diensts, und zum Konfigurieren der Cluster, Speicherkonten und sonstigen Ressourcen, die den HDInsight-Clustern zugeordnet sind, die von einem Azure-Abonnement verwaltet werden.

## <a name="management-libraries"></a>Verwaltungsbibliotheken

### <a name="jobs"></a>Aufträge

Verwenden Sie das Azure HDInsight-Client-SDK zum Erstellen, verwalten und Überwachen von Aufträgen in einem Hadoop-Cluster. 

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

#### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird ein Hive-Auftrag in einem Hadoop-Cluster ausgeführt.

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

### <a name="hdinsight"></a>HDInsight

Verwenden Sie das Azure HDInsight-Verwaltungs-SDK zum Erstellen, Verwalten, Starten, Beenden und Skalieren von Hadoop-Clustern.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
```

#### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird ein HDInsight-Linux-Hadoop-Cluster mit zwei Knoten mit einem vorhandenen Azure Blob Storage erstellt.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/hdinsights/management)


## <a name="samples"></a>Beispiele

- [Erstellen von Linux-basierten Clustern in HDInsight mit dem .NET-SDK](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-dotnet-sdk)
- [Verwalten von Hadoop-Clustern in HDInsight mit .NET-SDK](https://docs.microsoft.com/azure/hdinsight/hdinsight-administer-use-dotnet-sdk)
- [Ausführen von Hive-Abfragen per HDInsight .NET-SDK](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [Ausführen von Pig-Aufträgen mithilfe des .NET-SDK für Hadoop in HDInsight](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [Übermitteln von Hadoop-Aufträgen in HDInsight](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight) von Beispielen für Azure SQL-Datenbank an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
