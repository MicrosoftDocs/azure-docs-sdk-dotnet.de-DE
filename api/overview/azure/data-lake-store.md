---
title: "Azure Data Lake Store-Bibliotheken für .NET"
description: "Referenz für Azure Data Lake Store-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Data Lake Store
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/18/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: 18746d745d64065a3d92215e704bce575130bdb0
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-data-lake-store-libraries-for-net"></a><span data-ttu-id="4203f-104">Azure Data Lake Store-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="4203f-104">Azure Data Lake Store libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4203f-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="4203f-105">Overview</span></span>

<span data-ttu-id="4203f-106">Azure Data Lake-Speicher ist ein unternehmensweites riesiges Repository für Big Data-Analyseworkloads.</span><span class="sxs-lookup"><span data-stu-id="4203f-106">Azure Data Lake Store is an enterprise-wide hyper-scale repository for big data analytic workloads.</span></span> <span data-ttu-id="4203f-107">Azure Data Lake bietet Ihnen die Möglichkeit, Daten von beliebiger Größe, Art und Erfassungsgeschwindigkeit zur Durchführung operativer und explorativer Analysen an einem einzigen Ort zu erfassen.</span><span class="sxs-lookup"><span data-stu-id="4203f-107">Azure Data Lake enables you to capture data of any size, type, and ingestion speed in one single place for operational and exploratory analytics.</span></span>

<span data-ttu-id="4203f-108">Weitere Informationen finden Sie in der [Übersicht über Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).</span><span class="sxs-lookup"><span data-stu-id="4203f-108">To learn more, see [Overview of Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="4203f-109">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="4203f-109">Management library</span></span>

<span data-ttu-id="4203f-110">Verwenden Sie die Verwaltungsbibliothek, um die Verbindung mit Ihren Big Data-Repositorys herzustellen und sie zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="4203f-110">Use the management library to connect to and manage your big data repositories.</span></span>

<span data-ttu-id="4203f-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="4203f-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4203f-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="4203f-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Store
```

### <a name="code-example"></a><span data-ttu-id="4203f-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="4203f-113">Code Example</span></span>

<span data-ttu-id="4203f-114">In diesem Beispiel erfolgt eine Authentifizierung bei einem Analytics-Konto und -speicher, und die erforderlichen Clients für die Verwaltung werden erstellt.</span><span class="sxs-lookup"><span data-stu-id="4203f-114">This example authenticates to an analytics account and store and creates the clients necessary for management.</span></span>

```csharp
/*
using AdlClient
using AdlClient.Models 
*/

// Setup authentication 
Authentication auth = new Authentication("microsoft.onmicrosoft.com"); // change this to YOUR tenant
auth.Authenticate();

// Identify the accounts
StoreAccountRef adls_account = new StoreAccountRef(subscriptionId, resourceGroup, userName);

// Create the clients
AzureClient az = new AzureClient(auth);
StoreClient adls = new StoreClient(auth, adls_account);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="4203f-115">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="4203f-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datalakestore/management)

## <a name="samples"></a><span data-ttu-id="4203f-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="4203f-116">Samples</span></span>

* [<span data-ttu-id="4203f-117">Azure Data Lake-.NET-Client-Beispiel</span><span class="sxs-lookup"><span data-stu-id="4203f-117">Azure Data Lake .NET Client Example</span></span>](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

<span data-ttu-id="4203f-118">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="4203f-118">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-add-package
