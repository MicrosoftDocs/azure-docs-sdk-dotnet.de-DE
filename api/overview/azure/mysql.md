---
title: "Bibliotheken zu Azure-Datenbank für MySQL für .NET"
description: "Referenzdokumentation für die .NET-Clientbibliotheken für Azure-Datenbank für MySQL"
keywords: Azure, .NET, SDK, API, SQL, Datenbank, MySQL
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: mysql
ms.openlocfilehash: 1bc373d63b0172fd554277a6ef30fa09772a395b
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-database-for-mysql-libraries-for-net"></a><span data-ttu-id="6ef02-104">Bibliotheken zu Azure-Datenbank für MySQL für .NET</span><span class="sxs-lookup"><span data-stu-id="6ef02-104">Azure Database for MySQL libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="6ef02-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="6ef02-105">Overview</span></span>

<span data-ttu-id="6ef02-106">Arbeiten Sie mit Daten und Ressourcen, die in [Azure-Datenbank für MySQL](/azure/mysql/overview) gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="6ef02-106">Work with data and resources stored in [Azure Database for MySQL](/azure/mysql/overview).</span></span>

## <a name="client-apis"></a><span data-ttu-id="6ef02-107">Client-APIs</span><span class="sxs-lookup"><span data-stu-id="6ef02-107">Client APIs</span></span>

<span data-ttu-id="6ef02-108">Die empfohlene Clientbibliothek für den Zugriff auf Azure-Datenbank für MySQL ist [Connector/Net](https://dev.mysql.com/doc/connector-net/en) von MySQL.</span><span class="sxs-lookup"><span data-stu-id="6ef02-108">The recommended client library for accessing Azure Database for MySQL is MySQL's [Connector/Net](https://dev.mysql.com/doc/connector-net/en).</span></span> <span data-ttu-id="6ef02-109">Verwenden Sie das Paket zum Herstellen einer Verbindung mit der Datenbank und Ausführen von SQL-Anweisungen direkt.</span><span class="sxs-lookup"><span data-stu-id="6ef02-109">Use the package to connect to the database and execute SQL statements directly.</span></span> 

<span data-ttu-id="6ef02-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/MySql.Data) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="6ef02-110">Install the [NuGet package](https://www.nuget.org/packages/MySql.Data) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6ef02-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="6ef02-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package MySql.Data
```

#### <a name="net-core-cli"></a><span data-ttu-id="6ef02-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="6ef02-112">.NET Core CLI</span></span>

```bash
dotnet add package MySql.Data
```

### <a name="code-example"></a><span data-ttu-id="6ef02-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="6ef02-113">Code Example</span></span>

<span data-ttu-id="6ef02-114">Herstellen einer Verbindung mit einer MySQL-Datenbank und Ausführen einer Abfrage:</span><span class="sxs-lookup"><span data-stu-id="6ef02-114">Connect to a MySQL database and execute a query:</span></span>

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

## <a name="samples"></a><span data-ttu-id="6ef02-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="6ef02-115">Samples</span></span>

- [<span data-ttu-id="6ef02-116">ADO.NET code examples</span><span class="sxs-lookup"><span data-stu-id="6ef02-116">ADO.NET code examples</span></span>](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)
- [<span data-ttu-id="6ef02-117">Entwerfen Ihrer ersten Azure-Datenbank für MySQL</span><span class="sxs-lookup"><span data-stu-id="6ef02-117">Design a MySQL database using the Azure CLI</span></span>](https://docs.microsoft.com/azure/mysql/tutorial-design-database-using-cli) 

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
