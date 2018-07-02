---
title: Azure Traffic Manager-Bibliotheken für .NET
description: Referenz für Azure Traffic Manager-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Traffic Manager
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: traffic-manager
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 05856cbe48a5cf5f0c9ebf43609a029928f490f9
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065870"
---
# <a name="azure-traffic-manager-libraries-for-net"></a><span data-ttu-id="44bd8-104">Azure Traffic Manager-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="44bd8-104">Azure Traffic Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="44bd8-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="44bd8-105">Overview</span></span>

<span data-ttu-id="44bd8-106">Microsoft Azure Traffic Manager ermöglicht die Verteilung von Benutzerdatenverkehr für Dienstendpunkte in unterschiedlichen Rechenzentren.</span><span class="sxs-lookup"><span data-stu-id="44bd8-106">Microsoft Azure Traffic Manager allows you to control the distribution of user traffic for service endpoints in different datacenters.</span></span> <span data-ttu-id="44bd8-107">Zu den von Traffic Manager unterstützten Dienstendpunkten zählen virtuelle Azure-Computer, Web-Apps und Clouddienste.</span><span class="sxs-lookup"><span data-stu-id="44bd8-107">Service endpoints supported by Traffic Manager include Azure VMs, Web Apps, and cloud services.</span></span> <span data-ttu-id="44bd8-108">Darüber hinaus kann Traffic Manager auch mit externen, Azure-fremden Endpunkten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="44bd8-108">You can also use Traffic Manager with external, non-Azure endpoints.</span></span>

<span data-ttu-id="44bd8-109">Weitere Informationen zu [Azure Traffic Manager](/azure/traffic-manager/traffic-manager-overview).</span><span class="sxs-lookup"><span data-stu-id="44bd8-109">Learn more about [Azure Traffic Manager](/azure/traffic-manager/traffic-manager-overview).</span></span>  

## <a name="management-library"></a><span data-ttu-id="44bd8-110">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="44bd8-110">Management library</span></span>

<span data-ttu-id="44bd8-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="44bd8-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="44bd8-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="44bd8-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.TrafficManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.TrafficManager.Fluent
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="44bd8-113">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="44bd8-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/trafficmanager/management)

## <a name="samples"></a><span data-ttu-id="44bd8-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="44bd8-114">Samples</span></span>

<span data-ttu-id="44bd8-115">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="44bd8-115">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package