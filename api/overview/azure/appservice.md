---
title: "Azure App Service-Bibliotheken für .NET"
description: "Referenz für Azure App Service-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Web-Apps, App Service, mobile Apps, ASP.NET
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: app-service
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 356a86e8fa70512b6f31c6e237173a74d1c6f60a
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2018
---
# <a name="azure-app-service-libraries-for-net"></a>Azure App Service-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure App Service](/azure/app-service/app-service-value-prop-what-is) ermöglicht Ihnen das Bereitstellen und Skalieren von Websites, Webanwendungen, Diensten und REST-APIs.

## <a name="management-api"></a>Verwaltungs-API

Sie können Elemente, die in Azure App Service gehostet werden, mit der Verwaltungs-API bereitstellen, verwalten und skalieren.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.AppService.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].


#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.AppService.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.AppService.Fluent
```

### <a name="code-example"></a>Codebeispiel

Erstellen Sie eine neue Web-App.

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
using Microsoft.Azure.Management.AppService.Fluent;
*/

IWebApp app1 = azure.WebApps
    .Define("MyUniqueWebAddress")
    .WithRegion(Region.USWest)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewWindowsPlan(PricingTier.StandardS1)
    .Create();
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/appservice/management)

### <a name="samples"></a>Beispiele

* [Verwalten Ihrer Web-Apps mit dem .NET SDK für Azure](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-manage/)
* [ASP.NET-Beispiel für Azure App Service](https://azure.microsoft.com/resources/samples/app-service-web-dotnet-get-started/)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=app%20service) von Beispielen für Azure App Service an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package