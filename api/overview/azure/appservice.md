---
title: Azure App Service-Bibliotheken für .NET
description: Referenz für Azure App Service-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: app-service
ms.openlocfilehash: 82f8eccfafd2f7b1cf1df1ce0f40212509ccddd3
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47189993"
---
# <a name="azure-app-service-libraries-for-net"></a><span data-ttu-id="6b961-103">Azure App Service-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="6b961-103">Azure App Service libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="6b961-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="6b961-104">Overview</span></span>

<span data-ttu-id="6b961-105">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) ermöglicht Ihnen das Bereitstellen und Skalieren von Websites, Webanwendungen, Diensten und REST-APIs.</span><span class="sxs-lookup"><span data-stu-id="6b961-105">[Azure App Service](/azure/app-service/app-service-value-prop-what-is) allows you to deploy and scale websites, web applications, services, and REST APIs.</span></span>

## <a name="management-api"></a><span data-ttu-id="6b961-106">Verwaltungs-API</span><span class="sxs-lookup"><span data-stu-id="6b961-106">Management API</span></span>

<span data-ttu-id="6b961-107">Sie können Elemente, die in Azure App Service gehostet werden, mit der Verwaltungs-API bereitstellen, verwalten und skalieren.</span><span class="sxs-lookup"><span data-stu-id="6b961-107">Deploy, manage, and scale elements hosted in Azure App Service with the management API.</span></span>

<span data-ttu-id="6b961-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="6b961-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6b961-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="6b961-109">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="6b961-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="6b961-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a><span data-ttu-id="6b961-111">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="6b961-111">Code Example</span></span>

<span data-ttu-id="6b961-112">Erstellen Sie eine neue Web-App.</span><span class="sxs-lookup"><span data-stu-id="6b961-112">Create a new web app.</span></span>

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
> [<span data-ttu-id="6b961-113">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="6b961-113">Explore the Management APIs</span></span>](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a><span data-ttu-id="6b961-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="6b961-114">Samples</span></span>

* [<span data-ttu-id="6b961-115">Verwalten Ihrer Web-Apps mit dem .NET SDK für Azure</span><span class="sxs-lookup"><span data-stu-id="6b961-115">Manage your web apps with the .NET SDK for Azure</span></span>](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-manage/)
* [<span data-ttu-id="6b961-116">ASP.NET-Beispiel für Azure App Service</span><span class="sxs-lookup"><span data-stu-id="6b961-116">ASP.NET sample for Azure App Service</span></span>](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-get-started/)

<span data-ttu-id="6b961-117">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service) von Beispielen für Azure App Service an.</span><span class="sxs-lookup"><span data-stu-id="6b961-117">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service) of Azure App Service samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package