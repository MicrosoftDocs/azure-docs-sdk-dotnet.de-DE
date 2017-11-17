---
title: "Azure Notification Hubs-Bibliotheken für .NET"
description: "Referenz für Azure Notification Hubs-Bibliotheken für .NET"
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
ms.openlocfilehash: 6fe4e3f25aa420322478dc7c10aecd055a70f5c8
ms.sourcegitcommit: 4114b8821f20e02f4185fcea7549d716f29b9c90
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/24/2017
---
# <a name="azure-notification-hubs-libraries-for-net"></a><span data-ttu-id="dbfa9-104">Azure Notification Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="dbfa9-104">Azure Notification Hubs libraries for .NET</span></span>

<span data-ttu-id="dbfa9-105">Azure Notification Hubs bietet ein einfach zu bedienendes, horizontal skaliertes Pushmodul.</span><span class="sxs-lookup"><span data-stu-id="dbfa9-105">Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out push engine.</span></span> <span data-ttu-id="dbfa9-106">Mit einem einzelnen plattformübergreifende API-Aufruf können Sie zielgerichtete und personalisierte Pushbenachrichtigungen aus einem beliebigen Cloud- oder lokalen Back-End an sämtliche mobile Plattformen senden.</span><span class="sxs-lookup"><span data-stu-id="dbfa9-106">With a single cross-platform API call, you can easily send targeted and personalized push notifications to any mobile platform from any cloud or on-premises backend.</span></span>

## <a name="client-library"></a><span data-ttu-id="dbfa9-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="dbfa9-107">Client library</span></span>

<span data-ttu-id="dbfa9-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="dbfa9-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="dbfa9-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="dbfa9-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a><span data-ttu-id="dbfa9-110">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="dbfa9-110">Code Example</span></span>

<span data-ttu-id="dbfa9-111">In diesem Beispiel wird eine Verbindung mit einer Datenbank hergestellt. Anschließend werden Zeilen in einer Tabelle gelesen.</span><span class="sxs-lookup"><span data-stu-id="dbfa9-111">This example connects to a database and reads rows from a table.</span></span>

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="dbfa9-112">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="dbfa9-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a><span data-ttu-id="dbfa9-113">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="dbfa9-113">Management library</span></span>

<span data-ttu-id="dbfa9-114">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="dbfa9-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="dbfa9-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="dbfa9-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="dbfa9-116">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="dbfa9-116">Explore the management APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a><span data-ttu-id="dbfa9-117">Beispiele</span><span class="sxs-lookup"><span data-stu-id="dbfa9-117">Samples</span></span>

- <span data-ttu-id="dbfa9-118">[Get Started with Notification Hubs Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal) (Erste Schritte mit Notification Hubs Windows Universal)</span><span class="sxs-lookup"><span data-stu-id="dbfa9-118">[Getting Started with Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
