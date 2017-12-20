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
ms.openlocfilehash: 9fd49ccc8d02eff09a8a53e6f1b9baa6a7a59082
ms.sourcegitcommit: 33732307162ddf6f272b0e9cc7f74eb8e6fdda1b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/12/2017
---
# <a name="azure-notification-hubs-libraries-for-net"></a><span data-ttu-id="459eb-104">Azure Notification Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="459eb-104">Azure Notification Hubs libraries for .NET</span></span>

<span data-ttu-id="459eb-105">Azure Notification Hubs bietet ein einfach zu bedienendes, horizontal skaliertes Pushmodul.</span><span class="sxs-lookup"><span data-stu-id="459eb-105">Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out push engine.</span></span> <span data-ttu-id="459eb-106">Mit einem einzelnen plattformübergreifende API-Aufruf können Sie zielgerichtete und personalisierte Pushbenachrichtigungen aus einem beliebigen Cloud- oder lokalen Back-End an sämtliche mobile Plattformen senden.</span><span class="sxs-lookup"><span data-stu-id="459eb-106">With a single cross-platform API call, you can easily send targeted and personalized push notifications to any mobile platform from any cloud or on-premises backend.</span></span>

## <a name="client-library"></a><span data-ttu-id="459eb-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="459eb-107">Client library</span></span>

<span data-ttu-id="459eb-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="459eb-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

> [!NOTE]
> <span data-ttu-id="459eb-109">Eine [neue Vorschauversion des NuGet-Pakets](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1) unterstützt nun .NET Standard, wodurch die Verwendung von .NET Core für die Back-End-Nutzung von Notifications Hubs ermöglicht wird</span><span class="sxs-lookup"><span data-stu-id="459eb-109">A [new preview version of the NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs/2.0.0-preview1) now supports .NET Standard, which allows using .NET core for backend use of Notifications Hubs</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="459eb-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="459eb-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a><span data-ttu-id="459eb-111">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="459eb-111">Code Example</span></span>

<span data-ttu-id="459eb-112">In diesem Beispiel wird eine Verbindung mit einer Datenbank hergestellt. Anschließend werden Zeilen in einer Tabelle gelesen.</span><span class="sxs-lookup"><span data-stu-id="459eb-112">This example connects to a database and reads rows from a table.</span></span>

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="459eb-113">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="459eb-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a><span data-ttu-id="459eb-114">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="459eb-114">Management library</span></span>

<span data-ttu-id="459eb-115">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="459eb-115">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="459eb-116">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="459eb-116">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="459eb-117">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="459eb-117">Explore the management APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a><span data-ttu-id="459eb-118">Beispiele</span><span class="sxs-lookup"><span data-stu-id="459eb-118">Samples</span></span>

- <span data-ttu-id="459eb-119">[Get Started with Notification Hubs Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal) (Erste Schritte mit Notification Hubs Windows Universal)</span><span class="sxs-lookup"><span data-stu-id="459eb-119">[Getting Started with Windows Universal](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
