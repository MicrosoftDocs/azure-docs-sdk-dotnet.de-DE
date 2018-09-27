---
title: Azure Cosmos DB-Bibliotheken für .NET
description: Referenz für Azure Cosmos DB-Bibliotheken für .NET
ms.date: 08/31/2018
ms.topic: reference
ms.service: cosmos-db
ms.openlocfilehash: 21a2f2168259528a0d27103783e34aa532d7e17a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190792"
---
# <a name="azure-cosmos-db-libraries-for-net"></a>Azure Cosmos DB-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein global verteilter Datenbankdienst mit Unterstützung mehrerer Modelle. Mit diesem Dienst können Sie in einer beliebigen Anzahl von geografischen Azure-Regionen mit einer umfassenden SLA elastische und unabhängige Skalierungen für Durchsatz und Speicher durchführen. Mit Azure Cosmos DB können Sie unter Verwendung von APIs und Programmiermodellen Datenbanken mit Dokumenten, Schlüsselwerten, breiten Spalten und Graphen speichern und auf die Datenbanken zugreifen. 

[Erste Schritte mit Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet)

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Azure Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Azure Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern. Die Erstellung eines neuen Azure Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.DocumentDB.Core) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.DocumentDB.Core
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.DocumentDB.Core
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird eine Verbindung mit einer vorhandenen Azure Cosmos DB-SQL-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert.   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString();
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>Beispiele

* [Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/) (Entwickeln einer .NET-App mit der MongoDB-API von Azure Cosmos DB)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
