---
title: Erste Schritte mit Azure .NET-APIs
description: Machen Sie sich mit der grundlegenden Verwendung der Azure-Bibliotheken für .NET mit Ihrem eigenen Azure-Abonnement vertraut.
keywords: Azure, .NET, SDK, API, authentifizieren, erste Schritte
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: a3733898f948dbb2ec07da20aa61724e07f23e73
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2018
ms.locfileid: "29752872"
---
# <a name="get-started-with-the-azure-net-apis"></a><span data-ttu-id="eb817-104">Erste Schritte mit den Azure .NET-APIs</span><span class="sxs-lookup"><span data-stu-id="eb817-104">Get started with the Azure .NET APIs</span></span>

<span data-ttu-id="eb817-105">Dieses Tutorial veranschaulicht die Verwendung mehrerer [Azure-APIs für .NET](/dotnet/api/overview/azure/).</span><span class="sxs-lookup"><span data-stu-id="eb817-105">This tutorial demonstrates the usage of several [Azure APIs for .NET](/dotnet/api/overview/azure/).</span></span>  <span data-ttu-id="eb817-106">Sie richten die Authentifizierung ein und erstellen und verwenden ein Azure Storage-Konto sowie eine Azure SQL-Datenbank-Instanz. Außerdem stellen Sie einige virtuelle Computer und eine Azure App Service-Web-App über GitHub bereit.</span><span class="sxs-lookup"><span data-stu-id="eb817-106">You will set up authentication, create and use an Azure Storage account, create and use an Azure SQL Database, deploy some virtual machines, and deploy an Azure App Service Web App from GitHub.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="eb817-107">Voraussetzungen</span><span class="sxs-lookup"><span data-stu-id="eb817-107">Prerequisites</span></span>

- <span data-ttu-id="eb817-108">Ein Azure-Konto.</span><span class="sxs-lookup"><span data-stu-id="eb817-108">An Azure account.</span></span> <span data-ttu-id="eb817-109">Falls Sie noch kein Konto haben, können Sie eine [kostenlose Testversion](https://azure.microsoft.com/free/) verwenden.</span><span class="sxs-lookup"><span data-stu-id="eb817-109">If you don't have one, [get a free trial](https://azure.microsoft.com/free/)</span></span>
- [<span data-ttu-id="eb817-110">Azure PowerShell</span><span class="sxs-lookup"><span data-stu-id="eb817-110">Azure PowerShell</span></span>](/powershell/azure/install-azurerm-ps)

## <a name="set-up-authentication"></a><span data-ttu-id="eb817-111">Einrichten der Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="eb817-111">Set up authentication</span></span>

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="create-a-new-project"></a><span data-ttu-id="eb817-112">Erstellen eines neuen Projekts</span><span class="sxs-lookup"><span data-stu-id="eb817-112">Create a new project</span></span> 

<span data-ttu-id="eb817-113">Erstellen Sie ein neues Konsolenanwendungsprojekt.</span><span class="sxs-lookup"><span data-stu-id="eb817-113">Create a new console application project.</span></span>  <span data-ttu-id="eb817-114">Klicken Sie dazu in Visual Studio auf **Datei** -> **Neu** und dann auf **Projekt...**.  Wählen Sie unter „Visual C#-Vorlagen“ **Konsolen-App (.NET Core)** aus. Benennen Sie das Projekt, und klicken Sie dann auf **OK**.</span><span class="sxs-lookup"><span data-stu-id="eb817-114">In Visual Studio, do this by clicking **File**, **New**, and then clicking **Project...**.  Under the Visual C# templates, select **Console App (.NET Core)**, name your project, and then click **OK**.</span></span>

![Dialogfeld „Neues Projekt“](media/dotnet-sdk-azure-get-started/new-project.png)

<span data-ttu-id="eb817-116">Nachdem die neue Konsolen-App erstellt wurde, öffnen Sie die Paket-Manager-Konsole, indem Sie auf **Extras** -> **NuGet-Paket-Manager** und dann auf **Paket-Manager-Konsole** klicken.</span><span class="sxs-lookup"><span data-stu-id="eb817-116">When the new console app is created, open the Package Manager Console by clicking **Tools**, **NuGet Package Manager**, and then click **Package Manager Console**.</span></span>  <span data-ttu-id="eb817-117">Rufen Sie in der Konsole die benötigten Pakete ab, indem Sie die folgenden drei Befehle ausführen:</span><span class="sxs-lookup"><span data-stu-id="eb817-117">In the console, get the packages you'll need by executing the following three commands:</span></span>

```powershell
# Azure Management Libraries for .NET (Fluent)
Install-Package Microsoft.Azure.Management.Fluent

# Azure Store client libraries
Install-Package WindowsAzure.Storage

# SQL Database client libraries
Install-Package System.Data.SqlClient
```

## <a name="directives"></a><span data-ttu-id="eb817-118">Anweisungen</span><span class="sxs-lookup"><span data-stu-id="eb817-118">Directives</span></span>

<span data-ttu-id="eb817-119">Bearbeiten Sie die Datei `Program.cs` Ihrer Anwendung.</span><span class="sxs-lookup"><span data-stu-id="eb817-119">Edit your application's `Program.cs` file.</span></span>  <span data-ttu-id="eb817-120">Ersetzen Sie die `using`-Anweisungen im oberen Bereich durch Folgendes:</span><span class="sxs-lookup"><span data-stu-id="eb817-120">Replace the `using` directives at the top with the following:</span></span>

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

## <a name="create-a-virtual-machine"></a><span data-ttu-id="eb817-121">Erstellen eines virtuellen Computers</span><span class="sxs-lookup"><span data-stu-id="eb817-121">Create a virtual machine</span></span>

<span data-ttu-id="eb817-122">In diesem Beispiel wird eine VM bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="eb817-122">This example deploys a virtual machine.</span></span> 

<span data-ttu-id="eb817-123">Ersetzen Sie die `Main`-Methode durch Folgendes.</span><span class="sxs-lookup"><span data-stu-id="eb817-123">Replace the `Main` method with the following.</span></span>  <span data-ttu-id="eb817-124">Geben Sie für die VM unbedingt einen tatsächlichen `username` (Benutzernamen) samt `password` (Kennwort) an.</span><span class="sxs-lookup"><span data-stu-id="eb817-124">Be sure to provide an actual `username` and `password` for the virtual machine.</span></span>

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

<span data-ttu-id="eb817-125">Drücken Sie **F5**, um das Beispiel auszuführen.</span><span class="sxs-lookup"><span data-stu-id="eb817-125">Press **F5** to run the sample.</span></span>

<span data-ttu-id="eb817-126">Nach einigen Minuten wird das Programm beendet, und Sie werden aufgefordert, die EINGABETASTE zu drücken.</span><span class="sxs-lookup"><span data-stu-id="eb817-126">After several minutes, the program will finish, prompting you to press enter.</span></span> <span data-ttu-id="eb817-127">Überprüfen Sie nach Drücken der EINGABETASTE die VM in Ihrem Abonnement mit PowerShell:</span><span class="sxs-lookup"><span data-stu-id="eb817-127">After pressing enter, verify the virtual machine in your subscription with PowerShell:</span></span>

```powershell
Get-AzureRmVm -ResourceGroupName sampleResourceGroup
```

## <a name="deploy-a-web-app-from-a-github-repo"></a><span data-ttu-id="eb817-128">Bereitstellen einer Web-App aus einem GitHub-Repository</span><span class="sxs-lookup"><span data-stu-id="eb817-128">Deploy a web app from a GitHub repo</span></span>

<span data-ttu-id="eb817-129">Nun ändern Sie Ihren Code, um eine neue Web-App mithilfe eines vorhandenen GitHub-Repositorys zu erstellen und bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="eb817-129">Now you'll modify your code to create a deploy a new web app from an existing GitHub repository.</span></span> <span data-ttu-id="eb817-130">Ersetzen Sie die `Main`-Methode durch den folgenden Code:</span><span class="sxs-lookup"><span data-stu-id="eb817-130">Replace the `Main` method with the following code:</span></span>

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

<span data-ttu-id="eb817-131">Führen Sie den Code wie zuvor durch Drücken von **F5** aus.</span><span class="sxs-lookup"><span data-stu-id="eb817-131">Run the code as before by pressing **F5**.</span></span>  <span data-ttu-id="eb817-132">Überprüfen Sie die Bereitstellung, indem Sie einen Browser öffnen und zur in der Konsole angezeigten URL navigieren.</span><span class="sxs-lookup"><span data-stu-id="eb817-132">Verify the deployment by opening a browser and navigating to URL displayed in the console.</span></span>

## <a name="connect-to-a-sql-database"></a><span data-ttu-id="eb817-133">Herstellen einer Verbindung mit einer SQL-Datenbank-Instanz</span><span class="sxs-lookup"><span data-stu-id="eb817-133">Connect to a SQL database</span></span>

<span data-ttu-id="eb817-134">In diesem Beispiel wird eine neue Azure SQL-Datenbank-Instanz erstellt, in der einige SQL-Vorgänge erfolgen.</span><span class="sxs-lookup"><span data-stu-id="eb817-134">This example creates a new Azure SQL Database and performs a few SQL operations.</span></span>

<span data-ttu-id="eb817-135">Ersetzen Sie die `Main`-Methode durch Folgendes, und weisen Sie für `dbPassword` unbedingt ein sicheres Kennwort zu:</span><span class="sxs-lookup"><span data-stu-id="eb817-135">Replace the `Main` method with the following, making sure to assign a strong password for `dbPassword`:</span></span>

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
<span data-ttu-id="eb817-136">Führen Sie den Code wie zuvor durch Drücken von **F5** aus.</span><span class="sxs-lookup"><span data-stu-id="eb817-136">Run the code as before by pressing **F5**.</span></span>  <span data-ttu-id="eb817-137">Die Konsolenausgabe sollte bestätigen, dass der Server erstellt wurde und erwartungsgemäß funktioniert. Doch Sie können auch nach Wunsch mit einem Tool wie SQL Server Management Studio eine direkte Verbindung damit herstellen.</span><span class="sxs-lookup"><span data-stu-id="eb817-137">The console output should validate that the server was created and works as expected, but you can connect to it directly with a tool like SQL Server Management Studio if you like.</span></span>

## <a name="write-a-blob-into-a-new-storage-account"></a><span data-ttu-id="eb817-138">Schreiben eines Blobs in ein neues Speicherkonto</span><span class="sxs-lookup"><span data-stu-id="eb817-138">Write a blob into a new storage account</span></span>

<span data-ttu-id="eb817-139">In diesem Beispiel wird ein Speicherkonto erstellt und ein Blob hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="eb817-139">This example will create a storage account and upload a blob.</span></span>  

<span data-ttu-id="eb817-140">Ersetzen Sie die `Main`-Methode durch Folgendes.</span><span class="sxs-lookup"><span data-stu-id="eb817-140">Replace the `Main` method with the following.</span></span>

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

<span data-ttu-id="eb817-141">Drücken Sie **F5**, um das Beispiel auszuführen.</span><span class="sxs-lookup"><span data-stu-id="eb817-141">Press **F5** to run the sample.</span></span>

<span data-ttu-id="eb817-142">Nach einigen Minuten wird das Programm beendet.</span><span class="sxs-lookup"><span data-stu-id="eb817-142">After several minutes, the program will finish.</span></span> <span data-ttu-id="eb817-143">Vergewissern Sie sich, dass das Blob hochgeladen wurde, indem Sie zur in der Konsole angezeigten URL wechseln.</span><span class="sxs-lookup"><span data-stu-id="eb817-143">Verify the blob was uploaded by browsing to the URL displayed in the console.</span></span>  <span data-ttu-id="eb817-144">Der Text „Hello, Azure!“ sollte</span><span class="sxs-lookup"><span data-stu-id="eb817-144">You should see the text "Hello, Azure!"</span></span> <span data-ttu-id="eb817-145">in Ihrem Browser angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="eb817-145">in your browser.</span></span>

## <a name="clean-up"></a><span data-ttu-id="eb817-146">Bereinigen</span><span class="sxs-lookup"><span data-stu-id="eb817-146">Clean up</span></span>

> [!IMPORTANT]
> <span data-ttu-id="eb817-147">Wenn Sie die in diesem Tutorial verwendeten Ressourcen nicht bereinigen, werden Sie Ihnen weiter in Rechnung gestellt.</span><span class="sxs-lookup"><span data-stu-id="eb817-147">If you don't clean up your resources from this tutorial, you will continue to be charged for them.</span></span>  <span data-ttu-id="eb817-148">Versäumen Sie deshalb diesen Schritt nicht.</span><span class="sxs-lookup"><span data-stu-id="eb817-148">Be sure to do this step.</span></span>

<span data-ttu-id="eb817-149">Löschen Sie alle Ressourcen, die Sie erstellt haben, durch folgende Eingabe in PowerShell:</span><span class="sxs-lookup"><span data-stu-id="eb817-149">Delete all the resources you created by entering the following in PowerShell:</span></span>

```powershell
Remove-AzureRmResourceGroup -ResourceGroupName sampleResourceGroup
```
## <a name="explore-more-samples"></a><span data-ttu-id="eb817-150">Erkunden weiterer Beispiele</span><span class="sxs-lookup"><span data-stu-id="eb817-150">Explore more samples</span></span>

<span data-ttu-id="eb817-151">Weitere Informationen zur Ressourcenverwaltung und Aufgabenautomatisierung mit den Azure-Bibliotheken für .NET finden Sie in unserem Beispielcode für [virtuelle Computer](dotnet-sdk-azure-virtual-machine-samples.md), [Web-Apps](dotnet-sdk-azure-web-apps-samples.md) und [SQL-Datenbank](dotnet-sdk-azure-sql-database-samples.md).</span><span class="sxs-lookup"><span data-stu-id="eb817-151">To learn more about how to use the Azure libraries for .NET to manage resources and automate tasks, see our sample code for [virtual machines](dotnet-sdk-azure-virtual-machine-samples.md), [web apps](dotnet-sdk-azure-web-apps-samples.md) and [SQL database](dotnet-sdk-azure-sql-database-samples.md).</span></span>

## <a name="reference"></a><span data-ttu-id="eb817-152">Verweis</span><span class="sxs-lookup"><span data-stu-id="eb817-152">Reference</span></span>

<span data-ttu-id="eb817-153">Für alle Pakete steht eine [Referenz](http://docs.microsoft.com/dotnet/api) zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="eb817-153">A [reference](http://docs.microsoft.com/dotnet/api) is available for all packages.</span></span>

[!include[Contribute and community](includes/contribute.md)]
