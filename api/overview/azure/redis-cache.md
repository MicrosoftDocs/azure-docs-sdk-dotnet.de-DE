---
title: Azure Redis Cache-Bibliotheken für .NET
description: Referenz für Azure Redis Cache-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Redis Cache
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: redis-cache
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 64bb5a43cec8c82412b3dc7b60fea1e8566ab399
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566341"
---
# <a name="azure-redis-cache-libraries-for-net"></a><span data-ttu-id="b3306-104">Azure Redis Cache-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="b3306-104">Azure Redis Cache libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="b3306-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="b3306-105">Overview</span></span>

<span data-ttu-id="b3306-106">Azure Redis Cache ist ein sicherer Datencache und Messagingbroker, der Anwendungen Datenzugriff mit hohem Durchsatz und geringer Latenz bietet.</span><span class="sxs-lookup"><span data-stu-id="b3306-106">Azure Redis Cache is a secure data cache and messaging broker that provides high throughput and low-latency access to data for applications.</span></span>  <span data-ttu-id="b3306-107">Weitere Informationen finden Sie unter [Verwenden von Azure Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span><span class="sxs-lookup"><span data-stu-id="b3306-107">For more information, see [How to Use Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span></span>

## <a name="client-library"></a><span data-ttu-id="b3306-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="b3306-108">Client library</span></span>

<span data-ttu-id="b3306-109">Azure Redis Cache ist kompatibel mit jeder Redis-Client-API einschließlich `StackExchange.Redis`.</span><span class="sxs-lookup"><span data-stu-id="b3306-109">Azure Redis Cache is compatible with any Redis client API, including `StackExchange.Redis`.</span></span>

<span data-ttu-id="b3306-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/StackExchange.Redis) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="b3306-110">Install the [NuGet package](https://www.nuget.org/packages/StackExchange.Redis) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b3306-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="b3306-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package StackExchange.Redis
```

```bash
dotnet add package StackExchange.Redis
```

### <a name="example"></a><span data-ttu-id="b3306-112">Beispiel</span><span class="sxs-lookup"><span data-stu-id="b3306-112">Example</span></span>

<span data-ttu-id="b3306-113">In diesem Beispiel wird eine Verbindung mit einer Redis Cache-Datenbankinstanz hergestellt, und es werden einige Zeichenfolgen anhand des Namens dem Cache hinzugefügt und anschließend wieder abgerufen.</span><span class="sxs-lookup"><span data-stu-id="b3306-113">This example connects to a Redis Cache database instance, adds some strings to the cache by name, and then retrieves them again.</span></span>

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

## <a name="management-library"></a><span data-ttu-id="b3306-114">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="b3306-114">Management library</span></span>

<span data-ttu-id="b3306-115">Mit der Redis Cache-Verwaltungsbibliothek können Sie Redis Cache-Ressourcen und Zugriffsschlüssel verwalten.</span><span class="sxs-lookup"><span data-stu-id="b3306-115">The Redis Cache management library allows you to manage Redis Cache resources and access keys.</span></span>

<span data-ttu-id="b3306-116">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="b3306-116">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b3306-117">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="b3306-117">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Redis.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Redis.Fluent
```

### <a name="example"></a><span data-ttu-id="b3306-118">Beispiel</span><span class="sxs-lookup"><span data-stu-id="b3306-118">Example</span></span>

<span data-ttu-id="b3306-119">In diesem Beispiel wird ein neuer Redis Cache erstellt.</span><span class="sxs-lookup"><span data-stu-id="b3306-119">This example creates a new Redis Cache.</span></span>

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
> [<span data-ttu-id="b3306-120">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="b3306-120">Explore the management APIs</span></span>](/dotnet/api/overview/azure/rediscache/management)


## <a name="samples"></a><span data-ttu-id="b3306-121">Beispiele</span><span class="sxs-lookup"><span data-stu-id="b3306-121">Samples</span></span>

* <span data-ttu-id="b3306-122">[Getting Started with Redis – Manage Redis –in .NET](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache) (Erste Schritte mit Redis – Verwalten von Redis – in .NET)</span><span class="sxs-lookup"><span data-stu-id="b3306-122">[Getting Started with Redis - Manage Redis - in .NET](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
