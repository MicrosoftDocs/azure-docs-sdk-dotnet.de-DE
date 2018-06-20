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
# <a name="deploy-to-azure-from-the-command-line-with-net-core"></a><span data-ttu-id="81115-104">Bereitstellen in Azure über die Befehlszeile mit .NET Core</span><span class="sxs-lookup"><span data-stu-id="81115-104">Deploy to Azure from the command line with .NET Core</span></span>

<span data-ttu-id="81115-105">Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von .NET Core.</span><span class="sxs-lookup"><span data-stu-id="81115-105">This tutorial will walk you through building and deploying a Microsoft Azure application using .NET Core.</span></span>  <span data-ttu-id="81115-106">Am Ende verfügen Sie über eine webbasierte, in ASP.NET MVC Core erstellte Aufgabenanwendung, die als Azure-Web-App gehostet wird und Azure Cosmos DB zur Datenspeicherung nutzt.</span><span class="sxs-lookup"><span data-stu-id="81115-106">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure Cosmos DB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="81115-107">Voraussetzungen</span><span class="sxs-lookup"><span data-stu-id="81115-107">Prerequisites</span></span>

* <span data-ttu-id="81115-108">Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="81115-108">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>
* <span data-ttu-id="81115-109">[.NET Core](https://www.microsoft.com/net/download/core) (optional)</span><span class="sxs-lookup"><span data-stu-id="81115-109">[.NET Core](https://www.microsoft.com/net/download/core) (optional)</span></span>
* <span data-ttu-id="81115-110">[Azure CLI 2.0](/cli/azure/install-az-cli2) (optional)</span><span class="sxs-lookup"><span data-stu-id="81115-110">[Azure CLI 2.0](/cli/azure/install-az-cli2) (optional)</span></span>
* <span data-ttu-id="81115-111">[Git](https://www.git-scm.com/)-Befehlszeilenclient (optional)</span><span class="sxs-lookup"><span data-stu-id="81115-111">[Git](https://www.git-scm.com/) command line client (optional)</span></span>

<span data-ttu-id="81115-112">In der [Azure Cloud Shell](/azure/cloud-shell/) sind alle optionalen Voraussetzungen für dieses Tutorial vorinstalliert.</span><span class="sxs-lookup"><span data-stu-id="81115-112">The [Azure Cloud Shell](/azure/cloud-shell/) has all of the optional prerequisites for this tutorial preinstalled.</span></span>  <span data-ttu-id="81115-113">Sie müssen die oben aufgeführten optionalen Komponenten nur installieren, wenn Sie das Tutorial lokal ausführen möchten.</span><span class="sxs-lookup"><span data-stu-id="81115-113">You only need to install the optional components above if you wish to run the tutorial locally.</span></span>  <span data-ttu-id="81115-114">Um die Cloud Shell schnell zu starten, klicken Sie einfach in einem der folgenden Codeblöcke rechts oben auf die Schaltfläche **Ausprobieren**.</span><span class="sxs-lookup"><span data-stu-id="81115-114">To quickly launch the Cloud Shell, just click the **Try it** button in the top-right of any of the below code blocks.</span></span>

## <a name="create-an-azure-cosmos-db-account"></a><span data-ttu-id="81115-115">Erstellen eines Azure Cosmos DB-Kontos</span><span class="sxs-lookup"><span data-stu-id="81115-115">Create an Azure Cosmos DB account</span></span>

<span data-ttu-id="81115-116">Da in diesem Tutorial Azure Cosmos DB als Datenspeicher verwendet wird, muss ein Konto erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="81115-116">Azure Cosmos DB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="81115-117">Führen Sie dieses Skript lokal oder in der Cloud Shell aus, um ein Azure Cosmos DB-Konto für die SQL-API zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="81115-117">Run this script locally or in the Cloud Shell to create an Azure Cosmos DB SQL API account.</span></span>

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

## <a name="download-and-configure-the-application"></a><span data-ttu-id="81115-118">Herunterladen und Konfigurieren der Anwendung</span><span class="sxs-lookup"><span data-stu-id="81115-118">Download and configure the application</span></span>

<span data-ttu-id="81115-119">Die Anwendung, die Sie bereitstellen, ist eine [einfache App](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/), die in ASP.NET MVC Core geschrieben wird und Azure Cosmos DB-Clientbibliotheken verwendet.</span><span class="sxs-lookup"><span data-stu-id="81115-119">The application you're going to deploy is a [simple to-do app](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/) written using ASP.NET MVC Core using the Azure Cosmos DB client libraries.</span></span>  <span data-ttu-id="81115-120">Im nächsten Schritt rufen Sie den Code für dieses Tutorial ab und konfigurieren ihn mit Ihren Azure Cosmos DB-Informationen.</span><span class="sxs-lookup"><span data-stu-id="81115-120">Now you'll get the code for this tutorial and configure it with your Azure Cosmos DB information.</span></span>

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
> <span data-ttu-id="81115-121">Wenn Sie `git commit` noch nicht zuvor in dieser Umgebung ausgeführt haben, werden Sie ggf. aufgefordert, Ihre Identität festzulegen.</span><span class="sxs-lookup"><span data-stu-id="81115-121">If you've never run `git commit` in this environment before, you may be prompted to set your identity.</span></span> <span data-ttu-id="81115-122">Führen Sie die Anweisungen auf dem Bildschirm und dann den Befehl `git commit` erneut aus.</span><span class="sxs-lookup"><span data-stu-id="81115-122">Follow the on-screen instructions and then re-run the `git commit` command.</span></span>

<span data-ttu-id="81115-123">Stellen Sie die NuGet-Pakete wieder her, und erstellen Sie die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="81115-123">Restore the NuGet packages and build the application.</span></span>

```azurecli-interactive
dotnet restore
dotnet build
```

> [!TIP]
> <span data-ttu-id="81115-124">Wenn Sie die Tools auf Ihrem eigenen Computer verwenden, können Sie die Anwendung testen, indem Sie `dotnet run` ausführen und zur angezeigten Adresse von `localhost` navigieren.</span><span class="sxs-lookup"><span data-stu-id="81115-124">If you are using the tools on your own machine, you can test the application by running `dotnet run` and browsing to the displayed `localhost` address.</span></span>  <span data-ttu-id="81115-125">In der Cloud Shell können Sie allerdings nicht zu dieser Adresse navigieren.</span><span class="sxs-lookup"><span data-stu-id="81115-125">You are not able to browse to this address in the Cloud Shell, however.</span></span>  

## <a name="configure-azure-app-service-and-deploy-the-web-app"></a><span data-ttu-id="81115-126">Konfigurieren von Azure App Service und Bereitstellen der Web-App</span><span class="sxs-lookup"><span data-stu-id="81115-126">Configure Azure App Service and deploy the web app</span></span>

<span data-ttu-id="81115-127">Sie haben die Webanwendung erfolgreich heruntergeladen und erstellt, die Sie nun als Azure-Web-App bereitstellen können.</span><span class="sxs-lookup"><span data-stu-id="81115-127">You've successfully downloaded and built the web application, and you're ready to deploy it as an Azure Web App.</span></span>  <span data-ttu-id="81115-128">Sie beginnen mit dem Erstellen einer Web-App-Ressource.</span><span class="sxs-lookup"><span data-stu-id="81115-128">You'll start by creating the Web App resource.</span></span>

```azurecli-interactive
# Generate a unique Web App name
let randomNum=$RANDOM*$RANDOM
webappname=todoApp$randomNum

# Create an App Service plan.
az appservice plan create --name $webappname --resource-group DotNetAzureTutorial --sku FREE

# Create the Web App
az webapp create --name $webappname --resource-group DotNetAzureTutorial --plan $webappname

```

<span data-ttu-id="81115-129">Vor der Bereitstellung müssen Sie die Anmeldeinformationen für die Bereitstellung auf Kontoebene festlegen.</span><span class="sxs-lookup"><span data-stu-id="81115-129">Before you deploy, you need to set the account-level deployment credentials.</span></span>  <span data-ttu-id="81115-130">Verwenden Sie das folgende Skript, und fügen Sie Ihre eigenen Werte für den Benutzernamen und das Kennwort ein.</span><span class="sxs-lookup"><span data-stu-id="81115-130">Use the script below, making sure to include your own values for the user name and password.</span></span>

```azurecli-interactive
az webapp deployment user set --user-name <desired user name> --password <desired password>
```

<span data-ttu-id="81115-131">Stellen Sie schließlich die Anwendung in Azure bereit.</span><span class="sxs-lookup"><span data-stu-id="81115-131">Finally, deploy the application to Azure.</span></span>  <span data-ttu-id="81115-132">Sie werden aufgefordert, das zuvor erstellte Kennwort einzugeben.</span><span class="sxs-lookup"><span data-stu-id="81115-132">You will be prompted for the password you created above.</span></span>

```azurecli-interactive
# Get the Git deployment URL
giturl=$(az webapp deployment source config-local-git -n $webappname -g DotNetAzureTutorial --query [url] -o tsv)

# Add the URL as a Git remote repository
git remote add azure $giturl

# Push the local repository to the remote
git push azure master
```

<span data-ttu-id="81115-133">Die Anwendung wird remote erstellt und bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="81115-133">The application will be built remotely and deployed.</span></span>  <span data-ttu-id="81115-134">Testen Sie die Anwendung, indem Sie zu `https://<web app name>.azurewebsites.net` wechseln.</span><span class="sxs-lookup"><span data-stu-id="81115-134">Test the application by browsing to `https://<web app name>.azurewebsites.net`.</span></span>  <span data-ttu-id="81115-135">Um die Adresse in der Konsole anzuzeigen, verwenden Sie Folgendes:</span><span class="sxs-lookup"><span data-stu-id="81115-135">To display the address in the console, use the following:</span></span>

```azurecli-interactive
az webapp show -n $webappname -g DotNetAzureTutorial --query defaultHostName -o tsv
```

<span data-ttu-id="81115-136">Sie können der Aufgabenliste neue Elemente hinzufügen, indem Sie auf **Neu erstellen** klicken.</span><span class="sxs-lookup"><span data-stu-id="81115-136">You can add new items to the to-do list by clicking **Create New**.</span></span>

![Die fertige App](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="81115-138">Bereinigen</span><span class="sxs-lookup"><span data-stu-id="81115-138">Clean up</span></span>

<span data-ttu-id="81115-139">Wenn Sie die App getestet und sich mit dem Code und den Ressourcen vertraut gemacht haben, können Sie die Web-App und das Azure Cosmos DB-Konto löschen, indem Sie die Ressourcengruppe löschen.</span><span class="sxs-lookup"><span data-stu-id="81115-139">When you're done testing the app and inspecting the code and resources, you can delete the Web App and Azure Cosmos DB account by deleting the resource group.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="81115-140">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="81115-140">Next steps</span></span>

* [<span data-ttu-id="81115-141">An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD</span><span class="sxs-lookup"><span data-stu-id="81115-141">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="81115-142">Erstellen einer Azure-Web-App mithilfe von Azure SQL-Datenbank</span><span class="sxs-lookup"><span data-stu-id="81115-142">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="81115-143">Testen einer .NET-Beispielanwendung mit Azure Storage</span><span class="sxs-lookup"><span data-stu-id="81115-143">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


