---
title: "Bibliotheken zu Azure-Datenbank für PostgreSQL für .NET"
description: "Referenzdokumentation für die .NET-Clientbibliotheken für Azure-Datenbank für PostgreSQL"
keywords: Azure, .NET ODBC, SDK, API, SQL, ADO.NET, Datenbank, PostGres, PostgreSQL
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: postgresql
ms.openlocfilehash: 899002b12dd36e6b23a05c8516670ff841abed79
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-database-for-postgresql-libraries-for-net"></a>Bibliotheken zu Azure-Datenbank für PostgreSQL für .NET

## <a name="overview"></a>Übersicht

Arbeiten Sie mit Daten und Ressourcen, die in [Azure-Datenbank für PostgreSQL](https://docs.microsoft.com/azure/postgresql/) gespeichert sind.

## <a name="client-api"></a>Client-API

Die empfohlene Clientbibliothek für den Zugriff auf Azure-Datenbank für PostgreSQL ist der [Npgsql-ADO.NET-Datenanbieter](http://www.npgsql.org/) (Open-Source). Verwenden Sie den ADO.NET-Anbieter, um eine Verbindung mit der Datenbank herzustellen und SQL-Anweisungen direkt oder über Entity Framework mit den Npgsql-Anbietern [Entity Framework 6](http://www.npgsql.org/ef6/index.html) oder [Entity Framework Core](http://www.npgsql.org/efcore/index.html) auszuführen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Npgsql) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Npgsql
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Npgsql
```

### <a name="code-example"></a>Codebeispiel

```csharp
/* Include this 'using' directive...
using Npgsql;
*/

// Always store connection strings securely. 
string connectionString = "Server=[servername].postgres.database.azure.com; " +
    "Port=5432; Database=myDataBase; User Id=[userid]@[servername]; Password=password;";

// Best practice is to scope the NpgsqlConnection to a "using" block
using (NpgsqlConnection conn = new NpgsqlConnection(connectionString))
{
    // Connect to the database
    conn.Open();

    // Read rows
    NpgsqlCommand selectCommand = new NpgsqlCommand("SELECT * FROM MyTable", conn);
    NpgsqlDataReader results = selectCommand.ExecuteReader();
    
    // Enumerate over the rows
    while(results.Read())
    {
        Console.WriteLine("Column 0: {0} Column 1: {1}", results[0], results[1]);
    }
}
```

### <a name="samples"></a>Beispiele

- [ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)
- [Entwerfen Ihrer ersten Azure-Datenbank für PostgreSQL mithilfe von Azure CLI](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli) [PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console [DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package