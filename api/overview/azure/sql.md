---
title: Azure SQL-Datenbank-APIs für .NET
description: Referenz für Azure SQL-Datenbank-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, SQL, SQL-Datenbank
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: sql-database
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 8096e66be1263bc50648ef5b9b16f3fc2bd08ac8
ms.sourcegitcommit: 512e031ead61a578ac96835c8ea01829842740bf
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/18/2018
ms.locfileid: "39116676"
---
# <a name="azure-sql-database-apis-for-net"></a>Azure SQL-Datenbank-APIs für .NET

## <a name="overview"></a>Übersicht

[Azure SQL-Datenbank](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) ist ein Datenbankdienst, der mit der Microsoft SQL Server-Engine arbeitet und relationale, JSON-, räumliche und XML-Daten unterstützt. 

Weitere Informationen zum Verwenden von SQL-Datenbank mit .NET finden Sie unter [Herstellen einer Verbindung mit einer Azure SQL-Datenbank und Abfragen der Datenbank mit .NET (C#) und Visual Studio](https://docs.microsoft.com/azure/sql-database/sql-database-connect-query-dotnet-visual-studio).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die .NET SQL-Clientbibliothek, um sich mit Ihrer Datenbank zu verbinden, sich bei ihr zu authentifizieren sowie T-SQL-Anweisungen und gespeicherte Prozeduren ad hoc auszuführen.

Installieren Sie das [NuGet-Paket]( https://www.nuget.org/packages/System.Data.SqlClient) direkt über die [Paket-Manager-Konsole](https://docs.microsoft.com/nuget/tools/package-manager-console) in Visual Studio oder mit der [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package System.Data.SqlClient
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package System.Data.SqlClient
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird eine Verbindung mit einer Datenbank hergestellt. Anschließend werden Zeilen in einer Tabelle gelesen.

```csharp
/* Include this 'using' directive...
using System.Data.SqlClient;
*/

// Always store connection strings securely. 
string connectionString = "Server=tcp:[serverName].database.windows.net;" 
    + "Database=myDataBase;User ID=[loginname]@[serverName];Password=myPassword;"
    + "Trusted_Connection=False;Encrypt=True;";

// Best practice is to scope the SqlConnection to a "using" block
using (SqlConnection conn = new SqlConnection(connectionString))
{
    // Connect to the database
    conn.Open();

    // Read rows
    SqlCommand selectCommand = new SqlCommand("SELECT * FROM MyTable", conn);
    SqlDataReader results = selectCommand.ExecuteReader();
    
    // Enumerate over the rows
    while(results.Read())
    {
        Console.WriteLine("Column 0: {0} Column 1: {1}", results[0], results[1]);
    }
}
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/sql/client)

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek für Azure SQL-Datenbank zum Erstellen, Verwalten und Skalieren von Serverinstanzen von Azure SQL-Datenbank.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent/) direkt über die [Paket-Manager-Konsole](https://docs.microsoft.com/nuget/tools/package-manager-console) in Visual Studio oder mit der [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Sql.Fluent
``` 

#### <a name="net-core-command-line"></a>.NET Core-Befehlszeile

```bash
dotnet add package Microsoft.Azure.Management.Sql.Fluent
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird zuerst eine Serverinstanz von SQL-Datenbank und anschließend eine neue Datenbank in dieser Instanz erstellt.

```csharp
/* Include these 'using' directives...
using Microsoft.Azure.Management.Sql.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

string startAddress = "0.0.0.0";
string endAddress = "255.255.255.255";

// Create the SQL server instance
ISqlServer sqlServer = azure.SqlServers.Define("UniqueServerName")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup("ResourceGroupName")
    .WithAdministratorLogin("UserName")
    .WithAdministratorPassword("Password")
    .WithNewFirewallRule(startAddress, endAddress)
    .Create();

// Create the database
ISqlDatabase sqlDb = sqlServer.Databases.Define("DatabaseName").Create();
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/sql/management)

## <a name="samples"></a>Beispiele

- [ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)
- [Azure-Verwaltungsbibliotheken für .NET-Beispiele für SQL-Datenbank](/dotnet/azure/dotnet-sdk-azure-sql-database-samples)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=sql+database) von Beispielen für Azure SQL-Datenbank an.

