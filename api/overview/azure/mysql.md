---
title: Bibliotheken zu Azure-Datenbank für MySQL für .NET
description: Referenzdokumentation für die .NET-Clientbibliotheken für Azure-Datenbank für MySQL
ms.date: 10/19/2017
ms.topic: reference
ms.service: mysql
ms.openlocfilehash: 34550c7089a2ec05164f7a16f24bfc8b18391f8a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190153"
---
# <a name="azure-database-for-mysql-libraries-for-net"></a><span data-ttu-id="e8a6b-103">Bibliotheken zu Azure-Datenbank für MySQL für .NET</span><span class="sxs-lookup"><span data-stu-id="e8a6b-103">Azure Database for MySQL libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="e8a6b-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="e8a6b-104">Overview</span></span>

<span data-ttu-id="e8a6b-105">Arbeiten Sie mit Daten und Ressourcen, die in [Azure-Datenbank für MySQL](/azure/mysql/overview) gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="e8a6b-105">Work with data and resources stored in [Azure Database for MySQL](/azure/mysql/overview).</span></span>

## <a name="client-apis"></a><span data-ttu-id="e8a6b-106">Client-APIs</span><span class="sxs-lookup"><span data-stu-id="e8a6b-106">Client APIs</span></span>

<span data-ttu-id="e8a6b-107">Die empfohlene Clientbibliothek für den Zugriff auf Azure-Datenbank für MySQL ist [Connector/Net](https://dev.mysql.com/doc/connector-net/en) von MySQL.</span><span class="sxs-lookup"><span data-stu-id="e8a6b-107">The recommended client library for accessing Azure Database for MySQL is MySQL's [Connector/Net](https://dev.mysql.com/doc/connector-net/en).</span></span> <span data-ttu-id="e8a6b-108">Verwenden Sie das Paket zum Herstellen einer Verbindung mit der Datenbank und Ausführen von SQL-Anweisungen direkt.</span><span class="sxs-lookup"><span data-stu-id="e8a6b-108">Use the package to connect to the database and execute SQL statements directly.</span></span> 

<span data-ttu-id="e8a6b-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/MySql.Data) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="e8a6b-109">Install the [NuGet package](https://www.nuget.org/packages/MySql.Data) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="e8a6b-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="e8a6b-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package MySql.Data
```

#### <a name="net-core-cli"></a><span data-ttu-id="e8a6b-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="e8a6b-111">.NET Core CLI</span></span>

```bash
dotnet add package MySql.Data
```

### <a name="code-example"></a><span data-ttu-id="e8a6b-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="e8a6b-112">Code Example</span></span>

<span data-ttu-id="e8a6b-113">Herstellen einer Verbindung mit einer MySQL-Datenbank und Ausführen einer Abfrage:</span><span class="sxs-lookup"><span data-stu-id="e8a6b-113">Connect to a MySQL database and execute a query:</span></span>

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

## <a name="samples"></a><span data-ttu-id="e8a6b-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="e8a6b-114">Samples</span></span>

- <span data-ttu-id="e8a6b-115">[ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples) (ADO.NET-Codebeispiele)</span><span class="sxs-lookup"><span data-stu-id="e8a6b-115">[ADO.NET code examples](/dotnet/framework/data/adonet/ado-net-code-examples)</span></span>
- [<span data-ttu-id="e8a6b-116">Entwerfen Ihrer ersten Azure-Datenbank für MySQL</span><span class="sxs-lookup"><span data-stu-id="e8a6b-116">Design a MySQL database using the Azure CLI</span></span>](https://docs.microsoft.com/azure/mysql/tutorial-design-database-using-cli) 

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
