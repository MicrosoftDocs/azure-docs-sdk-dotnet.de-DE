---
title: Azure Cosmos DB-Bibliotheken für .NET
description: Referenz für Azure Cosmos DB-Bibliotheken für .NET
ms.date: 08/31/2018
ms.topic: reference
ms.service: cosmos-db
ms.openlocfilehash: 95fcd8468c3d472cfcadeaae3b56ae789c3b1e7a
ms.sourcegitcommit: 55ee51501678d1575e5159f0ac0e475b5bf9daf3
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/22/2019
ms.locfileid: "54453994"
---
# <a name="azure-cosmos-db-libraries-for-net"></a><span data-ttu-id="9c244-103">Azure Cosmos DB-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="9c244-103">Azure Cosmos DB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="9c244-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="9c244-104">Overview</span></span>

<span data-ttu-id="9c244-105">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein global verteilter Datenbankdienst mit Unterstützung mehrerer Modelle.</span><span class="sxs-lookup"><span data-stu-id="9c244-105">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a globally distributed, multi-model database service.</span></span> <span data-ttu-id="9c244-106">Mit diesem Dienst können Sie in einer beliebigen Anzahl von geografischen Azure-Regionen mit einer umfassenden SLA elastische und unabhängige Skalierungen für Durchsatz und Speicher durchführen.</span><span class="sxs-lookup"><span data-stu-id="9c244-106">It is designed to elastically and independently scale throughput and storage across any number of geographical regions with a comprehensive SLA.</span></span> <span data-ttu-id="9c244-107">Mit Azure Cosmos DB können Sie unter Verwendung von APIs und Programmiermodellen Datenbanken mit Dokumenten, Schlüsselwerten, breiten Spalten und Graphen speichern und auf die Datenbanken zugreifen.</span><span class="sxs-lookup"><span data-stu-id="9c244-107">With Azure Cosmos DB, you can store and access document, key-value, wide-column, and graph databases by using APIs and programming models.</span></span> 

<span data-ttu-id="9c244-108">[Erste Schritte mit Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)</span><span class="sxs-lookup"><span data-stu-id="9c244-108">[Get started with Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="9c244-109">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="9c244-109">Client library</span></span>

<span data-ttu-id="9c244-110">Verwenden Sie die Azure Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Azure Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="9c244-110">Use the Azure Cosmos DB .NET client library to access and store data in an existing Azure Cosmos DB data store.</span></span> <span data-ttu-id="9c244-111">Die Erstellung eines neuen Azure Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.</span><span class="sxs-lookup"><span data-stu-id="9c244-111">To automate creation of a new Azure Cosmos DB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="9c244-112">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="9c244-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

<span data-ttu-id="9c244-113">So installieren Sie Version 2.x:</span><span class="sxs-lookup"><span data-stu-id="9c244-113">To install version 2.x:</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="9c244-114">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="9c244-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="9c244-115">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="9c244-115">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

<span data-ttu-id="9c244-116">So installieren Sie die Vorschau von Version 3.0 für .NET Standard:</span><span class="sxs-lookup"><span data-stu-id="9c244-116">To install the preview of version 3.0, which targets .NET standard:</span></span> 

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="9c244-117">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="9c244-117">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Cosmos -prerelease
```

#### <a name="net-core-cli"></a><span data-ttu-id="9c244-118">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="9c244-118">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Cosmos
```


### <a name="code-example"></a><span data-ttu-id="9c244-119">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="9c244-119">Code Example</span></span>

<span data-ttu-id="9c244-120">In diesem Beispiel wird eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `TodoItem`-Objekt deserialisiert.</span><span class="sxs-lookup"><span data-stu-id="9c244-120">This example connects to an existing Azure Cosmos DB SQL API database, reads a document from a collection, and deserializes it as an `TodoItem` object.</span></span> <span data-ttu-id="9c244-121">In diesem Beispiel wird Version 2.x des .NET SDK verwendet.</span><span class="sxs-lookup"><span data-stu-id="9c244-121">This example uses version 2.x of the .NET SDK.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
var todoItem = client.ReadDocumentAsync<TodoItem>(documentUri);
```

<span data-ttu-id="9c244-122">In diesem Beispiel stellen Sie eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank her. Darüber hinaus erstellen Sie eine neue Datenbank und einen neuen Container, lesen ein Element aus dem Container und deserialisieren es in ein `TodoItem`-Objekt.</span><span class="sxs-lookup"><span data-stu-id="9c244-122">This example connects to an existing Azure Cosmos DB SQL API database, creates a new database and container, reads an item from the container, and deserializes it to a `TodoItem` object.</span></span> <span data-ttu-id="9c244-123">In diesem Beispiel wird Version 3.x des .NET SDK verwendet.</span><span class="sxs-lookup"><span data-stu-id="9c244-123">This example uses version 3.x of the .NET SDK.</span></span>   

```csharp
using (CosmosClient cosmosClient = new CosmosClient("endpoint", "primaryKey"))
{
    // Read item from container
    CosmosItemResponse<TodoItem> todoItemResponse = await cosmosClient.Databases["DatabaseId"].Containers["ContainerId"].Items.ReadItemAsync<TodoItem>("partitionKeyValue", "ItemId");
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="9c244-124">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="9c244-124">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="9c244-125">Beispiele</span><span class="sxs-lookup"><span data-stu-id="9c244-125">Samples</span></span>

* <span data-ttu-id="9c244-126">[Developing a .NET app using Azure Cosmos DB's SQL API (Version 2.x)](https://github.com/Azure-Samples/documentdb-dotnet-todo-app/) (Entwickeln einer .NET-App mit der SQL-API von Azure Cosmos DB (Version 2.x))</span><span class="sxs-lookup"><span data-stu-id="9c244-126">[Developing a .NET app using Azure Cosmos DB's SQL API (Version 2.x)](https://github.com/Azure-Samples/documentdb-dotnet-todo-app/)</span></span>
* <span data-ttu-id="9c244-127">[Developing a .NET app using Azure Cosmos DB's SQL API (Version 3.x Preview)](https://github.com/Azure-Samples/cosmos-dotnet-todo-app/) (Entwickeln einer .NET-App mit der SQL-API von Azure Cosmos DB (Vorschau von Version 3.x))</span><span class="sxs-lookup"><span data-stu-id="9c244-127">[Developing a .NET app using Azure Cosmos DB's SQL API (Version 3.x Preview)](https://github.com/Azure-Samples/cosmos-dotnet-todo-app/)</span></span>
* <span data-ttu-id="9c244-128">[Developing a .NET Core app using Azure Cosmos DB's SQL API (Version 3.x Preview)](https://github.com/Azure-Samples/cosmos-dotnet-core-getting-started) (Entwickeln einer .NET Core-App mit der SQL-API von Azure Cosmos DB (Vorschau von Version 3.x))</span><span class="sxs-lookup"><span data-stu-id="9c244-128">[Developing a .NET Core app using Azure Cosmos DB's SQL API (Version 3.x Preview)](https://github.com/Azure-Samples/cosmos-dotnet-core-getting-started)</span></span>

<span data-ttu-id="9c244-129">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.</span><span class="sxs-lookup"><span data-stu-id="9c244-129">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
