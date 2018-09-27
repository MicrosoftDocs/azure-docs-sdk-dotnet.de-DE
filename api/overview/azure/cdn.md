---
title: Azure CDN-Bibliotheken für .NET
description: Referenz für Azure CDN-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: cdn
ms.openlocfilehash: 6475edbe4fa0d01739de5cff76038aa6e7fd2cf9
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190123"
---
# <a name="azure-cdn-libraries-for-net"></a><span data-ttu-id="be3fb-103">Azure CDN-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="be3fb-103">Azure CDN libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="be3fb-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="be3fb-104">Overview</span></span>

<span data-ttu-id="be3fb-105">Das Azure Content Delivery Network (CDN) speichert statische Webinhalte an strategisch platzierten Standorten zwischen, um beim Bereitstellen von Inhalten für Benutzer einen maximalen Durchsatz zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="be3fb-105">The Azure Content Delivery Network (CDN) caches static web content at strategically placed locations to provide maximum throughput for delivering content to users.</span></span> <span data-ttu-id="be3fb-106">Das CDN bietet Entwicklern eine globale Lösung für die Übermittlung von Inhalten mit hoher Bandbreite durch Zwischenspeichern der Inhalte auf physischen Knoten auf der ganzen Welt.</span><span class="sxs-lookup"><span data-stu-id="be3fb-106">The CDN offers developers a global solution for delivering high-bandwidth content by caching the content at physical nodes across the world.</span></span>

<span data-ttu-id="be3fb-107">Weitere Informationen zu Azure CDN finden Sie unter [Übersicht über Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).</span><span class="sxs-lookup"><span data-stu-id="be3fb-107">To learn more about Azure CDN, see [Overview of the Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).</span></span>


## <a name="management-library"></a><span data-ttu-id="be3fb-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="be3fb-108">Management library</span></span>

<span data-ttu-id="be3fb-109">Sie können die Azure CDN-Bibliothek für .NET verwenden, um die Erstellung und Verwaltung von CDN-Profilen und -Endpunkten zu automatisieren.</span><span class="sxs-lookup"><span data-stu-id="be3fb-109">You can use the Azure CDN Library for .NET to automate creation and management of CDN profiles and endpoints.</span></span> 

<span data-ttu-id="be3fb-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="be3fb-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="be3fb-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="be3fb-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Cdn.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Cdn.Fluent
```

### <a name="example"></a><span data-ttu-id="be3fb-112">Beispiel</span><span class="sxs-lookup"><span data-stu-id="be3fb-112">Example</span></span>

<span data-ttu-id="be3fb-113">In diesem Beispiel erstellen Sie ein neues CDN-Profil mit einem neuen Endpunkt, der auf `www.contoso.com` verweist.</span><span class="sxs-lookup"><span data-stu-id="be3fb-113">This example creates a new CDN profile with a new endpoint pointed to `www.contoso.com`.</span></span>

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
> [<span data-ttu-id="be3fb-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="be3fb-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/cdn/management)


## <a name="samples"></a><span data-ttu-id="be3fb-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="be3fb-115">Samples</span></span>

* [<span data-ttu-id="be3fb-116">Erste Schritte mit CDN (CDN-Verwaltung) in .NET</span><span class="sxs-lookup"><span data-stu-id="be3fb-116">Getting started with CDN - Manage CDN - in .NET</span></span>](https://github.com/Azure-Samples/cdn-dotnet-manage-cdn)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
