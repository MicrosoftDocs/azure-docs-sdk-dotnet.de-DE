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
# <a name="tutorials-for-authenticating-users-in-your-net-apps-running-on-azure"></a>Tutorials zum Authentifizieren von Benutzern in Ihren in Azure ausgeführten .NET-Anwendungen.

Die folgende Tabelle enthält Links zu ausführlichen Tutorials zum Authentifizieren von Benutzern und Sichern von in Azure ausgeführten .NET-Anwendungen.

Beispielquellcode finden Sie in der Liste der [Beispiele für Azure-Dienste](https://azure.microsoft.com/resources/samples/?platform=dotnet).

| | |
|---|---|
|**Active Directory**||
| [Hinzufügen von Azure Active Directory zu Ihrer Webanwendung mithilfe der Option „Verbundene Dienste“ in Visual Studio][5] | Verbinden einer Web-App mit Azure AD in Visual Studio |
| [An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD][1] | An- und Abmeldung von Benutzern bei Ihrer ASP.NET-App mit der ADAL-Bibliothek. |
| [Integrieren von Azure AD in einer Windows-Desktop-WPF-Anwendung][2]| Integrieren von Azure AD in einer Windows-Desktop-WPF-App mit ADAL. | 
| [Schützen einer Web-API mit Bearertoken aus Azure AD][3] | Schützen einer Web-API mit Bearer-Token aus Azure AD. |
|**Schlüsseltresor**||
| [Hinzufügen von Key Vault zu Ihrer Webanwendung mithilfe der Option „Verbundene Dienste“ in Visual Studio][6] | Verbinden einer Web-App mit Azure Key Vault in Visual Studio |
| [Verwenden des Azure-Schlüsseltresors aus einer Webanwendung][4] | Greifen Sie aus einer Azure Key Vault-Instanz auf einen geheimen Schlüssel zu, um diesen in der Webanwendung verwenden zu können. | 

[1]: /azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet
[2]: /azure/active-directory/develop/active-directory-devquickstarts-dotnet
[3]: /azure/active-directory/develop/active-directory-devquickstarts-webapi-dotnet
[4]: /azure/key-vault/key-vault-use-from-web-application
[5]: /azure/active-directory/develop/vs-active-directory-add-connected-service
[6]: /azure/key-vault/vs-key-vault-add-connected-service