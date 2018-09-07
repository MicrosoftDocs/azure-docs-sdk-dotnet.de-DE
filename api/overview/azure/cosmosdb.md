---
title: Azure Cosmos DB-Bibliotheken für .NET
description: Referenz für Azure Cosmos DB-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Cosmos DB
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 08/31/2018
ms.topic: reference
ms.devlang: dotnet
ms.service: cosmos-db
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 4928c1dfdb7a5bb50ca4f5023cbfec71e05e9061
ms.sourcegitcommit: 299aa7bdbb9cec1b56e42e25550999e53e23de2c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/06/2018
ms.locfileid: "43839496"
---
# <a name="azure-cosmos-db-libraries-for-net"></a><span data-ttu-id="02c65-104">Azure Cosmos DB-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="02c65-104">Azure Cosmos DB libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="02c65-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="02c65-105">Overview</span></span>

<span data-ttu-id="02c65-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein global verteilter Datenbankdienst mit Unterstützung mehrerer Modelle.</span><span class="sxs-lookup"><span data-stu-id="02c65-106">[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) is a globally distributed, multi-model database service.</span></span> <span data-ttu-id="02c65-107">Mit diesem Dienst können Sie in einer beliebigen Anzahl von geografischen Azure-Regionen mit einer umfassenden SLA elastische und unabhängige Skalierungen für Durchsatz und Speicher durchführen.</span><span class="sxs-lookup"><span data-stu-id="02c65-107">It is designed to elastically and independently scale throughput and storage across any number of geographical regions with a comprehensive SLA.</span></span> <span data-ttu-id="02c65-108">Mit Azure Cosmos DB können Sie unter Verwendung von APIs und Programmiermodellen Datenbanken mit Dokumenten, Schlüsselwerten, breiten Spalten und Graphen speichern und auf die Datenbanken zugreifen.</span><span class="sxs-lookup"><span data-stu-id="02c65-108">With Azure Cosmos DB, you can store and access document, key-value, wide-column, and graph databases by using APIs and programming models.</span></span> 

<span data-ttu-id="02c65-109">[Erste Schritte mit Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)</span><span class="sxs-lookup"><span data-stu-id="02c65-109">[Get started with Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="02c65-110">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="02c65-110">Client library</span></span>

<span data-ttu-id="02c65-111">Verwenden Sie die Azure Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Azure Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern.</span><span class="sxs-lookup"><span data-stu-id="02c65-111">Use the Azure Cosmos DB .NET client library to access and store data in an existing Azure Cosmos DB data store.</span></span> <span data-ttu-id="02c65-112">Die Erstellung eines neuen Azure Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.</span><span class="sxs-lookup"><span data-stu-id="02c65-112">To automate creation of a new Azure Cosmos DB account, use the Azure portal, CLI, or PowerShell.</span></span>

<span data-ttu-id="02c65-113">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="02c65-113">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="02c65-114">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="02c65-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a><span data-ttu-id="02c65-115">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="02c65-115">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a><span data-ttu-id="02c65-116">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="02c65-116">Code Example</span></span>

<span data-ttu-id="02c65-117">In diesem Beispiel wird eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert.</span><span class="sxs-lookup"><span data-stu-id="02c65-117">This example connects to an existing Azure Cosmos DB SQL API database, reads a document from a collection, and deserializes it as an `Item` object.</span></span>   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="02c65-118">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="02c65-118">Explore the client APIs</span></span>](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a><span data-ttu-id="02c65-119">Beispiele</span><span class="sxs-lookup"><span data-stu-id="02c65-119">Samples</span></span>

* <span data-ttu-id="02c65-120">[Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/) (Entwickeln einer .NET-App mit der MongoDB-API von Azure Cosmos DB)</span><span class="sxs-lookup"><span data-stu-id="02c65-120">[Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/)</span></span>

<span data-ttu-id="02c65-121">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.</span><span class="sxs-lookup"><span data-stu-id="02c65-121">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) of Azure Cosmos DB samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
