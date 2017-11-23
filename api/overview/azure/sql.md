---
title: "Azure SQL-Datenbank-APIs für .NET"
description: "Referenz für Azure SQL-Datenbank-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, SQL, SQL-Datenbank
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: sql-database
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 3aba3c77935e0f00c7396b4cafa06be32ae2a50d
ms.sourcegitcommit: c360a22d5bff6eedd714b28b847d2f26b06665f4
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/15/2017
---
# <a name="azure-sql-database-apis-for-net"></a><span data-ttu-id="17cd1-104">Azure SQL-Datenbank-APIs für .NET</span><span class="sxs-lookup"><span data-stu-id="17cd1-104">Azure SQL Database APIs for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="17cd1-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="17cd1-105">Overview</span></span>

<span data-ttu-id="17cd1-106">[Azure SQL-Datenbank](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) ist Datenbankdienst, der mit dem Microsoft SQL Server-Modul arbeitet und relationale, JSON-, räumliche und XML-Daten unterstützt.</span><span class="sxs-lookup"><span data-stu-id="17cd1-106">[Azure SQL Database](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) is a database service using the Microsoft SQL Server engine that supports relational, JSON, spatial, and XML data.</span></span> 

<span data-ttu-id="17cd1-107">Weitere Informationen zum Verwenden von SQL-Datenbank mit .NET finden Sie unter [Herstellen einer Verbindung mit einer Azure SQL-Datenbank und Abfragen der Datenbank mit .NET (C#) und Visual Studio](https://docs.microsoft.com/azure/sql-database/sql-database-connect-query-dotnet-visual-studio).</span><span class="sxs-lookup"><span data-stu-id="17cd1-107">To learn more about the using SQL Database with .NET, see [Use .NET with Visual Studio to connect and query an Azure SQL database](https://docs.microsoft.com/azure/sql-database/sql-database-connect-query-dotnet-visual-studio).</span></span>

## <a name="client-library"></a><span data-ttu-id="17cd1-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="17cd1-108">Client library</span></span>

<span data-ttu-id="17cd1-109">Verwenden Sie die .NET SQL-Clientbibliothek, um sich mit Ihrer Datenbank zu verbinden, sich bei ihr zu authentifizieren sowie T-SQL-Anweisungen und gespeicherte Prozeduren ad hoc auszuführen.</span><span class="sxs-lookup"><span data-stu-id="17cd1-109">Use the .NET SQL client library to connect and authenticate with your database and execute ad-hoc T-SQL statements and stored procedures.</span></span>

<span data-ttu-id="17cd1-110">Installieren Sie das [NuGet-Paket]( https://www.nuget.org/packages/System.Data.SqlClient) direkt über die [Paket-Manager-Konsole](https://docs.microsoft.com/nuget/tools/package-manager-console) in Visual Studio oder mit der [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).</span><span class="sxs-lookup"><span data-stu-id="17cd1-110">Install the [NuGet package]( https://www.nuget.org/packages/System.Data.SqlClient) directly from the Visual Studio [Package Manager console](https://docs.microsoft.com/nuget/tools/package-manager-console) or with the [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="17cd1-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="17cd1-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package System.Data.SqlClient
```

#### <a name="net-core-cli"></a><span data-ttu-id="17cd1-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="17cd1-112">.NET Core CLI</span></span>

```bash
dotnet add package System.Data.SqlClient
```

### <a name="code-example"></a><span data-ttu-id="17cd1-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="17cd1-113">Code Example</span></span>

<span data-ttu-id="17cd1-114">In diesem Beispiel wird eine Verbindung mit einer Datenbank hergestellt. Anschließend werden Zeilen in einer Tabelle gelesen.</span><span class="sxs-lookup"><span data-stu-id="17cd1-114">This example connects to a database and reads rows from a table.</span></span>

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
> [<span data-ttu-id="17cd1-115">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="17cd1-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/sql/client)

## <a name="management-library"></a><span data-ttu-id="17cd1-116">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="17cd1-116">Management library</span></span>

<span data-ttu-id="17cd1-117">Verwenden Sie die Verwaltungsbibliothek für Azure SQL-Datenbank zum Erstellen, Verwalten und Skalieren von Serverinstanzen von Azure SQL-Datenbank.</span><span class="sxs-lookup"><span data-stu-id="17cd1-117">Use the Azure SQL Database management library to create, manage, and scale Azure SQL Database server instances.</span></span>

<span data-ttu-id="17cd1-118">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent/) direkt über die [Paket-Manager-Konsole](https://docs.microsoft.com/nuget/tools/package-manager-console) in Visual Studio oder mit der [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).</span><span class="sxs-lookup"><span data-stu-id="17cd1-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Sql.Fluent/) directly from the Visual Studio [Package Manager console](https://docs.microsoft.com/nuget/tools/package-manager-console) or with the [.NET Core CLI](https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package).</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="17cd1-119">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="17cd1-119">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Sql.Fluent
``` 

#### <a name="net-core-command-line"></a><span data-ttu-id="17cd1-120">.NET Core-Befehlszeile</span><span class="sxs-lookup"><span data-stu-id="17cd1-120">.NET Core command line</span></span>

```bash
dotnet add package Microsoft.Azure.Management.Sql.Fluent
```

### <a name="code-example"></a><span data-ttu-id="17cd1-121">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="17cd1-121">Code Example</span></span>

<span data-ttu-id="17cd1-122">In diesem Beispiel wird zuerst eine Serverinstanz von SQL-Datenbank und anschließend eine neue Datenbank in dieser Instanz erstellt.</span><span class="sxs-lookup"><span data-stu-id="17cd1-122">This example creates a new SQL Database server instance and then creates a new database on that instance.</span></span>

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
> [<span data-ttu-id="17cd1-123">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="17cd1-123">Explore the management APIs</span></span>](/dotnet/api/overview/azure/sql/management)

## <a name="samples"></a><span data-ttu-id="17cd1-124">Beispiele</span><span class="sxs-lookup"><span data-stu-id="17cd1-124">Samples</span></span>

- <span data-ttu-id="17cd1-125">[ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)</span><span class="sxs-lookup"><span data-stu-id="17cd1-125">[ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples)</span></span>
- [<span data-ttu-id="17cd1-126">Azure-Verwaltungsbibliotheken für .NET-Beispiele für SQL-Datenbank</span><span class="sxs-lookup"><span data-stu-id="17cd1-126">Azure management libraries for .NET samples for SQL Database</span></span>](/dotnet/azure/dotnet-sdk-azure-sql-database-samples)

<span data-ttu-id="17cd1-127">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=sql+database) von Beispielen für Azure SQL-Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="17cd1-127">View the [complete list](https://azure.microsoft.com/en-us/resources/samples/?platform=dotnet&term=sql+database) of Azure SQL Database samples.</span></span>

