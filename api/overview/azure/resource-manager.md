---
title: Azure Resource Manager-Bibliotheken für .NET
description: Referenz für Azure Resource Manager-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Resource Manager
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f9fe96fcdc94d3d27445f462c5220def9f2966da
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566371"
---
# <a name="azure-resource-manager-libraries-for-net"></a><span data-ttu-id="2b457-104">Azure Resource Manager-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="2b457-104">Azure Resource Manager libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="2b457-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="2b457-105">Overview</span></span>

<span data-ttu-id="2b457-106">Mit dem Azure-Ressourcen-Manager können Sie als Gruppe mit den Ressourcen in Ihrer Lösung arbeiten.</span><span class="sxs-lookup"><span data-stu-id="2b457-106">Azure Resource Manager enables you to work with the resources in your solution as a group.</span></span>  <span data-ttu-id="2b457-107">Weitere Informationen zu Resource Manager finden Sie unter [Übersicht über den Azure Resource Manager](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).</span><span class="sxs-lookup"><span data-stu-id="2b457-107">For more information about Resource Manager, see [Azure Resource Manager overview](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="2b457-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="2b457-108">Management library</span></span>

<span data-ttu-id="2b457-109">Die Azure Resource Manager-Bibliothek für .NET ermöglicht Ihnen das Erstellen, Aktualisieren, Löschen und Auflisten von Ressourcen und Ressourcengruppen.</span><span class="sxs-lookup"><span data-stu-id="2b457-109">The Azure Resource Manager library for .NET enables you to create, update, delete, and list resources and resource groups.</span></span>

<span data-ttu-id="2b457-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="2b457-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="2b457-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="2b457-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="example"></a><span data-ttu-id="2b457-112">Beispiel</span><span class="sxs-lookup"><span data-stu-id="2b457-112">Example</span></span>

<span data-ttu-id="2b457-113">Dieses Beispiel erstellt eine neue Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2b457-113">This example creates a new resource group.</span></span>

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
> [<span data-ttu-id="2b457-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="2b457-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/resources/management)


## <a name="samples"></a><span data-ttu-id="2b457-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="2b457-115">Samples</span></span>

* [<span data-ttu-id="2b457-116">Verwalten von Ressourcengruppen</span><span class="sxs-lookup"><span data-stu-id="2b457-116">Manage resource groups</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource-group)
* [<span data-ttu-id="2b457-117">Verwalten von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="2b457-117">Manage resources</span></span>](https://github.com/Azure-Samples/resources-dotnet-manage-resource)
* [<span data-ttu-id="2b457-118">Bereitstellen von Ressourcen mit ARM-Vorlagen</span><span class="sxs-lookup"><span data-stu-id="2b457-118">Deploy resources with ARM templates</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template)
* [<span data-ttu-id="2b457-119">Bereitstellen von Ressourcen mit ARM-Vorlagen (Fortschritt)</span><span class="sxs-lookup"><span data-stu-id="2b457-119">Deploy resources with ARM templates (with progress)</span></span>](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template-with-progress)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
