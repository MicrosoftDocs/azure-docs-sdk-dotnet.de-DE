---
title: Azure Recovery Services- und Backup-Bibliotheken für .NET
description: Referenz zu Azure Recovery Services- und Backup-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: backup
ms.openlocfilehash: c2faef5c83f28cb35158609b92f0334671161d1d
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348172"
---
# <a name="azure-recovery-services-and-backup-libraries-for-net"></a><span data-ttu-id="aec35-103">Azure Recovery Services- und Backup-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="aec35-103">Azure Recovery Services and Backup libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="aec35-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="aec35-104">Overview</span></span>

<span data-ttu-id="aec35-105">Azure Recovery Services ist eine Suite mit Diensten für die Datenwiederherstellung und enthält u.a. [Azure Backup](/azure/backup/) und [Azure Site Recovery](/azure/site-recovery/).</span><span class="sxs-lookup"><span data-stu-id="aec35-105">Azure Recovery Services is a suite of services for data recovery, including [Azure Backup](/azure/backup/) and [Azure Site Recovery](/azure/site-recovery/).</span></span>

## <a name="management-library"></a><span data-ttu-id="aec35-106">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="aec35-106">Management library</span></span>

<span data-ttu-id="aec35-107">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="aec35-107">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="aec35-108">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="aec35-108">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

#### <a name="net-core-cli"></a><span data-ttu-id="aec35-109">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="aec35-109">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="aec35-110">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="aec35-110">Explore the management APIs</span></span>](/dotnet/api/overview/azure/recoveryservices/management)


## <a name="code-example"></a><span data-ttu-id="aec35-111">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="aec35-111">Code Example</span></span>

<span data-ttu-id="aec35-112">Das folgende Codebeispiel verwendet die Verwaltungsbibliothek zum Auslösen einer Sicherung.</span><span class="sxs-lookup"><span data-stu-id="aec35-112">The following code example uses the management library to trigger a backup.</span></span>

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
