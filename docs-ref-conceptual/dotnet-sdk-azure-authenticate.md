---
title: Authentifizieren bei den Azure-Bibliotheken für .NET
description: Authentifizieren bei den Azure-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Authentifizierung, Active Directory, Dienstprinzipal
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 783b5ebf14abad992c18726df7232e4f3a68b72b
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2018
ms.locfileid: "29752772"
---
# <a name="authenticate-with-the-azure-libraries-for-net"></a>Authentifizieren bei den Azure-Bibliotheken für .NET

## <a name="connect-to-services-with-connection-strings"></a>Herstellen einer Verbindung mit Diensten mit Verbindungszeichenfolgen

Die meisten Azure-Dienstbibliotheken fordern für die Authentifizierung eine Verbindungszeichenfolge oder einen Schlüssel an. SQL-Datenbank verwendet beispielsweise eine standardmäßige SQL-Verbindungszeichenfolge:

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

Azure Storage verlangt einen Speicherschlüssel:

```csharp
string storageConnectionString = "DefaultEndpointsProtocol=https;"
        + "AccountName=" + storageName
        + ";AccountKey=" + storageKey
        + ";EndpointSuffix=core.windows.net";

var account = CloudStorageAccount.Parse(storageConnectionString);
// Do things with the account here...
```

Verbindungszeichenfolgen für Dienste werden in anderen Azure-Diensten wie [CosmosDB](/azure/documentdb/documentdb-dotnet-application#a-nametoc395637769astep-5-wiring-up-azure-cosmos-db), [Redis Cache](/azure/redis-cache/cache-dotnet-how-to-use-azure-redis-cache) und [Service Bus](/azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues) verwendet. Sie können diese Zeichenfolgen über das Azure-Portal, die CLI oder PowerShell abrufen.  Sie können auch die Azure-Verwaltungsbibliotheken für .NET zum Abfragen von Ressourcen verwenden, um Verbindungszeichenfolgen in Ihrem Code zu erstellen. 

Dieser Codeausschnitt verwendet beispielsweise die Verwaltungsbibliotheken, um eine Verbindungszeichenfolge für ein Speicherkonto zu erstellen:

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

Bei anderen Bibliotheken muss Ihre Anwendung mit einem [Dienstprinzipal](https://docs.microsoft.com/azure/active-directory/develop/active-directory-application-objects) ausgeführt werden, der die Ausführung der Anwendung mit erteilten Anmeldeinformationen autorisiert. Diese Konfiguration ist vergleichbar mit den objektbasierten Authentifizierungsschritten für die unten aufgeführte Verwaltungsbibliothek.

## <a name="mgmt-auth"></a>Azure-Verwaltungsbibliotheken für die .NET-Authentifizierung

[!include[Create service principal](includes/create-sp.md)]

Nachdem der Dienstprinzipal erstellt wurde, stehen zwei Optionen für die Authentifizierung beim Dienstprinzipal zur Verfügung, um Ressourcen zu erstellen und zu verwalten.

Bei beiden Optionen müssen Sie dem Projekt die folgenden NuGet-Pakete hinzufügen.

```
Install-Package Microsoft.Azure.Management.Fluent
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="authenticate-with-token-credentials"></a>Authentifizieren mit Zugriffstoken-Anmeldeinformationen

Die erste Methode sieht das Erstellen des tokenbasierten Anmeldeinformationsobjekts im Code vor.  Sie müssen die Anmeldeinformationen in einer Konfigurationsdatei, der Registrierung oder Azure Key Vault sicher speichern.

```csharp
var credentials = SdkContext.AzureCredentialsFactory
    .FromServicePrincipal(clientId,
    clientSecret,
    tenantId, 
    AzureEnvironment.AzureGlobalCloud);
```

- clientId: Verwenden Sie den Wert von *ApplicationId* aus der Dienstprinzipalausgabe.
- clientSecret: Verwenden Sie den Parameter *-Password* (ohne Anführungszeichen), den Sie bei Ausführung von `New-AzureRmADServicePrincipal` zugewiesen haben.
- tenantid: Verwenden Sie den Wert von *TenantId* nach der Ausführung von `Login-AzureRmAccount`.

Erstellen Sie dann das Einstiegspunktobjekt `Azure`, um mit der Verwendung der API zu beginnen:

```csharp
var azure = Microsoft.Azure.Management.Fluent.Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```

### <a name="mgmt-file"></a>Dateibasierte Authentifizierung

Die dateibasierte Authentifizierung ermöglicht Ihnen das Ablegen der Anmeldeinformationen für den Dienstprinzipal in einer einfachen Textdatei, die Sie im Dateisystem schützen.

[!include[File-based authentication](includes/file-based-auth.md)]

Lesen Sie den Inhalt der Datei, und erstellen Sie das Einstiegspunktobjekt `Azure`, um mit der Verwendung der API zu beginnen:

```csharp
// pull in the location of the authentication properties file from the environment 
var credentials = SdkContext.AzureCredentialsFactory
    .FromFile(Environment.GetEnvironmentVariable("AZURE_AUTH_LOCATION"));

var azure = Microsoft.Azure.Management.Fluent.Azure
    .Configure()
    .Authenticate(credentials)
    .WithDefaultSubscription();
```
