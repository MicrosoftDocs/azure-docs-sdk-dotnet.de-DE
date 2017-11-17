---
title: "Azure Recovery Services- und Backup-Bibliotheken für .NET"
description: "Referenz zu Azure Recovery Services- und Backup-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Recovery Services, Backup
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: recovery-services
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 3b399827f187fc2cb59c8698a555e63d08cee6c7
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-recovery-services-and-backup-libraries-for-net"></a><span data-ttu-id="dbfbb-104">Azure Recovery Services- und Backup-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="dbfbb-104">Azure Recovery Services and Backup libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="dbfbb-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="dbfbb-105">Overview</span></span>

<span data-ttu-id="dbfbb-106">Azure Recovery Services ist eine Suite mit Diensten für die Datenwiederherstellung und enthält u.a. [Azure Backup](/azure/backup/) und [Azure Site Recovery](/azure/site-recovery/).</span><span class="sxs-lookup"><span data-stu-id="dbfbb-106">Azure Recovery Services is a suite of services for data recovery, including [Azure Backup](/azure/backup/) and [Azure Site Recovery](/azure/site-recovery/).</span></span>

## <a name="management-library"></a><span data-ttu-id="dbfbb-107">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="dbfbb-107">Management library</span></span>

<span data-ttu-id="dbfbb-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="dbfbb-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="dbfbb-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="dbfbb-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

#### <a name="net-core-cli"></a><span data-ttu-id="dbfbb-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="dbfbb-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="dbfbb-111">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="dbfbb-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/recoveryservices/management)


## <a name="code-example"></a><span data-ttu-id="dbfbb-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="dbfbb-112">Code Example</span></span>

<span data-ttu-id="dbfbb-113">Das folgende Codebeispiel verwendet die Verwaltungsbibliothek zum Auslösen einer Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dbfbb-113">The following code example uses the management library to trigger a backup.</span></span>

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
