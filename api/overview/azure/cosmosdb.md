---
title: "Azure Cosmos DB-Bibliotheken für .NET"
description: "Referenz für Azure Cosmos DB-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Cosmos DB
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: babf34e98dae439a2dc3d4c63bd638335428e935
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-cosmosdb-libraries-for-net"></a><span data-ttu-id="72715-104">Azure Cosmos DB-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="72715-104">Azure CosmosDB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="72715-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="72715-105">Overview</span></span>

<span data-ttu-id="72715-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein verteilter und skalierbarer Datenspeicher, der viele verschiedene Datenbanktypen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="72715-106">[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a distributed and scalable data store, supporting multiple different types of databases.</span></span>

## <a name="client-library"></a><span data-ttu-id="72715-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="72715-107">Client library</span></span>

<span data-ttu-id="72715-108">Verwenden Sie die Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="72715-108">Use the CosmosDB .NET client library to access and store data in a CosmosDB data store.</span></span>

<span data-ttu-id="72715-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="72715-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="72715-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="72715-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="72715-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="72715-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="72715-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="72715-112">Code Example</span></span>

<span data-ttu-id="72715-113">In diesem Beispiel wird eine Verbindung mit einer vorhandenen Cosmos DB-DocumentDB-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert.</span><span class="sxs-lookup"><span data-stu-id="72715-113">This example connects to an existing CosmosDB DocumentDB API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
// "Item" is a class defined elsewhere...
Item item = client.ReadDocumentAsync<Item>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="72715-114">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="72715-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="72715-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="72715-115">Samples</span></span>

* [<span data-ttu-id="72715-116">Developing a .NET app using Azure Cosmos DB's MongoDB API</span><span class="sxs-lookup"><span data-stu-id="72715-116">Developing a .NET app using Azure Cosmos DB's MongoDB API</span></span>](https://azure.microsoft.com/en-us/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/) (Entwickeln einer .NET-App mit der MongoDB-API von Azure Cosmos DB)

<span data-ttu-id="72715-117">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.</span><span class="sxs-lookup"><span data-stu-id="72715-117">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
