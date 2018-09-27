---
title: Azure Redis Cache-Bibliotheken für .NET
description: Referenz für Azure Redis Cache-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: redis-cache
ms.openlocfilehash: cc043bbc6ea5915f7b6c2265b606210efb72d9d0
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190523"
---
# <a name="azure-redis-cache-libraries-for-net"></a><span data-ttu-id="5845b-103">Azure Redis Cache-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="5845b-103">Azure Redis Cache libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="5845b-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="5845b-104">Overview</span></span>

<span data-ttu-id="5845b-105">Azure Redis Cache ist ein sicherer Datencache und Messagingbroker, der Anwendungen Datenzugriff mit hohem Durchsatz und geringer Latenz bietet.</span><span class="sxs-lookup"><span data-stu-id="5845b-105">Azure Redis Cache is a secure data cache and messaging broker that provides high throughput and low-latency access to data for applications.</span></span>  <span data-ttu-id="5845b-106">Weitere Informationen finden Sie unter [Verwenden von Azure Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span><span class="sxs-lookup"><span data-stu-id="5845b-106">For more information, see [How to Use Redis Cache](https://docs.microsoft.com/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache).</span></span>

## <a name="client-library"></a><span data-ttu-id="5845b-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="5845b-107">Client library</span></span>

<span data-ttu-id="5845b-108">Azure Redis Cache ist kompatibel mit jeder Redis-Client-API einschließlich `StackExchange.Redis`.</span><span class="sxs-lookup"><span data-stu-id="5845b-108">Azure Redis Cache is compatible with any Redis client API, including `StackExchange.Redis`.</span></span>

<span data-ttu-id="5845b-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/StackExchange.Redis) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="5845b-109">Install the [NuGet package](https://www.nuget.org/packages/StackExchange.Redis) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5845b-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="5845b-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package StackExchange.Redis
```

```bash
dotnet add package StackExchange.Redis
```

### <a name="example"></a><span data-ttu-id="5845b-111">Beispiel</span><span class="sxs-lookup"><span data-stu-id="5845b-111">Example</span></span>

<span data-ttu-id="5845b-112">In diesem Beispiel wird eine Verbindung mit einer Redis Cache-Datenbankinstanz hergestellt, und es werden einige Zeichenfolgen anhand des Namens dem Cache hinzugefügt und anschließend wieder abgerufen.</span><span class="sxs-lookup"><span data-stu-id="5845b-112">This example connects to a Redis Cache database instance, adds some strings to the cache by name, and then retrieves them again.</span></span>

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

## <a name="management-library"></a><span data-ttu-id="5845b-113">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="5845b-113">Management library</span></span>

<span data-ttu-id="5845b-114">Mit der Redis Cache-Verwaltungsbibliothek können Sie Redis Cache-Ressourcen und Zugriffsschlüssel verwalten.</span><span class="sxs-lookup"><span data-stu-id="5845b-114">The Redis Cache management library allows you to manage Redis Cache resources and access keys.</span></span>

<span data-ttu-id="5845b-115">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="5845b-115">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Redis.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5845b-116">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="5845b-116">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Redis.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Redis.Fluent
```

### <a name="example"></a><span data-ttu-id="5845b-117">Beispiel</span><span class="sxs-lookup"><span data-stu-id="5845b-117">Example</span></span>

<span data-ttu-id="5845b-118">In diesem Beispiel wird ein neuer Redis Cache erstellt.</span><span class="sxs-lookup"><span data-stu-id="5845b-118">This example creates a new Redis Cache.</span></span>

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
> [<span data-ttu-id="5845b-119">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="5845b-119">Explore the management APIs</span></span>](/dotnet/api/overview/azure/rediscache/management)


## <a name="samples"></a><span data-ttu-id="5845b-120">Beispiele</span><span class="sxs-lookup"><span data-stu-id="5845b-120">Samples</span></span>

* <span data-ttu-id="5845b-121">[Getting Started with Redis – Manage Redis –in .NET](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache) (Erste Schritte mit Redis – Verwalten von Redis – in .NET)</span><span class="sxs-lookup"><span data-stu-id="5845b-121">[Getting Started with Redis - Manage Redis - in .NET](https://github.com/Azure-Samples/redis-cache-dotnet-manage-cache)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
