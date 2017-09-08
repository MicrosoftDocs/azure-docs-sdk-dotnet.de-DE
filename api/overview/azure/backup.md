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
# <a name="azure-backup-libraries-for-net"></a>Azure Backup-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Backup ist ein Clouddienst, den Sie zum Sichern, Schützen und Wiederherstellen Ihrer Daten verwenden können.

Weitere Informationen zu Azure Backup finden Sie unter [Übersicht über die Funktionen in Azure Backup](/azure/backup/backup-introduction-to-azure-backup).

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Sicherungsverwaltungsbibliothek zur Verwaltung von Sicherungen, und richten Sie Recovery Services-Tresore ein.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.RecoveryServices.Backup) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.RecoveryServices.Backup
```

```bash
dotnet add package Microsoft.Azure.Management.RecoveryServices.Backup
```

Das folgende Codebeispiel verwendet die Verwaltungsbibliothek zum Auslösen einer Sicherung.

```csharp
RecoveryServicesBackupManagementClient client = new RecoveryServicesBackupManagementClient(credentials);
TriggerBackupRequest triggerBackupRequest = new TriggerBackupRequest();
BaseRecoveryServicesJobResponse resp =
    await client.Backups.TriggerBackupAsync(resourceGroupName, resourceName, null,
        fabricName, containerName, protectedItemName, triggerBackupRequest);
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/backup/management)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
