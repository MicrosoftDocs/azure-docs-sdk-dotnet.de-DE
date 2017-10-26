---
title: "Azure App Service-Bibliotheken für .NET"
description: "Referenz für Azure App Service-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Web-Apps, App Service, mobile Apps, ASP.NET
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: app-service
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 9f54fb6aca934f07c6ae23a4ae40dc29fa48ec8b
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-app-service-libraries-for-net"></a><span data-ttu-id="63658-104">Azure App Service-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="63658-104">Azure App Service libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="63658-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="63658-105">Overview</span></span>

<span data-ttu-id="63658-106">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) ermöglicht Ihnen das Bereitstellen und Skalieren von Websites, Webanwendungen, Diensten und REST-APIs.</span><span class="sxs-lookup"><span data-stu-id="63658-106">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) allows you to deploy and scale websites, web applications, services, and REST APIs.</span></span>

## <a name="management-api"></a><span data-ttu-id="63658-107">Verwaltungs-API</span><span class="sxs-lookup"><span data-stu-id="63658-107">Management API</span></span>

<span data-ttu-id="63658-108">Sie können Elemente, die in Azure App Service gehostet werden, mit der Verwaltungs-API bereitstellen, verwalten und skalieren.</span><span class="sxs-lookup"><span data-stu-id="63658-108">Deploy, manage, and scale elements hosted in Azure App Service with the management API.</span></span>

<span data-ttu-id="63658-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="63658-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="63658-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="63658-110">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="63658-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="63658-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a><span data-ttu-id="63658-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="63658-112">Code Example</span></span>

<span data-ttu-id="63658-113">Erstellen Sie eine neue Web-App.</span><span class="sxs-lookup"><span data-stu-id="63658-113">Create a new web app.</span></span>

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.Azure.Management.AppService.Fluent;
*/

IWebApp app1 = azure.WebApps
    .Define("MyUniqueWebAddress")
    .WithRegion(Region.USWest)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewWindowsPlan(PricingTier.StandardS1)
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="63658-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="63658-114">Explore the Management APIs</span></span>](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a><span data-ttu-id="63658-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="63658-115">Samples</span></span>

* [<span data-ttu-id="63658-116">Verwalten Ihrer Web-Apps mit dem .NET SDK für Azure</span><span class="sxs-lookup"><span data-stu-id="63658-116">Manage your web apps with the .NET SDK for Azure</span></span>](https://azure.microsoft.com/en-us/resources/samples/app-service-web-dotnet-manage/)
* [<span data-ttu-id="63658-117">ASP.NET-Beispiel für Azure App Service</span><span class="sxs-lookup"><span data-stu-id="63658-117">ASP.NET sample for Azure App Service</span></span>](https://azure.microsoft.com/en-us/resources/samples/app-service-web-dotnet-get-started/)

<span data-ttu-id="63658-118">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=app%20service) von Beispielen für Azure App Service an.</span><span class="sxs-lookup"><span data-stu-id="63658-118">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=app%20service) of Azure App Service samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package