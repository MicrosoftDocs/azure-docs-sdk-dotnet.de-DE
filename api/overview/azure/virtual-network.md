---
title: "Azure Virtual Network-Bibliotheken für .NET"
description: "Referenz für Azure Virtual Network-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Virtual Network
author: camsoper
ms.author: casoper
manager: douge
ms.date: 08/01/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: ea605dbd632ef4deb9c97c8de3474246dd4be30d
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-virtual-network-libraries-for-net"></a><span data-ttu-id="4dbf9-104">Azure Virtual Network-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="4dbf9-104">Azure Virtual Network libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4dbf9-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="4dbf9-105">Overview</span></span>
<span data-ttu-id="4dbf9-106">Mit dem Dienst [Azure Virtual Network](/azure/virtual-network/virtual-networks-overview) können Sie Azure-Ressourcen über virtuelle Netzwerke (VNETs) sicher miteinander verbinden.</span><span class="sxs-lookup"><span data-stu-id="4dbf9-106">The [Azure Virtual Network](/azure/virtual-network/virtual-networks-overview) service enables you to securely connect Azure resources to each other with virtual networks (VNets).</span></span> <span data-ttu-id="4dbf9-107">Ein VNet ist eine Darstellung Ihres eigenen Netzwerks in der Cloud.</span><span class="sxs-lookup"><span data-stu-id="4dbf9-107">A VNet is a representation of your own network in the cloud.</span></span> <span data-ttu-id="4dbf9-108">Sie können VNETs auch miteinander verbinden, sodass Ressourcen, für die eine Verbindung mit einem der VNets besteht, darüber miteinander kommunizieren können.</span><span class="sxs-lookup"><span data-stu-id="4dbf9-108">You can also connect VNets to each other, enabling resources connected to either VNet to communicate with each other.</span></span> 

## <a name="management-library"></a><span data-ttu-id="4dbf9-109">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="4dbf9-109">Management library</span></span>

<span data-ttu-id="4dbf9-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="4dbf9-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4dbf9-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="4dbf9-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Network.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="4dbf9-112">.NET Core-CLI</span><span class="sxs-lookup"><span data-stu-id="4dbf9-112">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Network.Fluent
```

### <a name="code-example"></a><span data-ttu-id="4dbf9-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="4dbf9-113">Code Example</span></span>
<span data-ttu-id="4dbf9-114">Dieses Beispiel zeigt, wie Sie ein virtuelles Netzwerk erstellen können.</span><span class="sxs-lookup"><span data-stu-id="4dbf9-114">This example shows how you can create a virtual network.</span></span>

```csharp
/* 
  Include these "using" directives...
  
  using Microsoft.Azure.Management.Network.Fluent;
  using Microsoft.Azure.Management.Network.Fluent.Models;
*/
using (NetworkManagementClient client = new NetworkManagementClient(credentials))
{
    // Define VNet
    VirtualNetworkInner vnet = new VirtualNetworkInner()
    {
        Location = "West US",
        AddressSpace = new AddressSpace()
        {
            AddressPrefixes = new List<string>() { "0.0.0.0/16" }
        },

        DhcpOptions = new DhcpOptions()
        {
            DnsServers = new List<string>() { "1.1.1.1", "1.1.2.4" }
        },

        Subnets = new List<Subnet>()
        {
            new Subnet()
            {
                Name = subnet1Name,
                AddressPrefix = "1.0.1.0/24",
            },
            new Subnet()
            {
                Name = subnet2Name,
               AddressPrefix = "1.0.2.0/24",
            }
        }
    };
    
    await client.VirtualNetworks.CreateOrUpdateAsync(resourceGroupName, vNetName, vnet);
}

```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4dbf9-115">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="4dbf9-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/network/management)

## <a name="samples"></a><span data-ttu-id="4dbf9-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="4dbf9-116">Samples</span></span>
- <span data-ttu-id="4dbf9-117">[Managing Virtual Networks with subnets](https://github.com/Azure-Samples/network-dotnet-manage-virtual-network) (Verwalten von virtuellen Netzwerken mit Subnetzen)</span><span class="sxs-lookup"><span data-stu-id="4dbf9-117">[Managing Virtual Networks with subnets](https://github.com/Azure-Samples/network-dotnet-manage-virtual-network)</span></span>

<span data-ttu-id="4dbf9-118">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="4dbf9-118">Explore more [.NET sample code](https://azure.microsoft.com/resources/samples/?platform=dotnet) that you can use in your apps.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console 
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package 

