---
title: "Azure-Computebibliotheken für .NET"
description: "Referenz für Azure-Computebibliotheken für .NET"
keywords: Azure, .NET, SDK, API, VM, virtuelle Computer, compute
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: virtual-machines
ms.custom: devcenter, svc-overview
ms.openlocfilehash: b8caa9a46b858c2ea1f14e83880bd69d83f6a5e9
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-virtual-machine-libraries-for-net"></a><span data-ttu-id="1aa30-104">Azure Virtual Machines-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="1aa30-104">Azure virtual machine libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="1aa30-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="1aa30-105">Overview</span></span>

<span data-ttu-id="1aa30-106">Bedarfsgesteuerte, skalierbare Computeressourcen unter Linux oder Windows</span><span class="sxs-lookup"><span data-stu-id="1aa30-106">On-demand, scalable computing resources running Linux or Windows.</span></span>

<span data-ttu-id="1aa30-107">Informationen zu den ersten Schritten mit virtuellen Azure-Computern finden Sie unter [Erstellen einer Linux-VM mit dem Azure-Portal](https://review.docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal).</span><span class="sxs-lookup"><span data-stu-id="1aa30-107">To get started with Azure virtual machines, see [Create a Linux virtual machine with the Azure portal](https://review.docs.microsoft.com/en-us/azure/virtual-machines/linux/quick-create-portal).</span></span>

## <a name="management-apis"></a><span data-ttu-id="1aa30-108">Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="1aa30-108">Management APIs</span></span>

<span data-ttu-id="1aa30-109">Mit der Verwaltungs-API können Sie virtuelle Windows- und Linux-Computer in Azure über Ihren Code erstellen, konfigurieren und horizontal hochskalieren.</span><span class="sxs-lookup"><span data-stu-id="1aa30-109">Create, configure, and scale out Windows and Linux virtual machines in Azure from your code with the management API.</span></span>

<span data-ttu-id="1aa30-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="1aa30-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="1aa30-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="1aa30-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Compute.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="1aa30-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="1aa30-112">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Compute.Fluent
```

### <a name="code-example"></a><span data-ttu-id="1aa30-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="1aa30-113">Code Example</span></span>

<span data-ttu-id="1aa30-114">Erstellen Sie eine Windows-VM.</span><span class="sxs-lookup"><span data-stu-id="1aa30-114">Create a Windows VM.</span></span>

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.Compute.Fluent;
using Microsoft.Azure.Management.Compute.Fluent.Models;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IVirtualMachine windowsVM = azure.VirtualMachines.Define("MyVirtualMachine")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewPrimaryNetwork("10.0.0.0/28")
    .WithPrimaryPrivateIPAddressDynamic()
    .WithNewPrimaryPublicIPAddress("MyIPAddressLabel")
    .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
    .WithAdminUsername("UserName")
    .WithAdminPassword("Password")
    .WithSize(VirtualMachineSizeTypes.StandardD3V2)
    .Create();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="1aa30-115">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="1aa30-115">Explore the management APIs</span></span>](https://review.docs.microsoft.com/en-us/dotnet/api/overview/azure/virtualmachines/management?view=azure-dotnet)

### <a name="samples"></a><span data-ttu-id="1aa30-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="1aa30-116">Samples</span></span>

* [<span data-ttu-id="1aa30-117">Erstellen und Verwalten von virtuellen Computern</span><span class="sxs-lookup"><span data-stu-id="1aa30-117">Create and manage virtual machines</span></span>](/dotnet/azure/dotnet-sdk-azure-virtual-machine-samples)
* [<span data-ttu-id="1aa30-118">Deploy an SSH Enabled VM with a Template with .NET (Bereitstellen eines SSH-fähigen virtuellen Computers mit einer Vorlage mit .NET)</span><span class="sxs-lookup"><span data-stu-id="1aa30-118">Deploy an SSH-enabled VM with a Template with .NET</span></span>](https://azure.microsoft.com/en-us/resources/samples/resource-manager-dotnet-template-deployment/)

<span data-ttu-id="1aa30-119">Zeigen Sie die [vollständige](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=VM) Liste von VM-Beispielen an.</span><span class="sxs-lookup"><span data-stu-id="1aa30-119">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=VM) of virtual machine samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
