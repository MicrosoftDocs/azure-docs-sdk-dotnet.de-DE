---
title: "Azure CDN-Bibliotheken für .NET"
description: "Referenz für Azure CDN-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, CDN
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/31/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: cdn
ms.openlocfilehash: 1582f85c6e25a973fdf0294afb4393e6622e92a0
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-cdn-libraries-for-net"></a><span data-ttu-id="18a02-104">Azure CDN-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="18a02-104">Azure CDN libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="18a02-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="18a02-105">Overview</span></span>

<span data-ttu-id="18a02-106">Das Azure Content Delivery Network (CDN) speichert statische Webinhalte an strategisch platzierten Standorten zwischen, um beim Bereitstellen von Inhalten für Benutzer einen maximalen Durchsatz zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="18a02-106">The Azure Content Delivery Network (CDN) caches static web content at strategically placed locations to provide maximum throughput for delivering content to users.</span></span> <span data-ttu-id="18a02-107">Das CDN bietet Entwicklern eine globale Lösung für die Übermittlung von Inhalten mit hoher Bandbreite durch Zwischenspeichern der Inhalte auf physischen Knoten auf der ganzen Welt.</span><span class="sxs-lookup"><span data-stu-id="18a02-107">The CDN offers developers a global solution for delivering high-bandwidth content by caching the content at physical nodes across the world.</span></span>

<span data-ttu-id="18a02-108">Weitere Informationen zu Azure CDN finden Sie unter [Übersicht über Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).</span><span class="sxs-lookup"><span data-stu-id="18a02-108">To learn more about Azure CDN, see [Overview of the Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).</span></span>


## <a name="management-library"></a><span data-ttu-id="18a02-109">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="18a02-109">Management library</span></span>

<span data-ttu-id="18a02-110">Sie können die Azure CDN-Bibliothek für .NET verwenden, um die Erstellung und Verwaltung von CDN-Profilen und -Endpunkten zu automatisieren.</span><span class="sxs-lookup"><span data-stu-id="18a02-110">You can use the Azure CDN Library for .NET to automate creation and management of CDN profiles and endpoints.</span></span> 

<span data-ttu-id="18a02-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="18a02-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="18a02-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="18a02-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Cdn.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Cdn.Fluent
```

### <a name="example"></a><span data-ttu-id="18a02-113">Beispiel</span><span class="sxs-lookup"><span data-stu-id="18a02-113">Example</span></span>

<span data-ttu-id="18a02-114">In diesem Beispiel erstellen Sie ein neues CDN-Profil mit einem neuen Endpunkt, der auf `www.contoso.com` verweist.</span><span class="sxs-lookup"><span data-stu-id="18a02-114">This example creates a new CDN profile with a new endpoint pointed to `www.contoso.com`.</span></span>

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.Cdn.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

ICdnProfile profileDefinition = azure.CdnProfiles.Define("CdnProfileName")
    .WithRegion(Region.USCentral)
    .WithExistingResourceGroup("ResourceGroupName")
    .WithStandardVerizonSku()
    .WithNewEndpoint("www.contoso.com")
    .Create();

```

> [!div class="nextstepaction"]
> [<span data-ttu-id="18a02-115">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="18a02-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/cdn/management)


## <a name="samples"></a><span data-ttu-id="18a02-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="18a02-116">Samples</span></span>

* [<span data-ttu-id="18a02-117">Erste Schritte mit CDN (CDN-Verwaltung) in .NET</span><span class="sxs-lookup"><span data-stu-id="18a02-117">Getting started with CDN - Manage CDN - in .NET</span></span>](https://github.com/Azure-Samples/cdn-dotnet-manage-cdn)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
