---
title: Bibliotheken zu Azure-Datenbank für PostgreSQL für .NET
description: Referenzdokumentation für die .NET-Clientbibliotheken für Azure-Datenbank für PostgreSQL
ms.date: 10/19/2017
ms.topic: reference
ms.service: postgresql
ms.openlocfilehash: 4137e024eadba93c9cb3e94c1e7478d0816f8370
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190745"
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
- [Entwerfen Ihrer ersten Azure-Datenbank für PostgreSQL mithilfe der Azure CLI](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
