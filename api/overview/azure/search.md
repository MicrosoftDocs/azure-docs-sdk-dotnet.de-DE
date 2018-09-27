---
title: Azure Search-Bibliotheken für .NET
description: Referenz für Azure Search-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: search
ms.openlocfilehash: cf622ccb59f10a5270c02fa76d7396345fbb1a9b
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190243"
---
# <a name="azure-search-libraries-for-net"></a>Azure Search-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure Search](https://docs.microsoft.com/azure/search/search-what-is-azure-search) ist ein vollständig verwalteter Cloudsuchdienst, der eine umfassende Suche in Daten in Web-, mobilen und Unternehmensanwendungen ermöglicht.

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Azure Search-Clientbibliothek zum Zugriff auf und zur Durchführung von Indizierungs- und Suchvorgängen in einem Suchdienst, Index, in Dokumenten oder einem anderen Objekt. Eine schrittweise Einführung finden Sie unter [Verwenden von Azure Search aus einer .NET-Anwendung](https://docs.microsoft.com/azure/search/search-howto-dotnet-sdk).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Search) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Search
```

```bash
dotnet add package Microsoft.Azure.Search
```

### <a name="code-example"></a>Codebeispiel

```csharp
/* Include these 'using' directives:
   using Microsoft.Azure.Search;
   using Microsoft.Azure.Search.Models;
*/

// A service endpoint and an api-key are required on a connection.
// Set them in a config file (not shown) and then connect to the client.
IConfigurationBuilder builder = new ConfigurationBuilder().AddJsonFile("appsettings.json");
IConfigurationRoot configuration = builder.Build();

SearchServiceClient serviceClient = CreateSearchServiceClient(configuration);

// Create an index named hotels
ISearchIndexClient indexClient = serviceClient.Indexes.GetClient("hotels");

```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/search/client)


## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Azure Search-Verwaltungsbibliothek, um einen Dienst bereitzustellen, API-Schlüssel zu verwalten und Ressourcen anzupassen. Die Dienstverwaltung weist eine Abhängigkeit vom Azure Resource Manager für Abonnenten- und Mandantenidentifikation auf. Authentifizierung und Anwendungsregistrierung bei Azure Active Directory ist in der Regel auch erforderlich, um den Workflow zu unterstützen. Eine Einführung zur Bereitstellung des Azure Search-Diensts finden Sie unter [How to use the Management REST API (Azure Search)](https://docs.microsoft.com/rest/api/searchmanagement/search-howto-management-rest-api) (Gewusst wie: Verwenden der Verwaltungs-REST-API [Azure Search]).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Search) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Search
```

```bash
dotnet add package Microsoft.Azure.Management.Search
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/search/management)

## <a name="samples"></a>Beispiele

 + [Azure Samples / search-dotnet-getting-started](https://github.com/Azure-Samples/search-dotnet-getting-started) (Azure-Beispiele / search-dotnet-getting-started)
 + [Azure Samples / Search-Dotnet-Management-api](https://github.com/Azure-Samples/search-dotnet-management-api) (Azure-Beispiele / Search-Dotnet-Management-api)

Weitere Suchbeispiele finden Sie auf Github im [Azure-Beispielrepository](https://github.com/Azure-Samples/).

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
