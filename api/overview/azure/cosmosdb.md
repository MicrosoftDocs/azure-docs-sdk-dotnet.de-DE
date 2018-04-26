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
ms.openlocfilehash: fa9bc7497ac189f18ee0ba14d72d4cdb23a05f0b
ms.sourcegitcommit: e1a0e91988bb849c75e9583a80e3e6d712083785
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/14/2018
---
# <a name="azure-cosmos-db-libraries-for-net"></a><span data-ttu-id="755db-104">Azure Cosmos DB-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="755db-104">Azure Cosmos DB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="755db-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="755db-105">Overview</span></span>

<span data-ttu-id="755db-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein verteilter und skalierbarer Datenspeicher, der viele verschiedene Datenbanktypen unterstützt.</span><span class="sxs-lookup"><span data-stu-id="755db-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a distributed and scalable data store, supporting multiple different types of databases.</span></span>

<span data-ttu-id="755db-107">[Erste Schritte mit Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)</span><span class="sxs-lookup"><span data-stu-id="755db-107">[Get started with Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="755db-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="755db-108">Client library</span></span>

<span data-ttu-id="755db-109">Verwenden Sie die Azure Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Azure Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="755db-109">Use the Azure Cosmos DB .NET client library to access and store data in an existing Azure Cosmos DB data store.</span></span>  <span data-ttu-id="755db-110">Die Erstellung eines neuen Azure Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.</span><span class="sxs-lookup"><span data-stu-id="755db-110">To automate creation of a new Azure Cosmos DB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="755db-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="755db-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="755db-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="755db-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="755db-113">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="755db-113">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="755db-114">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="755db-114">Code Example</span></span>

<span data-ttu-id="755db-115">In diesem Beispiel wird eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert.</span><span class="sxs-lookup"><span data-stu-id="755db-115">This example connects to an existing Azure Cosmos DB SQL API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="755db-116">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="755db-116">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="755db-117">Beispiele</span><span class="sxs-lookup"><span data-stu-id="755db-117">Samples</span></span>

* <span data-ttu-id="755db-118">[Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/) (Entwickeln einer .NET-App mit der MongoDB-API von Azure Cosmos DB)</span><span class="sxs-lookup"><span data-stu-id="755db-118">[Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)</span></span>

<span data-ttu-id="755db-119">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.</span><span class="sxs-lookup"><span data-stu-id="755db-119">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
