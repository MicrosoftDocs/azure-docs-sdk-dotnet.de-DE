---
title: "Azure Search-Bibliotheken für .NET"
description: "Referenz für Azure Search-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Search
author: spboyer
ms.author: casoper
manager: douge
ms.date: 07/10/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 5330e0642bc27c97c4acc0857d4b92e6fc2a027c
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-search-libraries-for-net"></a><span data-ttu-id="815b7-104">Azure Search-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="815b7-104">Azure Search libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="815b7-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="815b7-105">Overview</span></span>

<span data-ttu-id="815b7-106">[Azure Search](https://docs.microsoft.com/azure/search/search-what-is-azure-search) ist ein vollständig verwalteter Cloudsuchdienst, der eine umfassende Suche in Daten in Web-, mobilen und Unternehmensanwendungen ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="815b7-106">[Azure Search](https://docs.microsoft.com/azure/search/search-what-is-azure-search) is a fully managed cloud search service that provides a rich search experience over data in web, mobile, and enterprise applications.</span></span>

## <a name="client-library"></a><span data-ttu-id="815b7-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="815b7-107">Client library</span></span>

<span data-ttu-id="815b7-108">Verwenden Sie die Azure Search-Clientbibliothek zum Zugriff auf und zur Durchführung von Indizierungs- und Suchvorgängen in einem Suchdienst, Index, in Dokumenten oder einem anderen Objekt.</span><span class="sxs-lookup"><span data-stu-id="815b7-108">Use the Azure Search client library to access and execute indexing and search operations on a search service, index, documents, or other object.</span></span> <span data-ttu-id="815b7-109">Eine schrittweise Einführung finden Sie unter [Verwenden von Azure Search aus einer .NET-Anwendung](https://docs.microsoft.com/azure/search/search-howto-dotnet-sdk).</span><span class="sxs-lookup"><span data-stu-id="815b7-109">For a step-by-step introduction, see [How to use Azure Search from a .NET application](https://docs.microsoft.com/azure/search/search-howto-dotnet-sdk).</span></span>

<span data-ttu-id="815b7-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Search) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="815b7-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Search) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="815b7-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="815b7-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Search
```

```bash
dotnet add package Microsoft.Azure.Search
```

### <a name="code-example"></a><span data-ttu-id="815b7-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="815b7-112">Code Example</span></span>

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
> [<span data-ttu-id="815b7-113">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="815b7-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/search/client)


## <a name="management-library"></a><span data-ttu-id="815b7-114">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="815b7-114">Management library</span></span>

<span data-ttu-id="815b7-115">Verwenden Sie die Azure Search-Verwaltungsbibliothek, um einen Dienst bereitzustellen, API-Schlüssel zu verwalten und Ressourcen anzupassen.</span><span class="sxs-lookup"><span data-stu-id="815b7-115">Use the Azure Search management library to provision a service, manage api-keys, and adjust resources.</span></span> <span data-ttu-id="815b7-116">Die Dienstverwaltung weist eine Abhängigkeit vom Azure Resource Manager für Abonnenten- und Mandantenidentifikation auf.</span><span class="sxs-lookup"><span data-stu-id="815b7-116">Service management has a dependency on Azure Resource Manager for subscriber and tenant identification.</span></span> <span data-ttu-id="815b7-117">Authentifizierung und Anwendungsregistrierung bei Azure Active Directory ist in der Regel auch erforderlich, um den Workflow zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="815b7-117">Typically, authentication and application registration with Azure Active Directory is also necessary to support the workflow.</span></span> <span data-ttu-id="815b7-118">Eine Einführung zur Bereitstellung des Azure Search-Diensts finden Sie unter [How to use the Management REST API (Azure Search)](https://docs.microsoft.com/rest/api/searchmanagement/search-howto-management-rest-api) (Gewusst wie: Verwenden der Verwaltungs-REST-API [Azure Search]).</span><span class="sxs-lookup"><span data-stu-id="815b7-118">For an introduction to Azure Search service provisioning, see [How to use the Management REST API](https://docs.microsoft.com/rest/api/searchmanagement/search-howto-management-rest-api).</span></span>

<span data-ttu-id="815b7-119">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Search) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="815b7-119">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Search) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="815b7-120">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="815b7-120">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Search
```

```bash
dotnet add package Microsoft.Azure.Management.Search
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="815b7-121">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="815b7-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/search/management)

## <a name="samples"></a><span data-ttu-id="815b7-122">Beispiele</span><span class="sxs-lookup"><span data-stu-id="815b7-122">Samples</span></span>

 + <span data-ttu-id="815b7-123">[Azure Samples / search-dotnet-getting-started](https://github.com/Azure-Samples/search-dotnet-getting-started) (Azure-Beispiele / search-dotnet-getting-started)</span><span class="sxs-lookup"><span data-stu-id="815b7-123">[Azure Samples / search-dotnet-getting-started](https://github.com/Azure-Samples/search-dotnet-getting-started)</span></span>
 + <span data-ttu-id="815b7-124">[Azure Samples / Search-Dotnet-Management-api](https://github.com/Azure-Samples/search-dotnet-management-api) (Azure-Beispiele / Search-Dotnet-Management-api)</span><span class="sxs-lookup"><span data-stu-id="815b7-124">[Azure Samples / search-dotnet-management-api](https://github.com/Azure-Samples/search-dotnet-management-api)</span></span>

<span data-ttu-id="815b7-125">Weitere Suchbeispiele finden Sie auf Github im [Azure-Beispielrepository](https://github.com/Azure-Samples/).</span><span class="sxs-lookup"><span data-stu-id="815b7-125">Find more search samples in the [Azure samples repository](https://github.com/Azure-Samples/) on Github.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
