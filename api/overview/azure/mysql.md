---
title: "Bibliotheken zu Azure-Datenbank für MySQL für .NET"
description: "Referenzdokumentation für die .NET-Clientbibliotheken für Azure-Datenbank für MySQL"
keywords: Azure, .NET, SDK, API, SQL, Datenbank, MySQL
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: mysql
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 27c1a2c7d36966d14daff5397b248a24197bec3b
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-database-for-mysql-libraries-for-net"></a>Bibliotheken zu Azure-Datenbank für MySQL für .NET

## <a name="overview"></a>Übersicht

Arbeiten Sie mit Daten und Ressourcen, die in [Azure-Datenbank für MySQL](/azure/mysql/overview) gespeichert sind.

## <a name="client-apis"></a>Client-APIs

Die empfohlene Clientbibliothek für den Zugriff auf Azure-Datenbank für MySQL ist [Connector/Net](https://dev.mysql.com/doc/connector-net/en) von MySQL. Verwenden Sie das Paket zum Herstellen einer Verbindung mit der Datenbank und Ausführen von SQL-Anweisungen direkt. 

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/MySql.Data) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package MySql.Data
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package MySql.Data
```

### <a name="code-example"></a>Codebeispiel

Herstellen einer Verbindung mit einer MySQL-Datenbank und Ausführen einer Abfrage:

```csharp
/* Include this "using" directive...
using MySql.Data.MySqlClient;
*/

string connectionString = "Server=[servername].mysql.database.azure.com; " +
    "Database=myDataBase; Uid=[userid]@[servername]; Pwd=myPassword;";

// Best practice is to scope the MySqlConnection to a "using" block
using (MySqlConnection conn = new MySqlConnection(connectionString))
{
    // Connect to the database
    conn.Open();

    // Read rows
    MySqlCommand selectCommand = new MySqlCommand("SELECT * FROM MyTable", conn);
    MySqlDataReader results = selectCommand.ExecuteReader();
    
    // Enumerate over the rows
    while(results.Read())
    {
        Console.WriteLine("Column 0: {0} Column 1: {1}", results[0], results[1]);
    }
}
```

## <a name="samples"></a>Beispiele

- [ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)
- [Entwerfen Ihrer ersten Azure-Datenbank für MySQL](https://docs.microsoft.com/azure/mysql/tutorial-design-database-using-cli) 

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
