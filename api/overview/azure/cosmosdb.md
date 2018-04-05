---
title: Azure Cosmos DB-Bibliotheken für .NET
description: Referenz für Azure Cosmos DB-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Cosmos DB
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 11/17/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: cosmos-db
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 4791e00c18d00fbed13bdf2c626a24fed2ff2863
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2018
---
# <a name="azure-cosmosdb-libraries-for-net"></a><span data-ttu-id="2b368-104">Azure Cosmos DB-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="2b368-104">Azure CosmosDB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="2b368-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="2b368-105">Overview</span></span>

<span data-ttu-id="2b368-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein verteilter und skalierbarer Datenspeicher, der viele verschiedene Datenbanktypen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="2b368-106">[Azure CosmosDB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a distributed and scalable data store, supporting multiple different types of databases.</span></span>

<span data-ttu-id="2b368-107">[Erste Schritte mit CosmosDB](https://docs.microsoft.com/azure/cosmos-db/create-documentdb-dotnet).</span><span class="sxs-lookup"><span data-stu-id="2b368-107">[Get started with CosmosDB](https://docs.microsoft.com/azure/cosmos-db/create-documentdb-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="2b368-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="2b368-108">Client library</span></span>

<span data-ttu-id="2b368-109">Verwenden Sie die Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="2b368-109">Use the CosmosDB .NET client library to access and store data in an existing CosmosDB data store.</span></span>  <span data-ttu-id="2b368-110">Die Erstellung eines neuen Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.</span><span class="sxs-lookup"><span data-stu-id="2b368-110">To automate creation of a new CosmosDB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="2b368-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="2b368-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="2b368-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="2b368-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="2b368-113">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="2b368-113">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="2b368-114">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="2b368-114">Code Example</span></span>

<span data-ttu-id="2b368-115">In diesem Beispiel wird eine Verbindung mit einer vorhandenen Cosmos DB-DocumentDB-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert.</span><span class="sxs-lookup"><span data-stu-id="2b368-115">This example connects to an existing CosmosDB DocumentDB API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="2b368-116">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="2b368-116">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="2b368-117">Beispiele</span><span class="sxs-lookup"><span data-stu-id="2b368-117">Samples</span></span>

* <span data-ttu-id="2b368-118">[Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/) (Entwickeln einer .NET-App mit der MongoDB-API von Azure Cosmos DB)</span><span class="sxs-lookup"><span data-stu-id="2b368-118">[Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)</span></span>

<span data-ttu-id="2b368-119">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.</span><span class="sxs-lookup"><span data-stu-id="2b368-119">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
