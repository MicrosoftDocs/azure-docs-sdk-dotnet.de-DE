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
ms.openlocfilehash: d5c34dfc7e649e00e8ef458537f3f76410db61d4
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2018
---
# <a name="deploy-to-azure-from-visual-studio"></a>Bereitstellen in Azure mithilfe von Visual Studio

Dieses Tutorial führt Sie durch das Erstellen und Bereitstellen einer Microsoft Azure-Anwendung mithilfe von Visual Studio und .NET.  Im Anschluss verfügen Sie über eine webbasierte in ASP.NET MVC Core erstellte Anwendung, die als Azure-Web-App gehostet wird und Azure CosmosDB zur Datenspeicherung nutzt.

## <a name="prerequisites"></a>Voraussetzungen

* [Visual Studio 2017](https://www.visualstudio.com/downloads/)
* Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)

## <a name="create-a-cosmosdb-account"></a>Erstellen eines CosmosDB-Kontos

CosmosDB dient in diesem Tutorial als Datenspeicher, weshalb Sie ein Konto erstellen müssen.  Führen Sie dieses Skript entweder lokal oder in der Cloud Shell aus, um ein Azure CosmosDB DocumentDB-API-Konto zu erstellen.  Klicken Sie im nachstehenden Codeblock auf die Schaltfläche **Ausprobieren**, um die [Azure Cloud Shell](/azure/cloud-shell/) zu öffnen. Kopieren Sie den Skriptblock, und fügen Sie ihn in die Shell ein.

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

Notieren Sie sich die angezeigten Werte für **authKey** und **endpoint**. 

## <a name="downloading-and-running-the-application"></a>Herunterladen und Ausführen der Anwendung

Rufen Sie den Beispielcode für diese exemplarische Vorgehensweise ab, und verknüpfen Sie ihn mit Ihrem CosmosDB-Konto.

1. Laden Sie den Beispielcode herunter.  Sie können [ihn von GitHub abrufen](https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart/). Wenn Sie über den [Git-Befehlszeilenclient](https://git-scm.com/) verfügen, können Sie ihn auch über den folgenden Befehl auf Ihren lokalen Computer klonen:

    ```cmd
    git clone https://github.com/Azure-Samples/dotnet-cosmosdb-quickstart
    ```

2. Öffnen Sie **todo.csproj** in Visual Studio.

3. Öffnen Sie **appsettings.json** im Webprojekt.  Suchen Sie die folgenden Zeilen:

    ```json
    "authKey": "AUTHKEYVALUE",
    "endpoint": "ENDPOINTVALUE",
    ```
    Ersetzen Sie **AUTHKEYVALUE** und **ENDPOINTVALUE** durch die zuvor notierten Werte.

4. Drücken Sie **F5** zum Wiederherstellen der NuGet-Pakete des Projekts. Erstellen Sie das Projekt, und führen Sie es lokal aus.

Die Webanwendung muss lokal in Ihrem Browser ausgeführt werden.  Sie können der Aufgabenliste neue Elemente hinzufügen, indem Sie auf **Neu erstellen** klicken.  Beachten Sie, dass die Daten, die Sie in die Anwendung eingeben, in Ihrem CosmosDB-Konto gespeichert werden.  Sie können [Ihre Daten im Azure-Portal anzeigen](/azure/documentdb/documentdb-view-json-document-explorer).

## <a name="deploying-the-application-as-an-azure-web-app"></a>Bereitstellen der Anwendung als Azure-Web-App

Sie haben erfolgreich eine Anwendung erstellt, die Azure-Dienste wie DocumentDB verwendet.  Als Nächstes stellen wir unsere Webanwendung in der Cloud bereit.

> [!IMPORTANT]
> Vergewissern Sie sich, dass Sie in Visual Studio mit dem Konto angemeldet sind, das Ihrem Azure-Abonnement zugeordnet ist.

1. Klicken Sie in Visual Studio im Projektmappen-Explorer mit der rechten Maustaste auf den Projektnamen, und wählen Sie **Veröffentlichen...** aus.

2. Wählen Sie im Dialogfeld „Veröffentlichen“ **Microsoft Azure App Service** > **Neu erstellen** aus, und klicken Sie dann auf **Veröffentlichen**.

3. Füllen Sie die Felder im Dialogfeld „App Service erstellen“ wie folgt aus:

    * Geben Sie für **Web-App-Name** einen eindeutigen Namen ein.  Dieser wird Teil der URL Ihrer App.
    * Wählen Sie das Azure-**Abonnement** aus, in dem die Bereitstellung erfolgt.  Verwenden Sie dasselbe Abonnement, mit dem Sie zuvor bei Cloud Shell angemeldet waren.
    * Wählen Sie *DotNetAzureTutorial* als **Ressourcengruppe** für Ihre Webanwendung aus.
    * Wählen oder erstellen Sie einen **App Service-Plan**, um den Tarif für Ihre Anwendung zu bestimmen.  Hier finden Sie [weitere Informationen zu App Service-Plänen](/azure/app-service/azure-web-sites-web-hosting-plans-in-depth-overview).

4. Klicken Sie zum Bereitstellen der Anwendung auf **Erstellen**.  Wenn die Bereitstellung abgeschlossen ist, wird ein Browserfenster mit der bereitgestellten Anwendung geöffnet.

![Die fertige App](./media/dotnet-quickstart/todo.png)

## <a name="clean-up"></a>Bereinigen

Wenn Sie mit dem Testen der App und Untersuchen des Codes und der Ressourcen fertig sind, können Sie die Web-App und das CosmosDB-Konto löschen, indem Sie die Ressourcengruppe löschen. Verwenden Sie dazu die Cloud Shell.

```azurecli-interactive
az group delete -n DotNetAzureTutorial
```

## <a name="next-steps"></a>Nächste Schritte

* [An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet)
* [Erstellen einer Azure-Web-App mithilfe von Azure SQL-Datenbank](/azure/app-service-web/web-sites-dotnet-get-started)
* [Testen einer .NET-Beispielanwendung mit Azure Storage](/azure/storage/storage-samples-dotnet)


