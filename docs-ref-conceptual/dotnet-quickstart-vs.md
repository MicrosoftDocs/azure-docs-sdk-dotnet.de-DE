---
title: Bereitstellen in Azure mithilfe von Visual Studio
description: "Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von Visual Studio und .NET."
keywords: Azure .NET, SDK, Azure .NET-API-Referenz, Azure .NET-Klassenbibliothek
author: camsoper
manager: douge
ms.author: casoper
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.assetid: 
ms.openlocfilehash: 0f8e3e5ea1ef5cde239b2d8ebbc9fe75dd978cb1
ms.sourcegitcommit: c630918c9e17f5e3c6d4f28fe740c041f60b1e66
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/03/2017
---
# <a name="deploy-to-azure-from-visual-studio"></a><span data-ttu-id="c53a8-104">Bereitstellen in Azure mithilfe von Visual Studio</span><span class="sxs-lookup"><span data-stu-id="c53a8-104">Deploy to Azure from Visual Studio</span></span>

<span data-ttu-id="c53a8-105">Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von Visual Studio und .NET.</span><span class="sxs-lookup"><span data-stu-id="c53a8-105">This tutorial will walk you through building and deploying a Microsoft Azure application using Visual Studio and .NET.</span></span>  <span data-ttu-id="c53a8-106">Im Anschluss verfügen Sie über eine webbasierte in ASP.NET MVC Core erstellte Anwendung, die als Azure-Web-App gehostet wird und Azure CosmosDB zur Datenspeicherung nutzt.</span><span class="sxs-lookup"><span data-stu-id="c53a8-106">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure CosmosDB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="c53a8-107">Voraussetzungen</span><span class="sxs-lookup"><span data-stu-id="c53a8-107">Prerequisites</span></span>

* [<span data-ttu-id="c53a8-108">Visual Studio 2017</span><span class="sxs-lookup"><span data-stu-id="c53a8-108">Visual Studio 2017</span></span>](https://www.visualstudio.com/downloads/)
* <span data-ttu-id="c53a8-109">Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="c53a8-109">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>

## <a name="create-a-cosmosdb-account"></a><span data-ttu-id="c53a8-110">Erstellen eines CosmosDB-Kontos</span><span class="sxs-lookup"><span data-stu-id="c53a8-110">Create a CosmosDB account</span></span>

<span data-ttu-id="c53a8-111">CosmosDB dient in diesem Tutorial als Datenspeicher, weshalb Sie ein Konto erstellen müssen.</span><span class="sxs-lookup"><span data-stu-id="c53a8-111">CosmosDB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="c53a8-112">Führen Sie dieses Skript entweder lokal oder in der Cloud Shell aus, um ein Azure CosmosDB DocumentDB-API-Konto zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="c53a8-112">Run this script locally or in the Cloud Shell to create an Azure CosmosDB DocumentDB API account.</span></span>  <span data-ttu-id="c53a8-113">Klicken Sie im nachstehenden Codeblock auf die Schaltfläche **Ausprobieren**, um die [Azure Cloud Shell](/azure/cloud-shell/) zu öffnen. Kopieren Sie den Skriptblock, und fügen Sie ihn in die Shell ein.</span><span class="sxs-lookup"><span data-stu-id="c53a8-113">Click the **Try it** button on the code block below to launch the [Azure Cloud Shell](/azure/cloud-shell/) and copy/paste the script block into the shell.</span></span>

```azurecli-interactive
# Create the DotNetAzureTutorial resource group
az group create --name DotNetAzureTutorial --location EastUS

# Generate a unique name for the account
let randomNum=$RANDOM*$RANDOM
cosmosdbname=dotnettutorial$randomNum

# Create the CosmosDB account
az cosmosdb create --name $cosmosdbname --resource-group DotNetAzureTutorial

# Retrieve the endpoint and key (you'll need these later)
cosmosEndpoint=$(az cosmosdb show -n $cosmosdbname -g DotNetAzureTutorial --query [documentEndpoint] -o tsv)
cosmosAuthKey=$(az cosmosdb list-keys -n $cosmosdbname -g DotNetAzureTutorial --query [primaryMasterKey] -o tsv)
printf "\n\nauthKey: $cosmosAuthKey\nendpoint: $cosmosEndpoint\n\n"

# Done!

```

<span data-ttu-id="c53a8-114">Notieren Sie sich die angezeigten Werte für **authKey** und **endpoint**.</span><span class="sxs-lookup"><span data-stu-id="c53a8-114">Make a note of the displayed **authKey** and **endpoint**</span></span> 

## <a name="downloading-and-running-the-application"></a><span data-ttu-id="c53a8-115">Herunterladen und Ausführen der Anwendung</span><span class="sxs-lookup"><span data-stu-id="c53a8-115">Downloading and running the application</span></span>

<span data-ttu-id="c53a8-116">Rufen Sie den Beispielcode für diese exemplarische Vorgehensweise ab, und verknüpfen Sie ihn mit Ihrem CosmosDB-Konto.</span><span class="sxs-lookup"><span data-stu-id="c53a8-116">Let's get the sample code for this walkthrough and hook it up to your CosmosDB account.</span></span>

1. <span data-ttu-id="c53a8-117">Laden Sie den Beispielcode herunter.</span><span class="sxs-lookup"><span data-stu-id="c53a8-117">Download the sample code.</span></span>  <span data-ttu-id="c53a8-118">Sie können [ihn von GitHub abrufen](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/). Wenn Sie über den [Git-Befehlszeilenclient](https://git-scm.com/) verfügen, können Sie ihn auch über den folgenden Befehl auf Ihren lokalen Computer klonen:</span><span class="sxs-lookup"><span data-stu-id="c53a8-118">You can [get it from GitHub](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/), or if you have the [git command line client](https://git-scm.com/), clone it to your local machine with the following command:</span></span>

    ```cmd
    git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart
    ```

2. <span data-ttu-id="c53a8-119">Öffnen Sie **todo.csproj** in Visual Studio.</span><span class="sxs-lookup"><span data-stu-id="c53a8-119">Open **todo.csproj** in Visual Studio.</span></span>

3. <span data-ttu-id="c53a8-120">Öffnen Sie **appsettings.json** im Webprojekt.</span><span class="sxs-lookup"><span data-stu-id="c53a8-120">Open **appsettings.json** in the web project.</span></span>  <span data-ttu-id="c53a8-121">Suchen Sie die folgenden Zeilen:</span><span class="sxs-lookup"><span data-stu-id="c53a8-121">Look for the following lines:</span></span>

    ```json
    "authKey": "AUTHKEYVALUE",
    "endpoint": "ENDPOINTVALUE",
    ```
    <span data-ttu-id="c53a8-122">Ersetzen Sie **AUTHKEYVALUE** und **ENDPOINTVALUE** durch die zuvor notierten Werte.</span><span class="sxs-lookup"><span data-stu-id="c53a8-122">Replace **AUTHKEYVALUE** and **ENDPOINTVALUE** with the values you noted earlier.</span></span>

4. <span data-ttu-id="c53a8-123">Drücken Sie **F5** zum Wiederherstellen der NuGet-Pakete des Projekts. Erstellen Sie das Projekt, und führen Sie es lokal aus.</span><span class="sxs-lookup"><span data-stu-id="c53a8-123">Press **F5** to restore the project's NuGet packages, build the project, and run it locally.</span></span>

<span data-ttu-id="c53a8-124">Die Webanwendung muss lokal in Ihrem Browser ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="c53a8-124">The web application should run locally in your browser.</span></span>  <span data-ttu-id="c53a8-125">Sie können der Aufgabenliste neue Elemente hinzufügen, indem Sie auf **Neu erstellen** klicken.</span><span class="sxs-lookup"><span data-stu-id="c53a8-125">You can add new items to the to-do list by clicking **Create New**.</span></span>  <span data-ttu-id="c53a8-126">Beachten Sie, dass die Daten, die Sie in die Anwendung eingeben, in Ihrem CosmosDB-Konto gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="c53a8-126">Note the data you enter in the application is being stored in your CosmosDB account.</span></span>  <span data-ttu-id="c53a8-127">Sie können [Ihre Daten im Azure-Portal anzeigen](/azure/documentdb/documentdb-view-json-document-explorer).</span><span class="sxs-lookup"><span data-stu-id="c53a8-127">You can [view your data in the Azure portal](/azure/documentdb/documentdb-view-json-document-explorer).</span></span>

## <a name="deploying-the-application-as-an-azure-web-app"></a><span data-ttu-id="c53a8-128">Bereitstellen der Anwendung als Azure-Web-App</span><span class="sxs-lookup"><span data-stu-id="c53a8-128">Deploying the application as an Azure Web App</span></span>

<span data-ttu-id="c53a8-129">Sie haben erfolgreich eine Anwendung erstellt, die Azure-Dienste wie DocumentDB verwendet.</span><span class="sxs-lookup"><span data-stu-id="c53a8-129">You've successfully built an application that uses Azure services like DocumentDB.</span></span>  <span data-ttu-id="c53a8-130">Als Nächstes stellen wir unsere Webanwendung in der Cloud bereit.</span><span class="sxs-lookup"><span data-stu-id="c53a8-130">Next, we'll deploy our web application to the cloud.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="c53a8-131">Vergewissern Sie sich, dass Sie in Visual Studio mit dem Konto angemeldet sind, das Ihrem Azure-Abonnement zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="c53a8-131">Be sure you're signed into Visual Studio with the same account your Azure subscription is associated with.</span></span>

1. <span data-ttu-id="c53a8-132">Klicken Sie in Visual Studio im Projektmappen-Explorer mit der rechten Maustaste auf den Projektnamen, und wählen Sie **Veröffentlichen...** aus.</span><span class="sxs-lookup"><span data-stu-id="c53a8-132">In Visual Studio Solution Explorer, right-click on the project name and select **Publish...**</span></span>

2. <span data-ttu-id="c53a8-133">Wählen Sie im Dialogfeld „Veröffentlichen“ **Microsoft Azure App Service** > **Neu erstellen** aus, und klicken Sie dann auf **Veröffentlichen**.</span><span class="sxs-lookup"><span data-stu-id="c53a8-133">Using the Publish dialog, select **Microsoft Azure App Service**, select **Create New**, and then click **Publish**</span></span>

3. <span data-ttu-id="c53a8-134">Füllen Sie die Felder im Dialogfeld „App Service erstellen“ wie folgt aus:</span><span class="sxs-lookup"><span data-stu-id="c53a8-134">Complete the Create App Service dialog as follows:</span></span>

    * <span data-ttu-id="c53a8-135">Geben Sie für **Web-App-Name** einen eindeutigen Namen ein.</span><span class="sxs-lookup"><span data-stu-id="c53a8-135">Enter a unique **Web App Name**.</span></span>  <span data-ttu-id="c53a8-136">Dieser wird Teil der URL Ihrer App.</span><span class="sxs-lookup"><span data-stu-id="c53a8-136">This will be part of the URL for your app.</span></span>
    * <span data-ttu-id="c53a8-137">Wählen Sie das Azure-**Abonnement** aus, in dem die Bereitstellung erfolgt.</span><span class="sxs-lookup"><span data-stu-id="c53a8-137">Select the Azure **Subscription** you're deploying to.</span></span>  <span data-ttu-id="c53a8-138">Verwenden Sie dasselbe Abonnement, mit dem Sie zuvor bei Cloud Shell angemeldet waren.</span><span class="sxs-lookup"><span data-stu-id="c53a8-138">Use same subscription with which you were logged into Cloud Shell earlier.</span></span>
    * <span data-ttu-id="c53a8-139">Wählen Sie *DotNetAzureTutorial* als **Ressourcengruppe** für Ihre Webanwendung aus.</span><span class="sxs-lookup"><span data-stu-id="c53a8-139">Select *DotNetAzureTutorial* for the **Resource Group** for your web application.</span></span>
    * <span data-ttu-id="c53a8-140">Wählen oder erstellen Sie einen **App Service-Plan**, um den Tarif für Ihre Anwendung zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="c53a8-140">Select or create an **App Service Plan** to determine the pricing your your application.</span></span>  <span data-ttu-id="c53a8-141">Hier finden Sie [weitere Informationen zu App Service-Plänen](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview).</span><span class="sxs-lookup"><span data-stu-id="c53a8-141">Here's [more information about App Service Plans](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview).</span></span>

4. <span data-ttu-id="c53a8-142">Klicken Sie zum Bereitstellen der Anwendung auf **Erstellen**.</span><span class="sxs-lookup"><span data-stu-id="c53a8-142">Click **Create** to deploy the application.</span></span>  <span data-ttu-id="c53a8-143">Wenn die Bereitstellung abgeschlossen ist, wird ein Browserfenster mit der bereitgestellten Anwendung geöffnet.</span><span class="sxs-lookup"><span data-stu-id="c53a8-143">When deployment is complete, a browser will open with your deployed application.</span></span>

![Die fertige App](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="c53a8-145">Bereinigen</span><span class="sxs-lookup"><span data-stu-id="c53a8-145">Clean up</span></span>

<span data-ttu-id="c53a8-146">Wenn Sie mit dem Testen der App und Untersuchen des Codes und der Ressourcen fertig sind, können Sie die Web-App und das CosmosDB-Konto löschen, indem Sie die Ressourcengruppe löschen.</span><span class="sxs-lookup"><span data-stu-id="c53a8-146">When you're done testing the app and inspecting the code and resources, you can delete the Web App and CosmosDB account by deleting the resource group.</span></span> <span data-ttu-id="c53a8-147">Verwenden Sie dazu die Cloud Shell.</span><span class="sxs-lookup"><span data-stu-id="c53a8-147">in the Cloud Shell.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="c53a8-148">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="c53a8-148">Next steps</span></span>

* [<span data-ttu-id="c53a8-149">An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD</span><span class="sxs-lookup"><span data-stu-id="c53a8-149">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="c53a8-150">Erstellen einer Azure-Web-App mithilfe von Azure SQL-Datenbank</span><span class="sxs-lookup"><span data-stu-id="c53a8-150">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="c53a8-151">Testen einer .NET-Beispielanwendung mit Azure Storage</span><span class="sxs-lookup"><span data-stu-id="c53a8-151">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


