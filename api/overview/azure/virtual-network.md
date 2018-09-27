---
title: Azure Virtual Network-Bibliotheken für .NET
description: Referenz für Azure Virtual Network-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: virtual-network
ms.openlocfilehash: 54dd79cf0f5bed1eab7b606b8a6e3b30c797ecd0
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190663"
---
# <a name="azure-virtual-network-libraries-for-net"></a>Azure Virtual Network-Bibliotheken für .NET

## <a name="overview"></a>Übersicht
Mit dem Dienst [Azure Virtual Network](/azure/virtual-network/virtual-networks-overview) können Sie Azure-Ressourcen über virtuelle Netzwerke (VNETs) sicher miteinander verbinden. Ein VNet ist eine Darstellung Ihres eigenen Netzwerks in der Cloud. Sie können VNETs auch miteinander verbinden, sodass Ressourcen, für die eine Verbindung mit einem der VNets besteht, darüber miteinander kommunizieren können. 

## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Network.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.Network.Fluent
```

### <a name="code-example"></a>Codebeispiel
Dieses Beispiel zeigt, wie Sie ein virtuelles Netzwerk erstellen können.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/network/management)

## <a name="samples"></a>Beispiele
- [Managing Virtual Networks with subnets](https://github.com/Azure-Samples/network-dotnet-manage-virtual-network) (Verwalten von virtuellen Netzwerken mit Subnetzen)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console 
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package 

