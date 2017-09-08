---
title: "Azure Redis Cache-Bibliotheken für .NET"
description: "Referenz für Azure Redis Cache-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Redis Cache
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/31/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: redis-cache
ms.openlocfilehash: 2316a179712b143b7e099f4592035c489d270bc3
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-redis-cache-libraries-for-net"></a><span data-ttu-id="89362-104">Azure Redis Cache-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="89362-104">Azure Redis Cache libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="89362-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="89362-105">Overview</span></span>

<span data-ttu-id="89362-106">Azure Redis Cache ist ein sicherer Datencache und Messagingbroker, der Anwendungen Datenzugriff mit hohem Durchsatz und geringer Latenz bietet.</span><span class="sxs-lookup"><span data-stu-id="89362-106">Azure Redis Cache is a secure data cache and messaging broker that provides high throughput and low-latency access to data for applications.</span></span>  <span data-ttu-id="89362-107">Weitere Informationen finden Sie unter [Verwenden von Azure Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span><span class="sxs-lookup"><span data-stu-id="89362-107">For more information, see [How to Use Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span></span>

## <a name="client-library"></a><span data-ttu-id="89362-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="89362-108">Client library</span></span>

<span data-ttu-id="89362-109">Azure Redis Cache ist kompatibel mit jeder Redis-Client-API einschließlich `StackExchange.Redis`.</span><span class="sxs-lookup"><span data-stu-id="89362-109">Azure Redis Cache is compatible with any Redis client API, including `StackExchange.Redis`.</span></span>

<span data-ttu-id="89362-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/StackExchange.Redis) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="89362-110">Install the [NuGet package](https://www.nuget.org/packages/StackExchange.Redis) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="89362-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="89362-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package StackExchange.Redis
```

```bash
dotnet add package StackExchange.Redis
```

### <a name="example"></a><span data-ttu-id="89362-112">Beispiel</span><span class="sxs-lookup"><span data-stu-id="89362-112">Example</span></span>

<span data-ttu-id="89362-113">In diesem Beispiel wird eine Verbindung mit einer Redis Cache-Datenbankinstanz hergestellt, und es werden einige Zeichenfolgen anhand des Namens dem Cache hinzugefügt und anschließend wieder abgerufen.</span><span class="sxs-lookup"><span data-stu-id="89362-113">This example connects to a Redis Cache database instance, adds some strings to the cache by name, and then retrieves them again.</span></span>

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

## <a name="management-library"></a><span data-ttu-id="89362-114">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="89362-114">Management library</span></span>

<span data-ttu-id="89362-115">Mit der Redis Cache-Verwaltungsbibliothek können Sie Redis Cache-Ressourcen und Zugriffsschlüssel verwalten.</span><span class="sxs-lookup"><span data-stu-id="89362-115">The Redis Cache management library allows you to manage Redis Cache resources and access keys.</span></span>

<span data-ttu-id="89362-116">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="89362-116">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="89362-117">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="89362-117">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Redis.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Redis.Fluent
```

### <a name="example"></a><span data-ttu-id="89362-118">Beispiel</span><span class="sxs-lookup"><span data-stu-id="89362-118">Example</span></span>

<span data-ttu-id="89362-119">In diesem Beispiel wird ein neuer Redis Cache erstellt.</span><span class="sxs-lookup"><span data-stu-id="89362-119">This example creates a new Redis Cache.</span></span>

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
> [<span data-ttu-id="89362-120">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="89362-120">Explore the management APIs</span></span>](/dotnet/api/overview/azure/rediscache/management)


## <a name="samples"></a><span data-ttu-id="89362-121">Beispiele</span><span class="sxs-lookup"><span data-stu-id="89362-121">Samples</span></span>

* [<span data-ttu-id="89362-122">Getting Started with Redis – Manage Redis –in .NET</span><span class="sxs-lookup"><span data-stu-id="89362-122">Getting Started with Redis - Manage Redis - in .NET</span></span>](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache) (Erste Schritte mit Redis – Verwalten von Redis – in .NET)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
