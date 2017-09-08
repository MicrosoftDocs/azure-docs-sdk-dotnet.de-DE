---
title: "Azure Active Directory-Bibliotheken für .NET"
description: "Referenz für Azure Active Directory-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, AAD, Active Directory
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/17/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: adbe907888e49066b6d67a4fb26410a6f6b3b095
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-active-directory-libraries-for-net"></a><span data-ttu-id="5cbdb-104">Azure Active Directory-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="5cbdb-104">Azure Active Directory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="5cbdb-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="5cbdb-105">Overview</span></span>

<span data-ttu-id="5cbdb-106">Mit Azure Active Directory können Sie Benutzer anmelden und den Zugriff auf Anwendungen und APIs verwalten.</span><span class="sxs-lookup"><span data-stu-id="5cbdb-106">Sign-on users and manage access to applications and APIs with Azure Active Directory.</span></span>

<span data-ttu-id="5cbdb-107">Informationen zu den ersten Schritten mit Azure Active Directory finden Sie unter [An- und Abmeldung bei ASP.NET-Web-Apps mit Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet).</span><span class="sxs-lookup"><span data-stu-id="5cbdb-107">To get started with Azure Active Directory, see [ASP.NET web app sign-in and sign-out with Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-devquickstarts-webapp-dotnet).</span></span>

## <a name="client-library"></a><span data-ttu-id="5cbdb-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="5cbdb-108">Client library</span></span>

<span data-ttu-id="5cbdb-109">Verbinden und Authentifizieren von Benutzern bzw. Anwendungen über OAuth2, OpenID Connect, Active Directory Graph-API-Authentifizierung oder [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span><span class="sxs-lookup"><span data-stu-id="5cbdb-109">Connect and authenticate users or applications over OAuth2, OpenID Connect, Active Directory Graph API authentication or [SAML 2.0](https://docs.microsoft.com/azure/active-directory/develop/active-directory-saml-protocol-reference).</span></span>

<span data-ttu-id="5cbdb-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="5cbdb-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="5cbdb-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="5cbdb-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.IdentityModel.Clients.ActiveDirectory
```

#### <a name="net-core-cli"></a><span data-ttu-id="5cbdb-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="5cbdb-112">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.IdentityModel.Clients.ActiveDirectory
```

### <a name="code-example"></a><span data-ttu-id="5cbdb-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="5cbdb-113">Code Example</span></span>

<span data-ttu-id="5cbdb-114">Abrufen eines Zugriffstokens für eine Desktopanwendung.</span><span class="sxs-lookup"><span data-stu-id="5cbdb-114">Retrieve an access token for a desktop application.</span></span>

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
> [<span data-ttu-id="5cbdb-115">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="5cbdb-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/activedirectory/client)

### <a name="samples"></a><span data-ttu-id="5cbdb-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="5cbdb-116">Samples</span></span>

* [<span data-ttu-id="5cbdb-117">Integrate Azure AD into a web application using OpenID Connect</span><span class="sxs-lookup"><span data-stu-id="5cbdb-117">Use OpenID Connect to authenticate users from an Azure AD tenant</span></span>](https://github.com/Azure-Samples/active-directory-dotnet-webapp-openidconnect) (Integrieren von Azure AD in eine Webanwendung mit OpenID Connect)
* [<span data-ttu-id="5cbdb-118">Calling a web api using an application identity</span><span class="sxs-lookup"><span data-stu-id="5cbdb-118">Use Oauth2 to call a web API with application permissions</span></span>](https://github.com/Azure-Samples/active-directory-dotnet-webapp-webapi-oauth2-appidentity) (Aufrufen einer Web-API mit einer Anwendungsidentität)
* [<span data-ttu-id="5cbdb-119">Authorization in a web app using Azure AD application roles & role claims</span><span class="sxs-lookup"><span data-stu-id="5cbdb-119">Use role-based access control (RBAC) in an application</span></span>](https://github.com/Azure-Samples/active-directory-dotnet-webapp-roleclaims) (Autorisierung in einer Web-App mit Azure AD-Anwendungsrollen und -rollenansprüchen)

<span data-ttu-id="5cbdb-120">Untersuchen Sie die vollständige Sammlung der [Azure Active Directory-Codebeispiele](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-code-samples).</span><span class="sxs-lookup"><span data-stu-id="5cbdb-120">Explore the full collection of [Azure Active Directory code samples](https://docs.microsoft.com/en-us/azure/active-directory/develop/active-directory-code-samples).</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
