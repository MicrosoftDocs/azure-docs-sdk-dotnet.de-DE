---
title: Azure DNS-Bibliotheken für .NET
description: Referenz für Azure DNS-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: dns
ms.openlocfilehash: b9ab6359aaa1e4e9b6e99e7a7b007928d18f3453
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190193"
---
# <a name="azure-dns-libraries-for-net"></a><span data-ttu-id="879a4-103">Azure DNS-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="879a4-103">Azure DNS libraries for .NET</span></span>

<span data-ttu-id="879a4-104">Verwenden Sie die Microsoft Azure DNS-Bibliotheken für .NET zum Erstellen und Ändern von DNS-Zonen und -Einträgen, die in Azure gehostet werden.</span><span class="sxs-lookup"><span data-stu-id="879a4-104">Use the Microsoft Azure DNS libraries for .NET to create and modify DNS zones and records hosted within Azure.</span></span> <span data-ttu-id="879a4-105">Zonen und Einträge werden als Azure-Ressourcen verwaltet.</span><span class="sxs-lookup"><span data-stu-id="879a4-105">Zones and records are managed as Azure Resources.</span></span> <span data-ttu-id="879a4-106">Um mehr zu erfahren, lesen Sie [Azure DNS – Übersicht](/azure/dns/dns-overview).</span><span class="sxs-lookup"><span data-stu-id="879a4-106">Learn more by reading the [Azure DNS overview](/azure/dns/dns-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="879a4-107">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="879a4-107">Management library</span></span>

<span data-ttu-id="879a4-108">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Ändern von DNS-Zonen und -Einträgen, die in Azure gehostet werden.</span><span class="sxs-lookup"><span data-stu-id="879a4-108">Use the management library to create and modify DNS zones and records that are hosted in Azure.</span></span>

<span data-ttu-id="879a4-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="879a4-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="879a4-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="879a4-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Dns
```

```bash
dotnet add package Microsoft.Azure.Management.Dns
```

### <a name="example"></a><span data-ttu-id="879a4-111">Beispiel</span><span class="sxs-lookup"><span data-stu-id="879a4-111">Example</span></span>

<span data-ttu-id="879a4-112">Im folgenden Beispiel wird eine neue DNS-Zone erstellt.</span><span class="sxs-lookup"><span data-stu-id="879a4-112">The following example creates a new DNS zone.</span></span>

```csharp
/*
using Microsoft.Rest.Azure.Authentication;
using Microsoft.Azure.Management.Dns;
using Microsoft.Azure.Management.Dns.Models;
*/
Microsoft.Rest.ServiceClientCredentials serviceCreds = await ApplicationTokenProvider.LoginSilentAsync(tenantId, clientId, secret);
DnsManagementClient dnsClient = new DnsManagementClient(serviceCreds);            
Zone dnsZoneParams = new Zone("global");
dnsZoneParams.Tags = new Dictionary<string, string>();
dnsZoneParams.Tags.Add("dept", "finance");
Zone dnsZone =
    await dnsClient.Zones.CreateOrUpdateAsync(resourceGroupName, zoneName, dnsZoneParams, null, "*");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="879a4-113">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="879a4-113">Explore the management APIs</span></span>](/dotnet/api/overview/azure/dns/management)

## <a name="samples"></a><span data-ttu-id="879a4-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="879a4-114">Samples</span></span>

* [<span data-ttu-id="879a4-115">Azure DNS .NET SDK: Beispielprojekt</span><span class="sxs-lookup"><span data-stu-id="879a4-115">Azure DNS .NET SDK Sample Project</span></span>](https://www.microsoft.com/download/details.aspx?id=47268)

<span data-ttu-id="879a4-116">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="879a4-116">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
