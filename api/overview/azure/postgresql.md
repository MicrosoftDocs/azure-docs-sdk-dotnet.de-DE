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
# <a name="azure-database-for-postgresql-libraries-for-net"></a><span data-ttu-id="509fb-104">Bibliotheken zu Azure-Datenbank für PostgreSQL für .NET</span><span class="sxs-lookup"><span data-stu-id="509fb-104">Azure Database for PostgreSQL libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="509fb-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="509fb-105">Overview</span></span>

<span data-ttu-id="509fb-106">Arbeiten Sie mit Daten und Ressourcen, die in [Azure-Datenbank für PostgreSQL](https://docs.microsoft.com/azure/postgresql/) gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="509fb-106">Work with data and resources stored in [Azure Database for PostgreSQL](https://docs.microsoft.com/azure/postgresql/).</span></span>

## <a name="client-api"></a><span data-ttu-id="509fb-107">Client-API</span><span class="sxs-lookup"><span data-stu-id="509fb-107">Client API</span></span>

<span data-ttu-id="509fb-108">Die empfohlene Clientbibliothek für den Zugriff auf Azure-Datenbank für PostgreSQL ist der [Npgsql-ADO.NET-Datenanbieter](http://www.npgsql.org/) (Open-Source).</span><span class="sxs-lookup"><span data-stu-id="509fb-108">The recommended client library for accessing Azure Database for PostgreSQL is the open-source [Npgsql ADO.NET data provider](http://www.npgsql.org/).</span></span> <span data-ttu-id="509fb-109">Verwenden Sie den ADO.NET-Anbieter, um eine Verbindung mit der Datenbank herzustellen und SQL-Anweisungen direkt oder über Entity Framework mit den Npgsql-Anbietern [Entity Framework 6](http://www.npgsql.org/ef6/index.html) oder [Entity Framework Core](http://www.npgsql.org/efcore/index.html) auszuführen.</span><span class="sxs-lookup"><span data-stu-id="509fb-109">Use the ADO.NET provider to connect to the database and execute SQL statements directly or through Entity Framework with the Npgsql's [Entity Framework 6](http://www.npgsql.org/ef6/index.html) or [Entity Framework Core](http://www.npgsql.org/efcore/index.html) providers.</span></span>

<span data-ttu-id="509fb-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Npgsql) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="509fb-110">Install the [NuGet package](https://www.nuget.org/packages/Npgsql) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="509fb-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="509fb-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Npgsql
```

#### <a name="net-core-cli"></a><span data-ttu-id="509fb-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="509fb-112">.NET Core CLI</span></span>

```bash
dotnet add package Npgsql
```

### <a name="code-example"></a><span data-ttu-id="509fb-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="509fb-113">Code Example</span></span>

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

### <a name="samples"></a><span data-ttu-id="509fb-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="509fb-114">Samples</span></span>

- [<span data-ttu-id="509fb-115">ADO.NET code examples</span><span class="sxs-lookup"><span data-stu-id="509fb-115">ADO.NET code examples</span></span>](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)
- <span data-ttu-id="509fb-116">[Entwerfen Ihrer ersten Azure-Datenbank für PostgreSQL mithilfe von Azure CLI](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli) [PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console [DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package</span><span class="sxs-lookup"><span data-stu-id="509fb-116">[Design a PostgreSQL database using the Azure CLI](https://docs.microsoft.com/azure/postgresql/tutorial-design-database-using-azure-cli) [PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console [DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package</span></span>