---
title: Azure Redis Cache-Bibliotheken für .NET
description: Referenz für Azure Redis Cache-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Redis Cache
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: redis-cache
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 879f42aa254103239fb0dceeb25cb99a7d5e9814
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065920"
---
# <a name="azure-redis-cache-libraries-for-net"></a>Azure Redis Cache-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Redis Cache ist ein sicherer Datencache und Messagingbroker, der Anwendungen Datenzugriff mit hohem Durchsatz und geringer Latenz bietet.  Weitere Informationen finden Sie unter [Verwenden von Azure Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).

## <a name="client-library"></a>Clientbibliothek

Azure Redis Cache ist kompatibel mit jeder Redis-Client-API einschließlich `StackExchange.Redis`.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/StackExchange.Redis) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package StackExchange.Redis
```

```bash
dotnet add package StackExchange.Redis
```

### <a name="example"></a>Beispiel

In diesem Beispiel wird eine Verbindung mit einer Redis Cache-Datenbankinstanz hergestellt, und es werden einige Zeichenfolgen anhand des Namens dem Cache hinzugefügt und anschließend wieder abgerufen.

```csharp
/* Include this "using" directive.
using StackExchange.Redis;
*/

ConnectionMultiplexer connection = 
    ConnectionMultiplexer.Connect("contoso.redis.cache.windows.net,abortConnect=false,ssl=true,password=...");
    IDatabase cache = connection.GetDatabase();

// Perform cache operations using the cache object...
// Simple put of integral data types into the cache
cache.StringSet("key1", "value");
cache.StringSet("key2", 25);

// Simple get of data types from the cache
string key1 = cache.StringGet("key1");
int key2 = (int)cache.StringGet("key2");
```

## <a name="management-library"></a>Verwaltungsbibliothek

Mit der Redis Cache-Verwaltungsbibliothek können Sie Redis Cache-Ressourcen und Zugriffsschlüssel verwalten.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Redis.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Redis.Fluent
```

### <a name="example"></a>Beispiel

In diesem Beispiel wird ein neuer Redis Cache erstellt.

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.Azure.Management.Redis.Fluent;
*/

IRedisCache redisCache1 = azure.RedisCaches.Define("RedisCacheName")
    .WithRegion(Region.USCentral)
    .WithNewResourceGroup("ResourceGroupName")
    .WithBasicSku()
    .Create();
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/rediscache/management)


## <a name="samples"></a>Beispiele

* [Getting Started with Redis – Manage Redis –in .NET](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache) (Erste Schritte mit Redis – Verwalten von Redis – in .NET)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
