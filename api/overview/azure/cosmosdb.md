---
title: Azure Cosmos DB-Bibliotheken für .NET
description: Referenz für Azure Cosmos DB-Bibliotheken für .NET
ms.date: 08/31/2018
ms.topic: reference
ms.service: cosmos-db
ms.openlocfilehash: 8ff565f1cd72eec2f574b45d04ceac526b8c5eb0
ms.sourcegitcommit: 01ec3adba39a6f946015552c28da0a9a6bb57180
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/08/2018
ms.locfileid: "53112018"
---
# <a name="azure-cosmos-db-libraries-for-net"></a>Azure Cosmos DB-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein global verteilter Datenbankdienst mit Unterstützung mehrerer Modelle. Mit diesem Dienst können Sie in einer beliebigen Anzahl von geografischen Azure-Regionen mit einer umfassenden SLA elastische und unabhängige Skalierungen für Durchsatz und Speicher durchführen. Mit Azure Cosmos DB können Sie unter Verwendung von APIs und Programmiermodellen Datenbanken mit Dokumenten, Schlüsselwerten, breiten Spalten und Graphen speichern und auf die Datenbanken zugreifen. 

[Erste Schritte mit Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Azure Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Azure Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern. Die Erstellung eines neuen Azure Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

So installieren Sie Version 2.x:

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

So installieren Sie die Vorschau von Version 3.0 für .NET Standard: 

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Cosmos -prerelease
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Cosmos
```


### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert. In diesem Beispiel wird Version 2.x des .NET SDK verwendet.   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString();
```

In diesem Beispiel stellen Sie eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank her. Darüber hinaus erstellen Sie eine neue Datenbank und einen neuen Container, lesen ein Element aus dem Container und deserialisieren es in ein `TodoItem`-Objekt. In diesem Beispiel wird Version 3.x des .NET SDK verwendet.   

```csharp
using (CosmosClient cosmosClient = new CosmosClient("endpoint", "primaryKey"))
{
    // Read item from container
    CosmosItemResponse<TodoItem> todoItemResponse = await cosmosClient.Databases["DatabaseId"].Containers["ContainerId"].Items.ReadItemAsync<TodoItem>("partitionKeyValue", "ItemId");
}
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>Beispiele

* [Developing a .NET app using Azure Cosmos DB's SQL API (Version 2.x)](https://github.com/Azure-Samples/documentdb-dotnet-todo-app/) (Entwickeln einer .NET-App mit der SQL-API von Azure Cosmos DB (Version 2.x))
* [Developing a .NET app using Azure Cosmos DB's SQL API (Version 3.x Preview)](https://github.com/Azure-Samples/cosmos-dotnet-todo-app/) (Entwickeln einer .NET-App mit der SQL-API von Azure Cosmos DB (Vorschau von Version 3.x))
* [Developing a .NET Core app using Azure Cosmos DB's SQL API (Version 3.x Preview)](https://github.com/Azure-Samples/cosmos-dotnet-core-getting-started) (Entwickeln einer .NET Core-App mit der SQL-API von Azure Cosmos DB (Vorschau von Version 3.x))

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
