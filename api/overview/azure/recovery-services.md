---
title: Azure Recovery Services- und Backup-Bibliotheken für .NET
description: Referenz zu Azure Recovery Services- und Backup-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: recovery-services
ms.openlocfilehash: c0381ce9a566b5371faca24307edc7b26174e785
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190791"
---
# <a name="azure-recovery-services-and-backup-libraries-for-net"></a>Azure Recovery Services- und Backup-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Recovery Services ist eine Suite mit Diensten für die Datenwiederherstellung und enthält u.a. [Azure Backup](/azure/backup/) und [Azure Site Recovery](/azure/site-recovery/).

## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/recoveryservices/management)


## <a name="code-example"></a>Codebeispiel

Das folgende Codebeispiel verwendet die Verwaltungsbibliothek zum Auslösen einer Sicherung.

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
