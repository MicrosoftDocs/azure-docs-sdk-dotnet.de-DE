---
title: Bereitstellen in Azure über die Befehlszeile mit .NET Core
description: In diesem Artikel wird beschrieben, wie Sie eine ASP.NET Core-Anwendung mithilfe von Befehlszeilentools in einer Azure App Service-Instanz bereitstellen.
keywords: Azure .NET, SDK, Azure .NET-API-Referenz, Azure .NET-Klassenbibliothek
author: camsoper
manager: douge
ms.author: casoper
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.openlocfilehash: 8371c304681ff88cba6f1cc3ba0d1caef836d609
ms.sourcegitcommit: e1a0e91988bb849c75e9583a80e3e6d712083785
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/14/2018
ms.locfileid: "31005877"
---
# <a name="deploy-to-azure-from-the-command-line-with-net-core"></a>Bereitstellen in Azure über die Befehlszeile mit .NET Core

Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von .NET Core.  Am Ende verfügen Sie über eine webbasierte, in ASP.NET MVC Core erstellte Aufgabenanwendung, die als Azure-Web-App gehostet wird und Azure Cosmos DB zur Datenspeicherung nutzt.

## <a name="prerequisites"></a>Voraussetzungen

* Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)
* [.NET Core](https://www.microsoft.com/net/download/core) (optional)
* [Azure CLI 2.0](/cli/azure/install-az-cli2) (optional)
* [Git](https://www.git-scm.com/)-Befehlszeilenclient (optional)

In der [Azure Cloud Shell](/azure/cloud-shell/) sind alle optionalen Voraussetzungen für dieses Tutorial vorinstalliert.  Sie müssen die oben aufgeführten optionalen Komponenten nur installieren, wenn Sie das Tutorial lokal ausführen möchten.  Um die Cloud Shell schnell zu starten, klicken Sie einfach in einem der folgenden Codeblöcke rechts oben auf die Schaltfläche **Ausprobieren**.

## <a name="create-an-azure-cosmos-db-account"></a>Erstellen eines Azure Cosmos DB-Kontos

Da in diesem Tutorial Azure Cosmos DB als Datenspeicher verwendet wird, muss ein Konto erstellt werden.  Führen Sie dieses Skript lokal oder in der Cloud Shell aus, um ein Azure Cosmos DB-Konto für die SQL-API zu erstellen.

```azurecli-interactive
# Create the DotNetAzureTutorial resource group
az group create --name DotNetAzureTutorial --location EastUS

# Generate a unique name for the account
let randomNum=$RANDOM*$RANDOM
cosmosdbname=dotnettutorial$randomNum

# Create the Azure Cosmos DB account
az cosmosdb create --name $cosmosdbname --resource-group DotNetAzureTutorial

# Retrieve the endpoint and key (you'll need these later)
cosmosEndpoint=$(az cosmosdb show -n $cosmosdbname -g DotNetAzureTutorial --query [documentEndpoint] -o tsv)
cosmosAuthKey=$(az cosmosdb list-keys -n $cosmosdbname -g DotNetAzureTutorial --query [primaryMasterKey] -o tsv)

```

## <a name="download-and-configure-the-application"></a>Herunterladen und Konfigurieren der Anwendung

Die Anwendung, die Sie bereitstellen, ist eine [einfache App](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/), die in ASP.NET MVC Core geschrieben wird und Azure Cosmos DB-Clientbibliotheken verwendet.  Im nächsten Schritt rufen Sie den Code für dieses Tutorial ab und konfigurieren ihn mit Ihren Azure Cosmos DB-Informationen.

```azurecli-interactive
# Get the code from GitHub
git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart

# Change the working directory
cd dotnet-cosmosdb-quickstart

# Replace authKey and endpoint values in appsettings.json
sed -i "s|AUTHKEYVALUE|$cosmosAuthKey|g" appsettings.json
sed -i "s|ENDPOINTVALUE|$cosmosEndpoint|g" appsettings.json

# Now commit your changes to the local Git repository.
git commit -a -m "Modified settings"

```

> [!NOTE]
> Wenn Sie `git commit` noch nicht zuvor in dieser Umgebung ausgeführt haben, werden Sie ggf. aufgefordert, Ihre Identität festzulegen. Führen Sie die Anweisungen auf dem Bildschirm und dann den Befehl `git commit` erneut aus.

Stellen Sie die NuGet-Pakete wieder her, und erstellen Sie die Anwendung.

```azurecli-interactive
dotnet restore
dotnet build
```

> [!TIP]
> Wenn Sie die Tools auf Ihrem eigenen Computer verwenden, können Sie die Anwendung testen, indem Sie `dotnet run` ausführen und zur angezeigten Adresse von `localhost` navigieren.  In der Cloud Shell können Sie allerdings nicht zu dieser Adresse navigieren.  

## <a name="configure-azure-app-service-and-deploy-the-web-app"></a>Konfigurieren von Azure App Service und Bereitstellen der Web-App

Sie haben die Webanwendung erfolgreich heruntergeladen und erstellt, die Sie nun als Azure-Web-App bereitstellen können.  Sie beginnen mit dem Erstellen einer Web-App-Ressource.

```azurecli-interactive
# Generate a unique Web App name
let randomNum=$RANDOM*$RANDOM
webappname=todoApp$randomNum

# Create an App Service plan.
az appservice plan create --name $webappname --resource-group DotNetAzureTutorial --sku FREE

# Create the Web App
az webapp create --name $webappname --resource-group DotNetAzureTutorial --plan $webappname

```

Vor der Bereitstellung müssen Sie die Anmeldeinformationen für die Bereitstellung auf Kontoebene festlegen.  Verwenden Sie das folgende Skript, und fügen Sie Ihre eigenen Werte für den Benutzernamen und das Kennwort ein.

```azurecli-interactive
az webapp deployment user set --user-name <desired user name> --password <desired password>
```

Stellen Sie schließlich die Anwendung in Azure bereit.  Sie werden aufgefordert, das zuvor erstellte Kennwort einzugeben.

```azurecli-interactive
# Get the Git deployment URL
giturl=$(az webapp deployment source config-local-git -n $webappname -g DotNetAzureTutorial --query [url] -o tsv)

# Add the URL as a Git remote repository
git remote add azure $giturl

# Push the local repository to the remote
git push azure master
```

Die Anwendung wird remote erstellt und bereitgestellt.  Testen Sie die Anwendung, indem Sie zu `https://<web app name>.azurewebsites.net` wechseln.  Um die Adresse in der Konsole anzuzeigen, verwenden Sie Folgendes:

```azurecli-interactive
az webapp show -n $webappname -g DotNetAzureTutorial --query defaultHostName -o tsv
```

Sie können der Aufgabenliste neue Elemente hinzufügen, indem Sie auf **Neu erstellen** klicken.

![Die fertige App](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a>Bereinigen

Wenn Sie die App getestet und sich mit dem Code und den Ressourcen vertraut gemacht haben, können Sie die Web-App und das Azure Cosmos DB-Konto löschen, indem Sie die Ressourcengruppe löschen.

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a>Nächste Schritte

* [An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [Erstellen einer Azure-Web-App mithilfe von Azure SQL-Datenbank](/azure/app-service-web/web-sites-dotnet-get-started)
* [Testen einer .NET-Beispielanwendung mit Azure Storage](/azure/storage/storage-samples-dotnet)


