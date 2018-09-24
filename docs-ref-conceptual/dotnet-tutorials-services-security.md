---
title: .NET-Tutorials zum Sichern Ihrer Azure-Apps
description: Tutorials für Anwendungssicherheit und Identitätsverwaltung in Ihren in Azure ausgeführten .NET-Anwendungen.
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 88ecfc69fbd57becf1adf1163a063c0d2bb086a8
ms.sourcegitcommit: 61638b504b6c4d96b357894835c80c2680a99fe6
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/17/2018
ms.locfileid: "45750588"
---
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a><span data-ttu-id="d6d46-103">Tutorials zum Authentifizieren von Benutzern in Ihren in Azure ausgeführten .NET-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="d6d46-103">Tutorials for authenticating users in your .NET apps running on Azure</span></span>

<span data-ttu-id="d6d46-104">Die folgende Tabelle enthält Links zu ausführlichen Tutorials zum Authentifizieren von Benutzern und Sichern von in Azure ausgeführten .NET-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="d6d46-104">The following table links to in-depth tutorials for authenticating users and securing .NET applications running on Azure.</span></span>

<span data-ttu-id="d6d46-105">Beispielquellcode finden Sie in der Liste der [Beispiele für Azure-Dienste](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span><span class="sxs-lookup"><span data-stu-id="d6d46-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>

| | |
|---|---|
|<span data-ttu-id="d6d46-106">**Active Directory**</span><span class="sxs-lookup"><span data-stu-id="d6d46-106">**Active Directory**</span></span>||
| <span data-ttu-id="d6d46-107">[Hinzufügen von Azure Active Directory zu Ihrer Webanwendung mithilfe der Option „Verbundene Dienste“ in Visual Studio][5]</span><span class="sxs-lookup"><span data-stu-id="d6d46-107">[Add Azure Active Directory to your web application by using Visual Studio Connected Services][5]</span></span> | <span data-ttu-id="d6d46-108">Verbinden einer Web-App mit Azure AD in Visual Studio</span><span class="sxs-lookup"><span data-stu-id="d6d46-108">Connect a web app to Azure AD in Visual Studio</span></span> |
| <span data-ttu-id="d6d46-109">[An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD][1]</span><span class="sxs-lookup"><span data-stu-id="d6d46-109">[Web app sign-in and sign-out with Azure AD][1]</span></span> | <span data-ttu-id="d6d46-110">An- und Abmeldung von Benutzern bei Ihrer ASP.NET-App mit der ADAL-Bibliothek.</span><span class="sxs-lookup"><span data-stu-id="d6d46-110">Sign users in and out of your ASP.NET with the ADAL library.</span></span> |
| <span data-ttu-id="d6d46-111">[Integrieren von Azure AD in einer Windows-Desktop-WPF-Anwendung][2]</span><span class="sxs-lookup"><span data-stu-id="d6d46-111">[Desktop application authentication with Azure AD][2]</span></span>| <span data-ttu-id="d6d46-112">Integrieren von Azure AD in einer Windows-Desktop-WPF-App mit ADAL.</span><span class="sxs-lookup"><span data-stu-id="d6d46-112">Integrate Azure AD into a Windows Desktop WPF app using ADAL.</span></span> | 
| <span data-ttu-id="d6d46-113">[Schützen einer Web-API mit Bearertoken aus Azure AD][3]</span><span class="sxs-lookup"><span data-stu-id="d6d46-113">[Web API authentication with Azure AD][3]</span></span> | <span data-ttu-id="d6d46-114">Schützen einer Web-API mit Bearer-Token aus Azure AD.</span><span class="sxs-lookup"><span data-stu-id="d6d46-114">Protect a web API using bearer tokens from Azure AD.</span></span> |
|<span data-ttu-id="d6d46-115">**Schlüsseltresor**</span><span class="sxs-lookup"><span data-stu-id="d6d46-115">**Key Vault**</span></span>||
| <span data-ttu-id="d6d46-116">[Hinzufügen von Key Vault zu Ihrer Webanwendung mithilfe der Option „Verbundene Dienste“ in Visual Studio][6]</span><span class="sxs-lookup"><span data-stu-id="d6d46-116">[Add Key Vault to your web application by using Visual Studio Connected Services][6]</span></span> | <span data-ttu-id="d6d46-117">Verbinden einer Web-App mit Azure Key Vault in Visual Studio</span><span class="sxs-lookup"><span data-stu-id="d6d46-117">Connect a web app to Azure Key Vault in Visual Studio</span></span> |
| <span data-ttu-id="d6d46-118">[Verwenden des Azure-Schlüsseltresors aus einer Webanwendung][4]</span><span class="sxs-lookup"><span data-stu-id="d6d46-118">[Use Azure Key Vault from a Web Application][4]</span></span> | <span data-ttu-id="d6d46-119">Greifen Sie aus einer Azure Key Vault-Instanz auf einen geheimen Schlüssel zu, um diesen in der Webanwendung verwenden zu können.</span><span class="sxs-lookup"><span data-stu-id="d6d46-119">Access a secret from an Azure Key Vault so that it can be used in your web application.</span></span> | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application
[5]: /azure/active-directory/develop/vs-active-directory-add-connected-service
[6]: /azure/key-vault/vs-key-vault-add-connected-service