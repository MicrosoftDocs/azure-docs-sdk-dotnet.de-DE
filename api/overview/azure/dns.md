---
title: Azure DNS-Bibliotheken für .NET
description: Referenz für Azure DNS-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, DNS
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: dns
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 0360c4d5a0e276b4adf05d43689896fab6622f51
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065330"
---
# <a name="azure-dns-libraries-for-net"></a>Azure DNS-Bibliotheken für .NET

Verwenden Sie die Microsoft Azure DNS-Bibliotheken für .NET zum Erstellen und Ändern von DNS-Zonen und -Einträgen, die in Azure gehostet werden. Zonen und Einträge werden als Azure-Ressourcen verwaltet. Um mehr zu erfahren, lesen Sie [Azure DNS – Übersicht](/azure/dns/dns-overview).

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Ändern von DNS-Zonen und -Einträgen, die in Azure gehostet werden.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Dns) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Dns
```

```bash
dotnet add package Microsoft.Azure.Management.Dns
```

### <a name="example"></a>Beispiel

Im folgenden Beispiel wird eine neue DNS-Zone erstellt.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/dns/management)

## <a name="samples"></a>Beispiele

* [Azure DNS .NET SDK: Beispielprojekt](https://www.microsoft.com/download/details.aspx?id=47268)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
