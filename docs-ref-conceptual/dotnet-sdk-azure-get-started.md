---
title: Erste Schritte mit Azure .NET- und .NET Core-APIs
description: Machen Sie sich mit der grundlegenden Verwendung der Azure-Bibliotheken für .NET und .NET Core mit Ihrem eigenen Azure-Abonnement vertraut.
keywords: Azure, .NET, .NET Core, ASP.NET, ASP.NET Core SDK, API, authentifizieren, erste Schritte
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 07/17/2018
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: a8775993e71566b7659a8ae8ceb2c376ece14e45
ms.sourcegitcommit: 779c1b202d3670cfa0b9428c89f830cad9ec7e9d
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/18/2018
ms.locfileid: "39135778"
---
# <a name="get-started-with-the-azure-net-and-net-core-apis"></a>Erste Schritte mit den Azure .NET- und .NET Core-APIs

Dieses Tutorial veranschaulicht die Verwendung mehrerer [Azure-APIs für .NET](/dotnet/api/overview/azure/).  Sie richten die Authentifizierung ein und erstellen und verwenden ein Azure Storage-Konto sowie eine Azure SQL-Datenbank-Instanz. Außerdem stellen Sie einige virtuelle Computer und eine Azure App Service-Web-App über GitHub bereit.

## <a name="prerequisites"></a>Voraussetzungen

- Ein Azure-Konto. Falls Sie noch kein Konto haben, können Sie eine [kostenlose Testversion](https://azure.microsoft.com/free/) verwenden.
- [Azure PowerShell](/powershell/azure/install-azurerm-ps)

## <a name="set-up-authentication"></a>Einrichten der Authentifizierung

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="create-a-new-project"></a>Erstellen eines neuen Projekts 

Erstellen Sie ein neues Konsolenanwendungsprojekt.  Klicken Sie dazu in Visual Studio auf **Datei** -> **Neu** und dann auf **Projekt...**.  Wählen Sie unter „Visual C#-Vorlagen“ **Konsolen-App (.NET Core)** aus. Benennen Sie das Projekt, und klicken Sie dann auf **OK**.

![Dialogfeld „Neues Projekt“](media/dotnet-sdk-azure-get-started/new-project.png)

Nachdem die neue Konsolen-App erstellt wurde, öffnen Sie die Paket-Manager-Konsole, indem Sie auf **Extras** -> **NuGet-Paket-Manager** und dann auf **Paket-Manager-Konsole** klicken.  Rufen Sie in der Konsole die benötigten Pakete ab, indem Sie die folgenden drei Befehle ausführen:

```powershell
# Azure Management Libraries for .NET (Fluent)
Install-Package Microsoft.Azure.Management.Fluent

# Azure Store client libraries
Install-Package WindowsAzure.Storage

# SQL Database client libraries
Install-Package System.Data.SqlClient
```

## <a name="directives"></a>Anweisungen

Bearbeiten Sie die Datei `Program.cs` Ihrer Anwendung.  Ersetzen Sie die `using`-Anweisungen im oberen Bereich durch Folgendes:

```csharp
using System;
using System.Linq;
using Microsoft.Azure.Management.Compute.Fluent;
using Microsoft.Azure.Management.Compute.Fluent.Models;
using Microsoft.Azure.Management.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.WindowsAzure.Storage;
using Microsoft.WindowsAzure.Storage.Blob;
using System.Data.SqlClient;
```

## <a name="create-a-virtual-machine"></a>Erstellen eines virtuellen Computers

In diesem Beispiel wird eine VM bereitgestellt. 

Ersetzen Sie die `Main`-Methode durch Folgendes.  Geben Sie für die VM unbedingt einen tatsächlichen `username` (Benutzernamen) samt `password` (Kennwort) an.

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string username = "MY_USERNAME";
    string password = "MY_PASSWORD";
    string rgName = "sampleResourceGroup";
    string windowsVmName = "sampleWindowsVM";
    string publicIpDnsLabel = "samplePublicIP";

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .WithLogLevel(HttpLoggingDelegatingHandler.Level.Basic)
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the VM
    Console.WriteLine("Creating VM...");
    var windowsVM = azure.VirtualMachines.Define(windowsVmName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .WithNewPrimaryNetwork("10.0.0.0/28")
        .WithPrimaryPrivateIPAddressDynamic()
        .WithNewPrimaryPublicIPAddress(publicIpDnsLabel)
        .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
        .WithAdminUsername(username)
        .WithAdminPassword(password)
        .WithSize(VirtualMachineSizeTypes.StandardD2V2)
        .Create();

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

Drücken Sie **F5**, um das Beispiel auszuführen.

Nach einigen Minuten wird das Programm beendet, und Sie werden aufgefordert, die EINGABETASTE zu drücken. Überprüfen Sie nach Drücken der EINGABETASTE die VM in Ihrem Abonnement mit PowerShell:

```powershell
Get-AzureRmVm -ResourceGroupName sampleResourceGroup
```

## <a name="deploy-a-web-app-from-a-github-repo"></a>Bereitstellen einer Web-App aus einem GitHub-Repository

Nun ändern Sie Ihren Code, um eine neue Web-App mithilfe eines vorhandenen GitHub-Repositorys zu erstellen und bereitzustellen. Ersetzen Sie die `Main`-Methode durch den folgenden Code:

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string rgName = "sampleResourceGroup";
    string appName = SdkContext.RandomResourceName("WebApp", 20);

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the web app
    Console.WriteLine("Creating Web App...");
    var app = azure.WebApps.Define(appName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .WithNewFreeAppServicePlan()
        .DefineSourceControl()
        .WithPublicGitRepository("https://github.com/Azure-Samples/app-service-web-dotnet-get-started")
        .WithBranch("master")
        .Attach()
        .Create();
    Console.WriteLine("Your web app is live at: https://{0}", app.HostNames.First());

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

Führen Sie den Code wie zuvor durch Drücken von **F5** aus.  Überprüfen Sie die Bereitstellung, indem Sie einen Browser öffnen und zur in der Konsole angezeigten URL navigieren.

## <a name="connect-to-a-sql-database"></a>Herstellen einer Verbindung mit einer SQL-Datenbank-Instanz

In diesem Beispiel wird eine neue Azure SQL-Datenbank-Instanz erstellt, in der einige SQL-Vorgänge erfolgen.

Ersetzen Sie die `Main`-Methode durch Folgendes, und weisen Sie für `dbPassword` unbedingt ein sicheres Kennwort zu:

```csharp
 static void Main(string[] args)
{
    // Set some variables...
    string rgName = "sampleResourceGroup";
    string adminUser = SdkContext.RandomResourceName("db", 8);
    string sqlServerName = SdkContext.RandomResourceName("sql", 10);
    string sqlDbName = SdkContext.RandomResourceName("dbname", 8);
    string dbPassword = "YOUR_PASSWORD_HERE";

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the SQL server and database
    Console.WriteLine("Creating server...");
    var sqlServer = azure.SqlServers.Define(sqlServerName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .WithAdministratorLogin(adminUser)
        .WithAdministratorPassword(dbPassword)
        .WithNewFirewallRule("0.0.0.0", "255.255.255.255")
        .Create();

    Console.WriteLine("Creating database...");
    var sqlDb = sqlServer.Databases.Define(sqlDbName).Create();

    // Display information for connecting later...
    Console.WriteLine("Created database {0} in server {1}.", sqlDbName, sqlServer.FullyQualifiedDomainName);
    Console.WriteLine("Your user name is {0}.", adminUser + "@" + sqlServer.Name);

    // Build the connection string
    var builder = new SqlConnectionStringBuilder();
    builder.DataSource = sqlServer.FullyQualifiedDomainName;
    builder.InitialCatalog = sqlDbName;
    builder.UserID = adminUser + "@" + sqlServer.Name; // Format user ID as "user@server"
    builder.Password = dbPassword;
    builder.Encrypt = true;
    builder.TrustServerCertificate = true;

    // connect to the database, create a table and insert an entry into it
    using (var conn = new SqlConnection(builder.ConnectionString))
    {
        conn.Open();

        Console.WriteLine("Populating database...");
        var createCommand = new SqlCommand("CREATE TABLE CLOUD (name varchar(255), code int);", conn);
        createCommand.ExecuteNonQuery();

        var insertCommand = new SqlCommand("INSERT INTO CLOUD (name, code ) VALUES ('Azure', 1);", conn);
        insertCommand.ExecuteNonQuery();

        Console.WriteLine("Reading from database...");
        var selectCommand = new SqlCommand("SELECT * FROM CLOUD", conn);
        var results = selectCommand.ExecuteReader();
        while(results.Read())
        {
            Console.WriteLine("Name: {0} Code: {1}", results[0], results[1]);
        }
    }

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

Führen Sie den Code wie zuvor durch Drücken von **F5** aus.  Die Konsolenausgabe sollte bestätigen, dass der Server erstellt wurde und erwartungsgemäß funktioniert. Doch Sie können auch nach Wunsch mit einem Tool wie SQL Server Management Studio eine direkte Verbindung damit herstellen.

## <a name="write-a-blob-into-a-new-storage-account"></a>Schreiben eines Blobs in ein neues Speicherkonto

In diesem Beispiel wird ein Speicherkonto erstellt und ein Blob hochgeladen.  

Ersetzen Sie die `Main`-Methode durch Folgendes.

```csharp
static void Main(string[] args)
{
    // Set some variables...
    string rgName = "sampleResourceGroup";
    string storageAccountName = SdkContext.RandomResourceName("st", 10);

    // Authenticate
    var credentials = SdkContext.AzureCredentialsFactory
        .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

    var azure = Azure
        .Configure()
        .Authenticate(credentials)
        .WithDefaultSubscription();

    // Create the storage account
    Console.WriteLine("Creating storage account...");
    var storage = azure.StorageAccounts.Define(storageAccountName)
        .WithRegion(Region.USEast)
        .WithNewResourceGroup(rgName)
        .Create();

    var storageKeys = storage.GetKeys();
    string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storage.Name
        + ";AccountKey=" + storageKeys[0].Value
        + ";EndpointSuffix=core.windows.net";

    var account = CloudStorageAccount.Parse(storageConnectionString);
    var serviceClient = account.CreateCloudBlobClient();

    // Create container. Name must be lower case.
    Console.WriteLine("Creating container...");
    var container = serviceClient.GetContainerReference("helloazure");
    container.CreateIfNotExistsAsync().Wait();

    // Make the container public
    var containerPermissions = new BlobContainerPermissions()
        { PublicAccess = BlobContainerPublicAccessType.Container };
    container.SetPermissionsAsync(containerPermissions).Wait();

    // write a blob to the container
    Console.WriteLine("Uploading blob...");
    var blob = container.GetBlockBlobReference("helloazure.txt");
    blob.UploadTextAsync("Hello, Azure!").Wait();
    Console.WriteLine("Your blob is located at {0}", blob.StorageUri.PrimaryUri);

    // Wait for the user
    Console.WriteLine("Press enter to continue...");
    Console.ReadLine();
}
```

Drücken Sie **F5**, um das Beispiel auszuführen.

Nach einigen Minuten wird das Programm beendet. Vergewissern Sie sich, dass das Blob hochgeladen wurde, indem Sie zur in der Konsole angezeigten URL wechseln.  Der Text „Hello, Azure!“ sollte in Ihrem Browser angezeigt werden.

## <a name="clean-up"></a>Bereinigen

> [!IMPORTANT]
> Wenn Sie die in diesem Tutorial verwendeten Ressourcen nicht bereinigen, werden Sie Ihnen weiter in Rechnung gestellt.  Versäumen Sie deshalb diesen Schritt nicht.

Löschen Sie alle Ressourcen, die Sie erstellt haben, durch folgende Eingabe in PowerShell:

```powershell
Remove-AzureRmResourceGroup -ResourceGroupName sampleResourceGroup
```

## <a name="explore-more-samples"></a>Erkunden weiterer Beispiele

Weitere Informationen zur Ressourcenverwaltung und Aufgabenautomatisierung mit den Azure-Bibliotheken für .NET finden Sie in unserem Beispielcode für [virtuelle Computer](dotnet-sdk-azure-virtual-machine-samples.md), [Web-Apps](dotnet-sdk-azure-web-apps-samples.md) und [SQL-Datenbank](dotnet-sdk-azure-sql-database-samples.md).

## <a name="reference"></a>Verweis

Für alle Pakete steht eine [Referenz](http://docs.microsoft.com/dotnet/api) zur Verfügung.

[!include[Contribute and community](includes/contribute.md)]
