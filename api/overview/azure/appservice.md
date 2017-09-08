---
title: "Azure App Service-Bibliotheken für .NET"
description: "Referenz für Azure App Service-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Web-Apps, App Service, mobile Apps, ASP.NET
author: camsoper
ms.author: casoper
manager: douge
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: e81a296ea5f5dadf7086439c88a347c20ec2abee
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-app-service-libraries-for-net"></a><span data-ttu-id="5393b-104">Azure App Service-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="5393b-104">Azure App Service libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="5393b-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="5393b-105">Overview</span></span>

<span data-ttu-id="5393b-106">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) ermöglicht Ihnen das Bereitstellen und Skalieren von Websites, Webanwendungen, Diensten und REST-APIs.</span><span class="sxs-lookup"><span data-stu-id="5393b-106">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) allows you to deploy and scale websites, web applications, services, and REST APIs.</span></span>

## <a name="management-api"></a><span data-ttu-id="5393b-107">Verwaltungs-API</span><span class="sxs-lookup"><span data-stu-id="5393b-107">Management API</span></span>

<span data-ttu-id="5393b-108">Sie können Elemente, die in Azure App Service gehostet werden, mit der Verwaltungs-API bereitstellen, verwalten und skalieren.</span><span class="sxs-lookup"><span data-stu-id="5393b-108">Deploy, manage, and scale elements hosted in Azure App Service with the management API.</span></span>

<span data-ttu-id="5393b-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="5393b-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5393b-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="5393b-110">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="5393b-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="5393b-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a><span data-ttu-id="5393b-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="5393b-112">Code Example</span></span>

<span data-ttu-id="5393b-113">Erstellen Sie eine neue Web-App.</span><span class="sxs-lookup"><span data-stu-id="5393b-113">Create a new web app.</span></span>

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
> [<span data-ttu-id="5393b-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="5393b-114">Explore the Management APIs</span></span>](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a><span data-ttu-id="5393b-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="5393b-115">Samples</span></span>

* [<span data-ttu-id="5393b-116">Verwalten Ihrer Web-Apps mit dem .NET SDK für Azure</span><span class="sxs-lookup"><span data-stu-id="5393b-116">Manage your web apps with the .NET SDK for Azure</span></span>](https://azure.microsoft.com/en-us/resources/samples/app-service-web-dotnet-manage/)
* [<span data-ttu-id="5393b-117">ASP.NET-Beispiel für Azure App Service</span><span class="sxs-lookup"><span data-stu-id="5393b-117">ASP.NET sample for Azure App Service</span></span>](https://azure.microsoft.com/en-us/resources/samples/app-service-web-dotnet-get-started/)

<span data-ttu-id="5393b-118">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=app%20service) von Beispielen für Azure App Service an.</span><span class="sxs-lookup"><span data-stu-id="5393b-118">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=app%20service) of Azure App Service samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package