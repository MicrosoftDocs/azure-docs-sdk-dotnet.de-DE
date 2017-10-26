---
title: "Azure Active Directory-Bibliotheken für .NET"
description: "Referenz für Azure Active Directory-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, AAD, Active Directory
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: active-directory
ms.custom: devcenter, svc-overview
ms.openlocfilehash: aa20715fb62b1d4b714245c404f1a7c142caf586
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-active-directory-libraries-for-net"></a>Azure Active Directory-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Mit Azure Active Directory können Sie Benutzer anmelden und den Zugriff auf Anwendungen und APIs verwalten.

Informationen zu den ersten Schritten mit Azure Active Directory finden Sie unter [An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet).

## <a name="client-library"></a>Clientbibliothek

Verbinden und Authentifizieren von Benutzern bzw. Anwendungen über OAuth2, OpenID Connect, Active Directory Graph-API-Authentifizierung oder [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.IdentityModel.Clients.ActiveDirectory
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.IdentityModel.Clients.ActiveDirectory
```

### <a name="code-example"></a>Codebeispiel

Abrufen eines Zugriffstokens für eine Desktopanwendung.

```csharp
/* Include this "using" directive...
using Microsoft.IdentityModel.Clients.ActiveDirectory;
*/

AuthenticationResult result = null;
AuthenticationContext authContext = new AuthenticationContext("https://someauthority.com");
try
{
    result = await authContext.AcquireTokenAsync(graphResourceId, clientId, redirectUri, new PlatformParameters(PromptBehavior.Auto));
}
catch (AdalException ex)
{
    // An unexpected error occurred, or user canceled the sign in.
    if (ex.ErrorCode != "access_denied")
        MessageBox.Show(ex.Message);

    return;
}
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/activedirectory/client)

### <a name="samples"></a>Beispiele

* [Integrate Azure AD into a web application using OpenID Connect](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect) (Integrieren von Azure AD in eine Webanwendung mit OpenID Connect)
* [Calling a web api using an application identity](https://github.com/Azure-Samples/active-directory-dotnet-webapp-webapi-oauth2-appidentity) (Aufrufen einer Web-API mit einer Anwendungsidentität)
* [Authorization in a web app using Azure AD application roles &amp; role claims](https://github.com/Azure-Samples/active-directory-dotnet-webapp-roleclaims) (Autorisierung in einer Web-App mit Azure AD-Anwendungsrollen und -rollenansprüchen)

Untersuchen Sie die vollständige Sammlung der [Azure Active Directory-Codebeispiele](/azure/active-directory/develop/active-directory-code-samples).

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
