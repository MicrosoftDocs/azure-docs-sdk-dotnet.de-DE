---
title: Azure Resource Manager-Bibliotheken für .NET
description: Referenz für Azure Resource Manager-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: multiple
ms.openlocfilehash: 6d3a27c5f7ba94f5579723cc4f798826c8bdefd6
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190839"
---
# <a name="azure-resource-manager-libraries-for-net"></a><span data-ttu-id="fd2f0-103">Azure Resource Manager-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="fd2f0-103">Azure Resource Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="fd2f0-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="fd2f0-104">Overview</span></span>

<span data-ttu-id="fd2f0-105">Mit dem Azure-Ressourcen-Manager können Sie als Gruppe mit den Ressourcen in Ihrer Lösung arbeiten.</span><span class="sxs-lookup"><span data-stu-id="fd2f0-105">Azure Resource Manager enables you to work with the resources in your solution as a group.</span></span>  <span data-ttu-id="fd2f0-106">Weitere Informationen zu Resource Manager finden Sie unter [Übersicht über den Azure Resource Manager](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).</span><span class="sxs-lookup"><span data-stu-id="fd2f0-106">For more information about Resource Manager, see [Azure Resource Manager overview](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="fd2f0-107">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="fd2f0-107">Management library</span></span>

<span data-ttu-id="fd2f0-108">Die Azure Resource Manager-Bibliothek für .NET ermöglicht Ihnen das Erstellen, Aktualisieren, Löschen und Auflisten von Ressourcen und Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="fd2f0-108">The Azure Resource Manager library for .NET enables you to create, update, delete, and list resources and resource groups.</span></span>

<span data-ttu-id="fd2f0-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="fd2f0-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="fd2f0-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="fd2f0-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="example"></a><span data-ttu-id="fd2f0-111">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fd2f0-111">Example</span></span>

<span data-ttu-id="fd2f0-112">Dieses Beispiel erstellt eine neue Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fd2f0-112">This example creates a new resource group.</span></span>

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.ResourceManager.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IResourceGroup resourceGroup = azure.ResourceGroups
    .Define("ResourceGroupName")
    .WithRegion(Region.USWest)
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="fd2f0-113">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="fd2f0-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/resources/management)


## <a name="samples"></a><span data-ttu-id="fd2f0-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="fd2f0-114">Samples</span></span>

* [<span data-ttu-id="fd2f0-115">Verwalten von Ressourcengruppen</span><span class="sxs-lookup"><span data-stu-id="fd2f0-115">Manage resource groups</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource-group)
* [<span data-ttu-id="fd2f0-116">Verwalten von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="fd2f0-116">Manage resources</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource)
* [<span data-ttu-id="fd2f0-117">Bereitstellen von Ressourcen mit ARM-Vorlagen</span><span class="sxs-lookup"><span data-stu-id="fd2f0-117">Deploy resources with ARM templates</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template)
* [<span data-ttu-id="fd2f0-118">Bereitstellen von Ressourcen mit ARM-Vorlagen (Fortschritt)</span><span class="sxs-lookup"><span data-stu-id="fd2f0-118">Deploy resources with ARM templates (with progress)</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template-with-progress)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
