---
title: "Authentifizieren bei den Azure-Bibliotheken für .NET"
description: "Authentifizieren bei den Azure-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Authentifizierung, Active Directory, Dienstprinzipal
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: c9755d7e9c20186c7677b4bfe69d4033f9852607
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="authenticate-with-the-azure-libraries-for-net"></a><span data-ttu-id="7bcab-104">Authentifizieren bei den Azure-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="7bcab-104">Authenticate with the Azure Libraries for .NET</span></span>

## <a name="connect-to-services-with-connection-strings"></a><span data-ttu-id="7bcab-105">Herstellen einer Verbindung mit Diensten mit Verbindungszeichenfolgen</span><span class="sxs-lookup"><span data-stu-id="7bcab-105">Connect to services with connection strings</span></span>

<span data-ttu-id="7bcab-106">Die meisten Azure-Dienstbibliotheken fordern für die Authentifizierung eine Verbindungszeichenfolge oder einen Schlüssel an.</span><span class="sxs-lookup"><span data-stu-id="7bcab-106">Most Azure service libraries require a connection string or keys for authentication.</span></span> <span data-ttu-id="7bcab-107">SQL-Datenbank verwendet beispielsweise eine standardmäßige SQL-Verbindungszeichenfolge:</span><span class="sxs-lookup"><span data-stu-id="7bcab-107">For example, SQL Database uses a standard SQL connection string:</span></span>

```csharp
var builder = new SqlConnectionStringBuilder();
builder.DataSource = "example.database.windows.net";
builder.InitialCatalog = "MyDatabase";
builder.UserID = "sampleuser@example"; // Format user ID as "user@server"
builder.Password = password;
builder.Encrypt = true;
builder.TrustServerCertificate = true;
                
using (var conn = new SqlConnection(builder.ConnectionString))
{
    conn.Open();
    // Do things with the connection...
    // ...
}
```

<span data-ttu-id="7bcab-108">Azure Storage verlangt einen Speicherschlüssel:</span><span class="sxs-lookup"><span data-stu-id="7bcab-108">Azure Storage uses a storage key:</span></span>

```csharp
string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storageName
        + ";AccountKey=" + storageKey
        + ";EndpointSuffix=core.windows.net";

var account = CloudStorageAccount.Parse(storageConnectionString);
// Do things with the account here...
```

<span data-ttu-id="7bcab-109">Verbindungszeichenfolgen für Dienste werden in anderen Azure-Diensten wie [CosmosDB](/azure/documentdb/documentdb-dotnet-application#a-nametoc395637769astep-5-wiring-up-azure-cosmos-db), [Redis Cache](/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache) und [Service Bus](/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues) verwendet. Sie können diese Zeichenfolgen über das Azure-Portal, die CLI oder PowerShell abrufen.</span><span class="sxs-lookup"><span data-stu-id="7bcab-109">Service connection strings are used in other Azure services like [CosmosDB](/azure/documentdb/documentdb-dotnet-application#a-nametoc395637769astep-5-wiring-up-azure-cosmos-db), [Redis Cache](/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache), and [Service Bus](/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues) and you can get those strings using the Azure portal, CLI, or PowerShell.</span></span>  <span data-ttu-id="7bcab-110">Sie können auch die Azure-Verwaltungsbibliotheken für .NET zum Abfragen von Ressourcen verwenden, um Verbindungszeichenfolgen in Ihrem Code zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="7bcab-110">You can also use the Azure management libraries for .NET to query resources to build connection strings in your code.</span></span> 

<span data-ttu-id="7bcab-111">Dieser Codeausschnitt verwendet beispielsweise die Verwaltungsbibliotheken, um eine Verbindungszeichenfolge für ein Speicherkonto zu erstellen:</span><span class="sxs-lookup"><span data-stu-id="7bcab-111">This snippet uses the management libraries to create a storage account connection string:</span></span>

```csharp
// Get a storage account
var storage = azure.StorageAccounts.GetByResourceGroup("myResourceGroup", "myStorageAccount");

// Extract the keys
var storageKeys = storage.GetKeys();

// Build the connection string
string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storage.Name
        + ";AccountKey=" + storageKeys[0].Value
        + ";EndpointSuffix=core.windows.net";

// Connect
var account = CloudStorageAccount.Parse(storageConnectionString);

// Do things with the account here...
```

<span data-ttu-id="7bcab-112">Bei anderen Bibliotheken muss Ihre Anwendung mit einem [Dienstprinzipal](https://docs.microsoft.com/azure/active-directory/develop/active-directory-application-objects) ausgeführt werden, der die Ausführung der Anwendung mit erteilten Anmeldeinformationen autorisiert.</span><span class="sxs-lookup"><span data-stu-id="7bcab-112">Other libraries require your application to run with a [service principal](https://docs.microsoft.com/azure/active-directory/develop/active-directory-application-objects) authorizing the application to run with granted credentials.</span></span> <span data-ttu-id="7bcab-113">Diese Konfiguration ist vergleichbar mit den objektbasierten Authentifizierungsschritten für die unten aufgeführte Verwaltungsbibliothek.</span><span class="sxs-lookup"><span data-stu-id="7bcab-113">This configuration is similar to the object-based authentication steps for the management library listed below.</span></span>

## <span data-ttu-id="7bcab-114"><a name="mgmt-auth"></a>Azure-Verwaltungsbibliotheken für die .NET-Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="7bcab-114"><a name="mgmt-auth"></a>Azure management libraries for .NET authentication</span></span>

[!include[Create service principal](includes/create-sp.md)]

<span data-ttu-id="7bcab-115">Nachdem der Dienstprinzipal erstellt wurde, stehen zwei Optionen für die Authentifizierung beim Dienstprinzipal zur Verfügung, um Ressourcen zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="7bcab-115">Now that the service principal is created, two options are available to authenticate to the service principal to create and manage resources.</span></span>

<span data-ttu-id="7bcab-116">Bei beiden Optionen müssen Sie dem Projekt die folgenden NuGet-Pakete hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="7bcab-116">For both options you will need to add the following nuget packages to your project.</span></span>

```
Install-Package Microsoft.Azure.Management.Fluent
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="authenticate-with-token-credentials"></a><span data-ttu-id="7bcab-117">Authentifizieren mit Zugriffstoken-Anmeldeinformationen</span><span class="sxs-lookup"><span data-stu-id="7bcab-117">Authenticate with token credentials</span></span>

<span data-ttu-id="7bcab-118">Die erste Methode sieht das Erstellen des tokenbasierten Anmeldeinformationsobjekts im Code vor.</span><span class="sxs-lookup"><span data-stu-id="7bcab-118">The first method is to build the token credential object in code.</span></span>  <span data-ttu-id="7bcab-119">Sie müssen die Anmeldeinformationen in einer Konfigurationsdatei, der Registrierung oder Azure Key Vault sicher speichern.</span><span class="sxs-lookup"><span data-stu-id="7bcab-119">You should store the credentials securely in a configuration file, the registry, or Azure KeyVault.</span></span>

```csharp
var credentials = SdkContext.AzureCredentialsFactory
    .FromServicePrincipal(clientId,
    clientSecret,
    tenantId, 
    AzureEnvironment.AzureGlobalCloud);
```

- <span data-ttu-id="7bcab-120">clientId: Verwenden Sie den Wert von *ApplicationId* aus der Dienstprinzipalausgabe.</span><span class="sxs-lookup"><span data-stu-id="7bcab-120">clientId: use the *ApplicationId* value from the service principal output.</span></span>
- <span data-ttu-id="7bcab-121">clientSecret: Verwenden Sie den Parameter *-Password* (ohne Anführungszeichen), den Sie bei Ausführung von `New-AzureRmADServicePrincipal` zugewiesen haben.</span><span class="sxs-lookup"><span data-stu-id="7bcab-121">clientSecret: use the *-Password* parameter you assigned when you ran `New-AzureRmADServicePrincipal` (without quotes).</span></span>
- <span data-ttu-id="7bcab-122">tenantid: Verwenden Sie den Wert von *TenantId* nach der Ausführung von `Login-AzureRmAccount`.</span><span class="sxs-lookup"><span data-stu-id="7bcab-122">tenantId: use the *TenantId* value from when you ran `Login-AzureRmAccount`.</span></span>

<span data-ttu-id="7bcab-123">Erstellen Sie dann das Einstiegspunktobjekt `Azure`, um mit der Verwendung der API zu beginnen:</span><span class="sxs-lookup"><span data-stu-id="7bcab-123">Then create the entry point `Azure` object to start working with the API:</span></span>

```csharp
var azure = Microsoft.Azure.Management.Fluent.Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

### <span data-ttu-id="7bcab-124"><a name="mgmt-file"></a>Dateibasierte Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="7bcab-124"><a name="mgmt-file"></a>File-based authentication</span></span>

<span data-ttu-id="7bcab-125">Die dateibasierte Authentifizierung ermöglicht Ihnen das Ablegen der Anmeldeinformationen für den Dienstprinzipal in einer einfachen Textdatei, die Sie im Dateisystem schützen.</span><span class="sxs-lookup"><span data-stu-id="7bcab-125">File-based authentication allows you to put the service principal credentials in a plain text file and secure it within the file system.</span></span>

[!include[File-based authentication](includes/file-based-auth.md)]

<span data-ttu-id="7bcab-126">Lesen Sie den Inhalt der Datei, und erstellen Sie das Einstiegspunktobjekt `Azure`, um mit der Verwendung der API zu beginnen:</span><span class="sxs-lookup"><span data-stu-id="7bcab-126">Read the contents of the file and create the entry point `Azure` object to start working with the API:</span></span>

```csharp
// pull in the location of the authentication properties file from the environment 
var credentials = SdkContext.AzureCredentialsFactory
    .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

var azure = Microsoft.Azure.Management.Fluent.Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```
