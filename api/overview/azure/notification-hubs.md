---
title: Azure Notification Hubs-Bibliotheken für .NET
description: Referenz für Azure Notification Hubs-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Notification Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: notification-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 0cbbfbafd2d1900c00f08fd1ab2e0f1af80ae8ff
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065500"
---
# <a name="azure-notification-hubs-libraries-for-net"></a><span data-ttu-id="fed4f-104">Azure Notification Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="fed4f-104">Azure Notification Hubs libraries for .NET</span></span>

<span data-ttu-id="fed4f-105">Azure Notification Hubs bietet eine einfach zu bedienende, horizontal skalierte Push-Engine.</span><span class="sxs-lookup"><span data-stu-id="fed4f-105">Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out push engine.</span></span> <span data-ttu-id="fed4f-106">Mit einem einzelnen plattformübergreifende API-Aufruf können Sie zielgerichtete und personalisierte Pushbenachrichtigungen aus einem beliebigen Cloud- oder lokalen Back-End an sämtliche mobile Plattformen senden.</span><span class="sxs-lookup"><span data-stu-id="fed4f-106">With a single cross-platform API call, you can easily send targeted and personalized push notifications to any mobile platform from any cloud or on-premises backend.</span></span>

## <a name="client-library"></a><span data-ttu-id="fed4f-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="fed4f-107">Client library</span></span>

<span data-ttu-id="fed4f-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="fed4f-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

> [!NOTE]
> <span data-ttu-id="fed4f-109">Eine [neue Vorschauversion des NuGet-Pakets](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1) unterstützt nun .NET Standard, wodurch die Verwendung von .NET Core für die Back-End-Nutzung von Notifications Hubs ermöglicht wird</span><span class="sxs-lookup"><span data-stu-id="fed4f-109">A [new preview version of the NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1) now supports .NET Standard, which allows using .NET core for backend use of Notifications Hubs</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="fed4f-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="fed4f-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a><span data-ttu-id="fed4f-111">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="fed4f-111">Code Example</span></span>

<span data-ttu-id="fed4f-112">In diesem Beispiel wird eine Verbindung mit einem Notification Hub hergestellt und eine Nachricht des Windows-Pushbenachrichtigungsdiensts (Windows Push Notification Service, WPNS) gesendet.</span><span class="sxs-lookup"><span data-stu-id="fed4f-112">This example connects to a Notification Hub and sends a Windows Push Notification Service (WNS) message.</span></span>

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="fed4f-113">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="fed4f-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a><span data-ttu-id="fed4f-114">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="fed4f-114">Management library</span></span>

<span data-ttu-id="fed4f-115">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="fed4f-115">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="fed4f-116">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="fed4f-116">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="fed4f-117">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="fed4f-117">Explore the management APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a><span data-ttu-id="fed4f-118">Beispiele</span><span class="sxs-lookup"><span data-stu-id="fed4f-118">Samples</span></span>

- <span data-ttu-id="fed4f-119">[Get Started with Notification Hubs Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal) (Erste Schritte mit Notification Hubs Windows Universal)</span><span class="sxs-lookup"><span data-stu-id="fed4f-119">[Getting Started with Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
