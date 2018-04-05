---
title: Azure-Tools für Visual Studio 2015
description: Informationen zum Abrufen der Tools für das Verwenden der Azure .NET-Bibliotheken in Visual Studio 2015.
keywords: Azure .NET, SDK, VS2015, Visual Studio 2015
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 5046781a16b5b330b95c4ad36e8a8187126fef4e
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2018
---
# <a name="azure-tools-for-visual-studio-2015"></a><span data-ttu-id="33e7a-104">Azure-Tools für Visual Studio 2015</span><span class="sxs-lookup"><span data-stu-id="33e7a-104">Azure tools for Visual Studio 2015</span></span>

<span data-ttu-id="33e7a-105">Die schnellste und einfachste Methode zum Installieren der Elemente **Azure SDK für Visual Studio 2015** und **Service Fabric SDK und Tools für Visual Studio 2015** ist der [Webplattform-Installer](https://www.microsoft.com/web/downloads/platform.aspx).</span><span class="sxs-lookup"><span data-stu-id="33e7a-105">The quickest and easiest way to install the **Azure SDK for Visual Studio 2015** and **Service Fabric SDK and Tools for Visual Studio 2015** is using the [Web Platform Installer](https://www.microsoft.com/web/downloads/platform.aspx).</span></span>  <span data-ttu-id="33e7a-106">Der Microsoft-Webplattform-Installer ist ein kostenloses Tool zum Optimieren des Herunterladens, Installierens und Aktualisierens einiger Komponenten der Microsoft-Webplattform, einschließlich Azure-Tools für Visual Studio 2015.</span><span class="sxs-lookup"><span data-stu-id="33e7a-106">The Microsoft Web Platform Installer is a free tool that streamlines downloading, installing, and updating some of the components of the Microsoft Web Platform, including Azure tools for Visual Studio 2015.</span></span>  <span data-ttu-id="33e7a-107">Diese SDKs können auch über die [Azure-Downloadseite](https://azure.microsoft.com/downloads/) als einzelne Komponenten heruntergeladen und installiert werden.</span><span class="sxs-lookup"><span data-stu-id="33e7a-107">These SDKs can also be downloaded and installed as individual components from the [Azure Downloads page](https://azure.microsoft.com/downloads/).</span></span> 

## <a name="using-the-web-platform-installer"></a><span data-ttu-id="33e7a-108">Verwenden des Webplattform-Installers</span><span class="sxs-lookup"><span data-stu-id="33e7a-108">Using the Web Platform Installer</span></span>

1. <span data-ttu-id="33e7a-109">Laden Sie diesen [Webplattform-Installer-Bootstrapper](https://www.microsoft.com/web/handlers/webpi.ashx?command=getinstallerredirect&appid=VWDOrVs2015AzurePack;MicrosoftAzure-ServiceFabric-VS2015) herunter, und führen Sie ihn aus.</span><span class="sxs-lookup"><span data-stu-id="33e7a-109">Download and run this [Web Platform Installer bootstrapper](https://www.microsoft.com/web/handlers/webpi.ashx?command=getinstallerredirect&appid=VWDOrVs2015AzurePack;MicrosoftAzure-ServiceFabric-VS2015).</span></span>  

2. <span data-ttu-id="33e7a-110">Der Bootstrapper installiert den Webplattform-Installer (bei Bedarf) und legt die neuesten Versionen der Elemente **Azure SDK für Visual Studio 2015** und **Service Fabric SDK und Tools für Visual Studio 2015** automatisch in Ihrer Liste *Zu installierende Elemente* ab.</span><span class="sxs-lookup"><span data-stu-id="33e7a-110">The bootstrapper will install Web Platform Installer (if needed) and automatically put the latest versions of the  **Azure SDK for Visual Studio 2015** and **Service Fabric SDK and Tools for Visual Studio 2015** items in your *Items to be installed* list.</span></span>  <span data-ttu-id="33e7a-111">Klicken Sie auf **Installieren**.</span><span class="sxs-lookup"><span data-stu-id="33e7a-111">Click **Install**.</span></span>

    ![Webplattform-Installer](media/dotnet-sdk-vs2015-install/webpi.png)

3. <span data-ttu-id="33e7a-113">Klicken Sie auf dem nächsten Bildschirm auf **Ich stimme zu**.</span><span class="sxs-lookup"><span data-stu-id="33e7a-113">On the next screen, click **I Accept**.</span></span>  <span data-ttu-id="33e7a-114">Der Webplattform-Installer beginnt mit dem Herunterladen und Installieren der ausgewählten Komponenten.</span><span class="sxs-lookup"><span data-stu-id="33e7a-114">Web PI will begin downloading and installing the components you selected.</span></span>

4. <span data-ttu-id="33e7a-115">Nachdem die Installation abgeschlossen ist, wird ein Bestätigungsfenster angezeigt.</span><span class="sxs-lookup"><span data-stu-id="33e7a-115">After the installation is finished, it will display a confirmation screen.</span></span>  <span data-ttu-id="33e7a-116">Klicken Sie auf **Fertig stellen**.</span><span class="sxs-lookup"><span data-stu-id="33e7a-116">Click **Finish**.</span></span>  <span data-ttu-id="33e7a-117">Sie können den Webplattform-Installer jetzt schließen.</span><span class="sxs-lookup"><span data-stu-id="33e7a-117">You can now close Web Platform Installer.</span></span>

## <a name="verifying-the-installation"></a><span data-ttu-id="33e7a-118">Überprüfen der Installation</span><span class="sxs-lookup"><span data-stu-id="33e7a-118">Verifying the installation</span></span>

1. <span data-ttu-id="33e7a-119">Klicken Sie in Visual Studio 2015 im Menü **Extras** auf **Erweiterungen und Updates...**.</span><span class="sxs-lookup"><span data-stu-id="33e7a-119">In Visual Studio 2015, click the **Tools** menu, and then click **Extensions and Updates...**.</span></span>

2. <span data-ttu-id="33e7a-120">Die angezeigte Liste enthält mehrere Azure-Tools, z.B. **Microsoft Azure App Service-Tools**, **Microsoft Azure Storage - verbundener Dienst** und **Service Fabric-Tools**.</span><span class="sxs-lookup"><span data-stu-id="33e7a-120">The displayed list will contain several Azure tools, such as **Microsoft Azure App Service Tools**, **Microsoft Azure Storage Connected Service**, and **Service Fabric Tools**.</span></span>

    ![Erweiterungen und Updates](media\dotnet-sdk-vs2015-install\ext-tools.png)

## <a name="next-steps"></a><span data-ttu-id="33e7a-122">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="33e7a-122">Next steps</span></span>

<span data-ttu-id="33e7a-123">[Erste Schritte mit den Azure-Bibliotheken für .NET](dotnet-sdk-azure-get-started.md)</span><span class="sxs-lookup"><span data-stu-id="33e7a-123">[Get started with Azure libraries for .NET](dotnet-sdk-azure-get-started.md).</span></span>
