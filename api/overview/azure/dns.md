---
title: "Azure DNS-Bibliotheken für .NET"
description: "Referenz für Azure DNS-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, DNS
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/31/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 57c578f12ea426dc5784658338473f0044d21e5c
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-dns-libraries-for-net"></a><span data-ttu-id="2930e-104">Azure DNS-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="2930e-104">Azure DNS libraries for .NET</span></span>

<span data-ttu-id="2930e-105">Verwenden Sie die Microsoft Azure DNS-Bibliotheken für .NET zum Erstellen und Ändern von DNS-Zonen und -Einträgen, die in Azure gehostet werden.</span><span class="sxs-lookup"><span data-stu-id="2930e-105">Use the Microsoft Azure DNS libraries for .NET to create and modify DNS zones and records hosted within Azure.</span></span> <span data-ttu-id="2930e-106">Zonen und Einträge werden als Azure-Ressourcen verwaltet.</span><span class="sxs-lookup"><span data-stu-id="2930e-106">Zones and records are managed as Azure Resources.</span></span> <span data-ttu-id="2930e-107">Um mehr zu erfahren, lesen Sie [Azure DNS – Übersicht](/azure/dns/dns-overview).</span><span class="sxs-lookup"><span data-stu-id="2930e-107">Learn more by reading the [Azure DNS overview](/azure/dns/dns-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="2930e-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="2930e-108">Management library</span></span>

<span data-ttu-id="2930e-109">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Ändern von DNS-Zonen und -Einträgen, die in Azure gehostet werden.</span><span class="sxs-lookup"><span data-stu-id="2930e-109">Use the management library to create and modify DNS zones and records that are hosted in Azure.</span></span>

<span data-ttu-id="2930e-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="2930e-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="2930e-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="2930e-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Dns
```

```bash
dotnet add package Microsoft.Azure.Management.Dns
```

### <a name="example"></a><span data-ttu-id="2930e-112">Beispiel</span><span class="sxs-lookup"><span data-stu-id="2930e-112">Example</span></span>

<span data-ttu-id="2930e-113">Im folgenden Beispiel wird eine neue DNS-Zone erstellt.</span><span class="sxs-lookup"><span data-stu-id="2930e-113">The following example creates a new DNS zone.</span></span>

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
> [<span data-ttu-id="2930e-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="2930e-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/dns/management)

## <a name="samples"></a><span data-ttu-id="2930e-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="2930e-115">Samples</span></span>

* [<span data-ttu-id="2930e-116">Azure DNS .NET SDK: Beispielprojekt</span><span class="sxs-lookup"><span data-stu-id="2930e-116">Azure DNS .NET SDK Sample Project</span></span>](https://www.microsoft.com/download/details.aspx?id=47268)

<span data-ttu-id="2930e-117">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="2930e-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
