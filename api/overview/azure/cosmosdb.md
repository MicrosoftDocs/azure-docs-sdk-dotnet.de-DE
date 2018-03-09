---
title: "Azure Cosmos DB-Bibliotheken für .NET"
description: "Referenz für Azure Cosmos DB-Bibliotheken für .NET"
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
# <a name="azure-cosmosdb-libraries-for-net"></a>Azure Cosmos DB-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/introduction) ist ein verteilter und skalierbarer Datenspeicher, der viele verschiedene Datenbanktypen unterstützt.

[Erste Schritte mit CosmosDB](https://docs.microsoft.com/azure/cosmos-db/create-documentdb-dotnet).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Cosmos DB-.NET-Clientbibliothek, um auf Daten in einem vorhandenen Cosmos DB-Datenspeicher zuzugreifen und Daten dort zu speichern.  Die Erstellung eines neuen Cosmos DB-Kontos können Sie mit dem Azure-Portal, mit der CLI oder mit PowerShell automatisieren.

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

In diesem Beispiel wird eine Verbindung mit einer vorhandenen Cosmos DB-DocumentDB-API-Datenbank hergestellt sowie ein Dokument aus einer Sammlung gelesen und als `Item`-Objekt deserialisiert.   

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Documents.Client;
*/

DocumentClient client = new DocumentClient(endpointUri, authKeyString);
Uri documentUri = UriFactory.CreateDocumentUri("MyDatabaseName", "MyCollectionName", "DocumentId");
SomeClass myObject = client.ReadDocumentAsync<SomeClass>(documentUri).ToString()).Result;
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/cosmosdb/client)

## <a name="samples"></a>Beispiele

* [Developing a .NET app using Azure Cosmos DB's MongoDB API](https://azure.microsoft.com/resources/samples/azure-cosmos-db-mongodb-dotnet-getting-started/) (Entwickeln einer .NET-App mit der MongoDB-API von Azure Cosmos DB)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=cosmosdb) von Beispielen für Azure Cosmos DB an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
