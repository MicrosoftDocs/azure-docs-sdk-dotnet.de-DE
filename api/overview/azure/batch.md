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
# <a name="azure-batch-libraries-for-net"></a>Azure Batch-Bibliotheken für .NET

Bei Azure Batch handelt es sich um eine Plattform zum Ausführen umfangreicher paralleler und leistungsstarker Anwendungen (High Performance Computing, HPC) in der Cloud. Azure Batch plant die Ausführung rechenintensiver Aufgaben auf einer verwalteten Sammlung virtueller Computer und kann Computeressourcen automatisch skalieren, um den Anforderungen Ihrer Aufträge gerecht zu werden.

Mit Azure Batch definieren Sie mühelos Azure-Computeressourcen für die parallele und bedarfsorientierte Ausführung Ihrer Anwendungen. Es ist keine manuelle Erstellung, Konfiguration und Verwaltung eines HPC-Clusters, einzelner virtueller Computer, virtueller Netzwerke oder einer komplexen Infrastruktur für die Auftrags- und Aufgabenplanung erforderlich. Azure Batch automatisiert oder vereinfacht diese Aufgaben für Sie.

Weitere Informationen finden Sie unter [Ausführen intrinsisch paralleler Workloads mit Batch](/azure/batch/batch-technical-overview). Sie können sich auch über [Erste Schritte zum Erstellen von Lösungen mit der Batch-Clientbibliothek für .NET](/azure/batch/batch-dotnet-get-started) informieren. Lernen Sie auch das [Verwalten von Batch-Konten und -Kontingenten mit der Batch Management-Clientbibliothek für .NET](/azure/batch/batch-management-dotnet) kennen.

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Clientbibliothek zur Ausführung paralleler Workloads mit Batch.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Azure.Batch) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Azure.Batch
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Azure.Batch
```

### <a name="example"></a>Beispiel

Im folgenden Beispiel wird das Client-SDK zum Erstellen eines Auftrags in Azure Batch ausgeführt.

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
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/batch/client)

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek, um Batch-Konten, Kontingente und Anwendungspakete programmgesteuert zu verwalten.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Batch) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Batch
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.Batch
```

### <a name="example"></a>Beispiel

Im folgenden Beispiel wird das Kontingent für das Abonnement abgerufen, ein Konto erstellt und ein neuer primärer Kontoschlüssel generiert.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/batch/management)

## <a name="samples"></a>Beispiele

* [Azure Batch-Client- und Verwaltungs-SDK für .NET-Beispiele](https://github.com/Azure/azure-batch-samples/tree/master/CSharp)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
