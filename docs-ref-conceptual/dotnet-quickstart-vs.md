---
title: Bereitstellen in Azure mithilfe von Visual Studio
description: Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von Visual Studio und .NET.
keywords: Azure .NET, SDK, Azure .NET-API-Referenz, Azure .NET-Klassenbibliothek
author: camsoper
manager: douge
ms.author: casoper
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.openlocfilehash: 87f65d8b8b1b1a5184b9d71770c08be472c7e498
ms.sourcegitcommit: e1a0e91988bb849c75e9583a80e3e6d712083785
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/14/2018
ms.locfileid: "31005887"
---
# <a name="deploy-to-azure-from-visual-studio"></a><span data-ttu-id="77544-104">Bereitstellen in Azure mithilfe von Visual Studio</span><span class="sxs-lookup"><span data-stu-id="77544-104">Deploy to Azure from Visual Studio</span></span>

<span data-ttu-id="77544-105">Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von Visual Studio und .NET.</span><span class="sxs-lookup"><span data-stu-id="77544-105">This tutorial will walk you through building and deploying a Microsoft Azure application using Visual Studio and .NET.</span></span>  <span data-ttu-id="77544-106">Am Ende verfügen Sie über eine webbasierte, in ASP.NET MVC Core erstellte Aufgabenanwendung, die als Azure-Web-App gehostet wird und Azure Cosmos DB zur Datenspeicherung nutzt.</span><span class="sxs-lookup"><span data-stu-id="77544-106">When finished, you'll have a web-based to-do application built in ASP.NET MVC Core, hosted as an Azure Web App, and using Azure Cosmos DB for data storage.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="77544-107">Voraussetzungen</span><span class="sxs-lookup"><span data-stu-id="77544-107">Prerequisites</span></span>

* [<span data-ttu-id="77544-108">Visual Studio 2017</span><span class="sxs-lookup"><span data-stu-id="77544-108">Visual Studio 2017</span></span>](https://www.visualstudio.com/downloads/)
* <span data-ttu-id="77544-109">Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="77544-109">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>

## <a name="create-an-azure-cosmos-db-account"></a><span data-ttu-id="77544-110">Erstellen eines Azure Cosmos DB-Kontos</span><span class="sxs-lookup"><span data-stu-id="77544-110">Create an Azure Cosmos DB account</span></span>

<span data-ttu-id="77544-111">Da in diesem Tutorial Azure Cosmos DB als Datenspeicher verwendet wird, muss ein Konto erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="77544-111">Azure Cosmos DB is used for data storage in this tutorial, so you'll need to create an account.</span></span>  <span data-ttu-id="77544-112">Führen Sie dieses Skript lokal oder in der Cloud Shell aus, um ein Azure Cosmos DB-Konto für die SQL-API zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="77544-112">Run this script locally or in the Cloud Shell to create an Azure Cosmos DB SQL API account.</span></span>  <span data-ttu-id="77544-113">Klicken Sie im nachstehenden Codeblock auf die Schaltfläche **Ausprobieren**, um die [Azure Cloud Shell](/azure/cloud-shell/) zu öffnen. Kopieren Sie den Skriptblock, und fügen Sie ihn in die Shell ein.</span><span class="sxs-lookup"><span data-stu-id="77544-113">Click the **Try it** button on the code block below to launch the [Azure Cloud Shell](/azure/cloud-shell/) and copy/paste the script block into the shell.</span></span>

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
printf "\n\nauthKey: $cosmosAuthKey\nendpoint: $cosmosEndpoint\n\n"

# Done!

```

<span data-ttu-id="77544-114">Notieren Sie sich die angezeigten Werte für **authKey** und **endpoint**.</span><span class="sxs-lookup"><span data-stu-id="77544-114">Make a note of the displayed **authKey** and **endpoint**</span></span> 

## <a name="downloading-and-running-the-application"></a><span data-ttu-id="77544-115">Herunterladen und Ausführen der Anwendung</span><span class="sxs-lookup"><span data-stu-id="77544-115">Downloading and running the application</span></span>

<span data-ttu-id="77544-116">Rufen Sie den Beispielcode für diese exemplarische Vorgehensweise ab, und verknüpfen Sie ihn mit Ihrem Azure Cosmos DB-Konto.</span><span class="sxs-lookup"><span data-stu-id="77544-116">Let's get the sample code for this walkthrough and hook it up to your Azure Cosmos DB account.</span></span>

1. <span data-ttu-id="77544-117">Laden Sie den Beispielcode herunter.</span><span class="sxs-lookup"><span data-stu-id="77544-117">Download the sample code.</span></span>  <span data-ttu-id="77544-118">Sie können [ihn von GitHub abrufen](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/). Wenn Sie über den [Git-Befehlszeilenclient](https://git-scm.com/) verfügen, können Sie ihn auch über den folgenden Befehl auf Ihren lokalen Computer klonen:</span><span class="sxs-lookup"><span data-stu-id="77544-118">You can [get it from GitHub](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/), or if you have the [git command line client](https://git-scm.com/), clone it to your local machine with the following command:</span></span>

    ```cmd
    git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart
    ```

2. <span data-ttu-id="77544-119">Öffnen Sie **todo.csproj** in Visual Studio.</span><span class="sxs-lookup"><span data-stu-id="77544-119">Open **todo.csproj** in Visual Studio.</span></span>

3. <span data-ttu-id="77544-120">Öffnen Sie **appsettings.json** im Webprojekt.</span><span class="sxs-lookup"><span data-stu-id="77544-120">Open **appsettings.json** in the web project.</span></span>  <span data-ttu-id="77544-121">Suchen Sie die folgenden Zeilen:</span><span class="sxs-lookup"><span data-stu-id="77544-121">Look for the following lines:</span></span>

    ```json
    "authKey": "AUTHKEYVALUE",
    "endpoint": "ENDPOINTVALUE",
    ```
    <span data-ttu-id="77544-122">Ersetzen Sie **AUTHKEYVALUE** und **ENDPOINTVALUE** durch die zuvor notierten Werte.</span><span class="sxs-lookup"><span data-stu-id="77544-122">Replace **AUTHKEYVALUE** and **ENDPOINTVALUE** with the values you noted earlier.</span></span>

4. <span data-ttu-id="77544-123">Drücken Sie **F5** zum Wiederherstellen der NuGet-Pakete des Projekts. Erstellen Sie das Projekt, und führen Sie es lokal aus.</span><span class="sxs-lookup"><span data-stu-id="77544-123">Press **F5** to restore the project's NuGet packages, build the project, and run it locally.</span></span>

<span data-ttu-id="77544-124">Die Webanwendung muss lokal in Ihrem Browser ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="77544-124">The web application should run locally in your browser.</span></span>  <span data-ttu-id="77544-125">Sie können der Aufgabenliste neue Elemente hinzufügen, indem Sie auf **Neu erstellen** klicken.</span><span class="sxs-lookup"><span data-stu-id="77544-125">You can add new items to the to-do list by clicking **Create New**.</span></span>  <span data-ttu-id="77544-126">Beachten Sie, dass die Daten, die Sie in die Anwendung eingeben, in Ihrem Azure Cosmos DB-Konto gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="77544-126">Note the data you enter in the application is being stored in your Azure Cosmos DB account.</span></span>  <span data-ttu-id="77544-127">Ihre Daten können Sie im [Azure-Portal](https://portal.azure.com) anzeigen. Klicken Sie hierzu im linken Menü auf „Azure Cosmos DB“, klicken Sie auf Ihr Konto, und klicken Sie anschließend auf **Daten-Explorer**.</span><span class="sxs-lookup"><span data-stu-id="77544-127">You can view your data in the [Azure portal](https://portal.azure.com) by selecting Azure Cosmos DB from the left menu, selecting your account, and then selecting **Data Explorer**.</span></span>

## <a name="deploying-the-application-as-an-azure-web-app"></a><span data-ttu-id="77544-128">Bereitstellen der Anwendung als Azure-Web-App</span><span class="sxs-lookup"><span data-stu-id="77544-128">Deploying the application as an Azure Web App</span></span>

<span data-ttu-id="77544-129">Sie haben erfolgreich eine Anwendung erstellt, die Azure-Dienste wie Azure Cosmos DB verwendet.</span><span class="sxs-lookup"><span data-stu-id="77544-129">You've successfully built an application that uses Azure services like Azure Cosmos DB.</span></span>  <span data-ttu-id="77544-130">Als Nächstes stellen wir unsere Webanwendung in der Cloud bereit.</span><span class="sxs-lookup"><span data-stu-id="77544-130">Next, we'll deploy our web application to the cloud.</span></span>

> [!IMPORTANT]
> <span data-ttu-id="77544-131">Vergewissern Sie sich, dass Sie in Visual Studio mit dem Konto angemeldet sind, das Ihrem Azure-Abonnement zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="77544-131">Be sure you're signed into Visual Studio with the same account your Azure subscription is associated with.</span></span>

1. <span data-ttu-id="77544-132">Klicken Sie in Visual Studio im Projektmappen-Explorer mit der rechten Maustaste auf den Projektnamen, und wählen Sie **Veröffentlichen...** aus.</span><span class="sxs-lookup"><span data-stu-id="77544-132">In Visual Studio Solution Explorer, right-click on the project name and select **Publish...**</span></span>

2. <span data-ttu-id="77544-133">Wählen Sie im Dialogfeld „Veröffentlichen“ **Microsoft Azure App Service** > **Neu erstellen** aus, und klicken Sie dann auf **Veröffentlichen**.</span><span class="sxs-lookup"><span data-stu-id="77544-133">Using the Publish dialog, select **Microsoft Azure App Service**, select **Create New**, and then click **Publish**</span></span>

3. <span data-ttu-id="77544-134">Füllen Sie die Felder im Dialogfeld „App Service erstellen“ wie folgt aus:</span><span class="sxs-lookup"><span data-stu-id="77544-134">Complete the Create App Service dialog as follows:</span></span>

    * <span data-ttu-id="77544-135">Geben Sie für **Web-App-Name** einen eindeutigen Namen ein.</span><span class="sxs-lookup"><span data-stu-id="77544-135">Enter a unique **Web App Name**.</span></span>  <span data-ttu-id="77544-136">Dieser wird Teil der URL Ihrer App.</span><span class="sxs-lookup"><span data-stu-id="77544-136">This will be part of the URL for your app.</span></span>
    * <span data-ttu-id="77544-137">Wählen Sie das Azure-**Abonnement** aus, in dem die Bereitstellung erfolgt.</span><span class="sxs-lookup"><span data-stu-id="77544-137">Select the Azure **Subscription** you're deploying to.</span></span>  <span data-ttu-id="77544-138">Verwenden Sie dasselbe Abonnement, mit dem Sie zuvor bei Cloud Shell angemeldet waren.</span><span class="sxs-lookup"><span data-stu-id="77544-138">Use same subscription with which you were logged into Cloud Shell earlier.</span></span>
    * <span data-ttu-id="77544-139">Wählen Sie *DotNetAzureTutorial* als **Ressourcengruppe** für Ihre Webanwendung aus.</span><span class="sxs-lookup"><span data-stu-id="77544-139">Select *DotNetAzureTutorial* for the **Resource Group** for your web application.</span></span>
    * <span data-ttu-id="77544-140">Wählen oder erstellen Sie einen **App Service-Plan**, um den Tarif für Ihre Anwendung zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="77544-140">Select or create an **App Service Plan** to determine the pricing your your application.</span></span>  <span data-ttu-id="77544-141">Hier finden Sie [weitere Informationen zu App Service-Plänen](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview).</span><span class="sxs-lookup"><span data-stu-id="77544-141">Here's [more information about App Service Plans](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview).</span></span>

4. <span data-ttu-id="77544-142">Klicken Sie zum Bereitstellen der Anwendung auf **Erstellen**.</span><span class="sxs-lookup"><span data-stu-id="77544-142">Click **Create** to deploy the application.</span></span>  <span data-ttu-id="77544-143">Wenn die Bereitstellung abgeschlossen ist, wird ein Browserfenster mit der bereitgestellten Anwendung geöffnet.</span><span class="sxs-lookup"><span data-stu-id="77544-143">When deployment is complete, a browser will open with your deployed application.</span></span>

![Die fertige App](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a><span data-ttu-id="77544-145">Bereinigen</span><span class="sxs-lookup"><span data-stu-id="77544-145">Clean up</span></span>

<span data-ttu-id="77544-146">Wenn Sie die App getestet und sich mit dem Code und den Ressourcen vertraut gemacht haben, können Sie die Web-App und das Azure Cosmos DB-Konto löschen, indem Sie die Ressourcengruppe in der Cloud Shell löschen.</span><span class="sxs-lookup"><span data-stu-id="77544-146">When you're done testing the app and inspecting the code and resources, you can delete the Web App and Azure Cosmos DB account by deleting the resource group in the Cloud Shell.</span></span>

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a><span data-ttu-id="77544-147">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="77544-147">Next steps</span></span>

* [<span data-ttu-id="77544-148">An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD</span><span class="sxs-lookup"><span data-stu-id="77544-148">Use Azure Active Directory for authentication in an ASP.NET web application</span></span>](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [<span data-ttu-id="77544-149">Erstellen einer Azure-Web-App mithilfe von Azure SQL-Datenbank</span><span class="sxs-lookup"><span data-stu-id="77544-149">Build an Azure Web App using Azure SQL Database</span></span>](/azure/app-service-web/web-sites-dotnet-get-started)
* [<span data-ttu-id="77544-150">Testen einer .NET-Beispielanwendung mit Azure Storage</span><span class="sxs-lookup"><span data-stu-id="77544-150">Try a .NET sample application with Azure Storage</span></span>](/azure/storage/storage-samples-dotnet)


