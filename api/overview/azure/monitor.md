---
title: Azure Monitor-Bibliotheken für .NET
description: Referenz für Azure Monitor-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Monitor
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/27/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 8055b8861f6991e021ff1ea3bfa87cf96f554fa2
ms.sourcegitcommit: 64c9e16e42894e8db8ed088487e55c5e0edd6861
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/31/2017
ms.locfileid: "23639638"
---
# <a name="azure-monitor-libraries-for-net"></a><span data-ttu-id="0aaec-104">Azure Monitor-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="0aaec-104">Azure Monitor libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="0aaec-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="0aaec-105">Overview</span></span>

<span data-ttu-id="0aaec-106">Azure Monitor dient zum Nachverfolgen der Leistung, Aufrechterhalten der Sicherheit und Identifizieren von Trends.</span><span class="sxs-lookup"><span data-stu-id="0aaec-106">Azure Monitor helps you track performance, maintain security, and identify trends.</span></span>

<span data-ttu-id="0aaec-107">Weitere Informationen zu Azure Monitor finden Sie [hier](/azure/monitoring-and-diagnostics/).</span><span class="sxs-lookup"><span data-stu-id="0aaec-107">Learn more about [Azure Monitor](/azure/monitoring-and-diagnostics/).</span></span>   

## <a name="management-library"></a><span data-ttu-id="0aaec-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="0aaec-108">Management library</span></span>

<span data-ttu-id="0aaec-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="0aaec-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="0aaec-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="0aaec-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Monitor.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Monitor.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="0aaec-111">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="0aaec-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a><span data-ttu-id="0aaec-112">Beispiele</span><span class="sxs-lookup"><span data-stu-id="0aaec-112">Samples</span></span>

<span data-ttu-id="0aaec-113">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="0aaec-113">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package