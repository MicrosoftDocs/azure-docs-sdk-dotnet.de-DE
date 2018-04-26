---
title: Azure Notification Hubs-Bibliotheken für .NET
description: Referenz für Azure Notification Hubs-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Notification Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: notification-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f863bf9d5d63129e04dd31ba96b3e803bead87bc
ms.sourcegitcommit: 4c42de7e066b6aa0a5b5df02cce4d1d245aa558d
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/18/2018
---
# <a name="azure-notification-hubs-libraries-for-net"></a>Azure Notification Hubs-Bibliotheken für .NET

Azure Notification Hubs bietet eine einfach zu bedienende, horizontal skalierte Push-Engine. Mit einem einzelnen plattformübergreifende API-Aufruf können Sie zielgerichtete und personalisierte Pushbenachrichtigungen aus einem beliebigen Cloud- oder lokalen Back-End an sämtliche mobile Plattformen senden.

## <a name="client-library"></a>Clientbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

> [!NOTE]
> Eine [neue Vorschauversion des NuGet-Pakets](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1) unterstützt nun .NET Standard, wodurch die Verwendung von .NET Core für die Back-End-Nutzung von Notifications Hubs ermöglicht wird

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird eine Verbindung mit einem Notification Hub hergestellt und eine Nachricht des Windows-Pushbenachrichtigungsdiensts (Windows Push Notification Service, WPNS) gesendet.

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a>Beispiele

- [Get Started with Notification Hubs Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal) (Erste Schritte mit Notification Hubs Windows Universal)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
