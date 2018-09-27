---
title: Azure Active Directory-Bibliotheken für .NET
description: Referenz für Azure Active Directory-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: active-directory
ms.openlocfilehash: 0226f06546f7dc14b9ab3392008744754d47a19a
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190223"
---
# <a name="azure-active-directory-libraries-for-net"></a><span data-ttu-id="9b039-103">Azure Active Directory-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="9b039-103">Azure Active Directory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="9b039-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="9b039-104">Overview</span></span>

<span data-ttu-id="9b039-105">Mit Azure Active Directory können Sie Benutzer anmelden und den Zugriff auf Anwendungen und APIs verwalten.</span><span class="sxs-lookup"><span data-stu-id="9b039-105">Sign-on users and manage access to applications and APIs with Azure Active Directory.</span></span>

<span data-ttu-id="9b039-106">Informationen zu den ersten Schritten mit Azure Active Directory finden Sie unter [An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet).</span><span class="sxs-lookup"><span data-stu-id="9b039-106">To get started with Azure Active Directory, see [ASP.NET web app sign-in and sign-out with Azure AD](/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="9b039-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="9b039-107">Client library</span></span>

<span data-ttu-id="9b039-108">Verbinden und Authentifizieren von Benutzern bzw. Anwendungen über OAuth2, OpenID Connect, Active Directory Graph-API-Authentifizierung oder [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span><span class="sxs-lookup"><span data-stu-id="9b039-108">Connect and authenticate users or applications over OAuth2, OpenID Connect, Active Directory Graph API authentication or [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span></span>

<span data-ttu-id="9b039-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="9b039-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="9b039-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="9b039-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.IdentityModel.Clients.ActiveDirectory
```

#### <a name="net-core-cli"></a><span data-ttu-id="9b039-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="9b039-111">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.IdentityModel.Clients.ActiveDirectory
```

### <a name="code-example"></a><span data-ttu-id="9b039-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="9b039-112">Code Example</span></span>

<span data-ttu-id="9b039-113">Abrufen eines Zugriffstokens für eine Desktopanwendung.</span><span class="sxs-lookup"><span data-stu-id="9b039-113">Retrieve an access token for a desktop application.</span></span>

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
> [<span data-ttu-id="9b039-114">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="9b039-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/activedirectory/client)

### <a name="samples"></a><span data-ttu-id="9b039-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="9b039-115">Samples</span></span>

* <span data-ttu-id="9b039-116">[Integrate Azure AD into a web application using OpenID Connect](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect) (Integrieren von Azure AD in eine Webanwendung mit OpenID Connect)</span><span class="sxs-lookup"><span data-stu-id="9b039-116">[Use OpenID Connect to authenticate users from an Azure AD tenant](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect)</span></span>
* <span data-ttu-id="9b039-117">[Calling a web api using an application identity](https://github.com/Azure-Samples/active-directory-dotnet-webapp-webapi-oauth2-appidentity) (Aufrufen einer Web-API mit einer Anwendungsidentität)</span><span class="sxs-lookup"><span data-stu-id="9b039-117">[Use Oauth2 to call a web API with application permissions](https://github.com/Azure-Samples/active-directory-dotnet-webapp-webapi-oauth2-appidentity)</span></span>
* <span data-ttu-id="9b039-118">[Authorization in a web app using Azure AD application roles &amp; role claims](https://github.com/Azure-Samples/active-directory-dotnet-webapp-roleclaims) (Autorisierung in einer Web-App mit Azure AD-Anwendungsrollen und -rollenansprüchen)</span><span class="sxs-lookup"><span data-stu-id="9b039-118">[Use role-based access control (RBAC) in an application](https://github.com/Azure-Samples/active-directory-dotnet-webapp-roleclaims)</span></span>

<span data-ttu-id="9b039-119">Untersuchen Sie die vollständige Sammlung der [Azure Active Directory-Codebeispiele](/azure/active-directory/develop/active-directory-code-samples).</span><span class="sxs-lookup"><span data-stu-id="9b039-119">Explore the full collection of [Azure Active Directory code samples](/azure/active-directory/develop/active-directory-code-samples).</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
