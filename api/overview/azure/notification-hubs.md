---
title: Azure Notification Hubs-Bibliotheken für .NET
description: Referenz für Azure Notification Hubs-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: notification-hubs
ms.openlocfilehash: 750a51e8dfa7323f6afb54735b4bfc517f9ec15f
ms.sourcegitcommit: 4b68c73652cb7e44cf4db36f70cb33a17dd863ce
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/19/2019
ms.locfileid: "58085837"
---
# <a name="azure-notification-hubs-libraries-for-net"></a><span data-ttu-id="4f928-103">Azure Notification Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="4f928-103">Azure Notification Hubs libraries for .NET</span></span>

<span data-ttu-id="4f928-104">Azure Notification Hubs bietet eine einfach zu bedienende, horizontal skalierte Push-Engine.</span><span class="sxs-lookup"><span data-stu-id="4f928-104">Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out push engine.</span></span> <span data-ttu-id="4f928-105">Mit einem einzelnen plattformübergreifende API-Aufruf können Sie zielgerichtete und personalisierte Pushbenachrichtigungen aus einem beliebigen Cloud- oder lokalen Back-End an sämtliche mobile Plattformen senden.</span><span class="sxs-lookup"><span data-stu-id="4f928-105">With a single cross-platform API call, you can easily send targeted and personalized push notifications to any mobile platform from any cloud or on-premises backend.</span></span>

## <a name="client-library"></a><span data-ttu-id="4f928-106">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="4f928-106">Client library</span></span>

<span data-ttu-id="4f928-107">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="4f928-107">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

> [!NOTE]
> <span data-ttu-id="4f928-108">Das [Microsoft Azure Notification Hubs-NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) unterstützt nun .NET Standard, wodurch die Verwendung von .NET Core für die Back-End-Nutzung von Notifications Hubs ermöglicht wird.</span><span class="sxs-lookup"><span data-stu-id="4f928-108">The [Azure Notification Hubs NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) now supports .NET Standard, which allows using .NET core for backend use of Notifications Hubs</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4f928-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="4f928-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a><span data-ttu-id="4f928-110">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="4f928-110">Code Example</span></span>

<span data-ttu-id="4f928-111">In diesem Beispiel wird eine Verbindung mit einem Notification Hub hergestellt und eine Nachricht des Windows-Pushbenachrichtigungsdiensts (Windows Push Notification Service, WPNS) gesendet.</span><span class="sxs-lookup"><span data-stu-id="4f928-111">This example connects to a Notification Hub and sends a Windows Push Notification Service (WNS) message.</span></span>

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4f928-112">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="4f928-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/client)

## <a name="management-library"></a><span data-ttu-id="4f928-113">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="4f928-113">Management library</span></span>

<span data-ttu-id="4f928-114">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="4f928-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4f928-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="4f928-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4f928-116">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="4f928-116">Explore the management APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a><span data-ttu-id="4f928-117">Beispiele</span><span class="sxs-lookup"><span data-stu-id="4f928-117">Samples</span></span>

- <span data-ttu-id="4f928-118">[Get Started with Notification Hubs Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal) (Erste Schritte mit Notification Hubs Windows Universal)</span><span class="sxs-lookup"><span data-stu-id="4f928-118">[Getting Started with Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
