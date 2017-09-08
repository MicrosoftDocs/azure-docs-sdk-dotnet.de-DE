---
title: "Azure Notification Hubs-Bibliotheken für .NET"
description: "Referenz für Azure Notification Hubs-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Notification Hubs
author: camsoper
ms.author: casoper
manager: douge
ms.date: 08/07/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 630cdd465fdf6c77ad5d46d9f231c3f331467587
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-notification-hubs-libraries-for-net"></a><span data-ttu-id="ce216-104">Azure Notification Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="ce216-104">Azure Notification Hubs libraries for .NET</span></span>

<span data-ttu-id="ce216-105">Azure Notification Hubs bietet ein einfach zu bedienendes, horizontal skaliertes Pushmodul.</span><span class="sxs-lookup"><span data-stu-id="ce216-105">Azure Notification Hubs provide an easy-to-use, multi-platform, scaled-out push engine.</span></span> <span data-ttu-id="ce216-106">Mit einem einzelnen plattformübergreifende API-Aufruf können Sie zielgerichtete und personalisierte Pushbenachrichtigungen aus einem beliebigen Cloud- oder lokalen Back-End an sämtliche mobile Plattformen senden.</span><span class="sxs-lookup"><span data-stu-id="ce216-106">With a single cross-platform API call, you can easily send targeted and personalized push notifications to any mobile platform from any cloud or on-premises backend.</span></span>

## <a name="client-library"></a><span data-ttu-id="ce216-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="ce216-107">Client library</span></span>

<span data-ttu-id="ce216-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="ce216-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="ce216-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="ce216-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.NotificationHubs
```

### <a name="code-example"></a><span data-ttu-id="ce216-110">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="ce216-110">Code Example</span></span>

<span data-ttu-id="ce216-111">In diesem Beispiel wird eine Verbindung mit einer Datenbank hergestellt. Anschließend werden Zeilen in einer Tabelle gelesen.</span><span class="sxs-lookup"><span data-stu-id="ce216-111">This example connects to a database and reads rows from a table.</span></span>

```csharp
NotificationHubClient hub = NotificationHubClient
                                .CreateClientFromConnectionString("<connection string with full access>", "<hub name>");
string toast = @"<toast><visual><binding template=""ToastText01""><text id=""1"">Hello from a .NET App!</text></binding></visual></toast>";
await hub.SendWindowsNativeNotificationAsync(toast);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="ce216-112">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="ce216-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/client)


## <a name="management-library"></a><span data-ttu-id="ce216-113">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="ce216-113">Management library</span></span>

<span data-ttu-id="ce216-114">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="ce216-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.NotificationHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="ce216-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="ce216-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.NotificationHubs
```

```bash
dotnet add package Microsoft.Azure.Management.NotificationHubs
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="ce216-116">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="ce216-116">Explore the management APIs</span></span>](/dotnet/api/overview/azure/notificationhubs/management)

## <a name="samples"></a><span data-ttu-id="ce216-117">Beispiele</span><span class="sxs-lookup"><span data-stu-id="ce216-117">Samples</span></span>

- [<span data-ttu-id="ce216-118">Get Started with Notification Hubs Windows Universal</span><span class="sxs-lookup"><span data-stu-id="ce216-118">Getting Started with Windows Universal</span></span>](https://github.com/Azure/azure-notificationhubs-samples/tree/master/dotnet/GetStartedWindowsUniversal) (Erste Schritte mit Notification Hubs Windows Universal)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
