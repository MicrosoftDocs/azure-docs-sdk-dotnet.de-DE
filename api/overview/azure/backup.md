---
title: "Azure Backup-Bibliotheken für .NET"
description: "Referenz für Azure Backup-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Backup
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/24/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 93eeaeda1860e3b7190dfb0ae917b4b85b5a3609
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-backup-libraries-for-net"></a><span data-ttu-id="71845-104">Azure Backup-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="71845-104">Azure Backup libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="71845-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="71845-105">Overview</span></span>

<span data-ttu-id="71845-106">Azure Backup ist ein Clouddienst, den Sie zum Sichern, Schützen und Wiederherstellen Ihrer Daten verwenden können.</span><span class="sxs-lookup"><span data-stu-id="71845-106">Azure Backup is the cloud service you can use to back up, protect, and restore your data.</span></span>

<span data-ttu-id="71845-107">Weitere Informationen zu Azure Backup finden Sie unter [Übersicht über die Funktionen in Azure Backup](/azure/backup/backup-introduction-to-azure-backup).</span><span class="sxs-lookup"><span data-stu-id="71845-107">Learn more about Azure Backup by reading [What is Azure Backup?](/azure/backup/backup-introduction-to-azure-backup).</span></span>

## <a name="management-library"></a><span data-ttu-id="71845-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="71845-108">Management library</span></span>

<span data-ttu-id="71845-109">Verwenden Sie die Sicherungsverwaltungsbibliothek zur Verwaltung von Sicherungen, und richten Sie Recovery Services-Tresore ein.</span><span class="sxs-lookup"><span data-stu-id="71845-109">Use the backup management library to manage backups and set up Recovery Services vaults.</span></span>

<span data-ttu-id="71845-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices.Backup) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="71845-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices.Backup) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="71845-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="71845-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

<span data-ttu-id="71845-112">Das folgende Codebeispiel verwendet die Verwaltungsbibliothek zum Auslösen einer Sicherung.</span><span class="sxs-lookup"><span data-stu-id="71845-112">The following code example uses the management library to trigger a backup.</span></span>

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="71845-113">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="71845-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/backup/management)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
