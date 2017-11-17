---
title: "Azure Data Lake Analytics-Bibliotheken für .NET"
description: "Referenz für Azure Data Lake Analytics-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Data Lake Analytics
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: data-lake-analytics
ms.custom: devcenter, svc-overview
ms.openlocfilehash: aa99608ec5568450a90cc2b93c3f1c5d0e38bfb1
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-data-lake-analytics-libraries-for-net"></a><span data-ttu-id="02a12-104">Azure Data Lake Analytics-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="02a12-104">Azure Data Lake Analytics libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="02a12-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="02a12-105">Overview</span></span>

<span data-ttu-id="02a12-106">Azure Data Lake Analytics ist ein bedarfsgesteuerter Dienst für Analyseaufträge zum Vereinfachen von Big Data-Analysen.</span><span class="sxs-lookup"><span data-stu-id="02a12-106">Azure Data Lake Analytics is an on-demand analytics job service to simplify big data analytics.</span></span>

<span data-ttu-id="02a12-107">Weitere Informationen finden Sie in der [Übersicht über Microsoft Azure Data Lake Analytics](/azure/data-lake-analytics/data-lake-analytics-overview).</span><span class="sxs-lookup"><span data-stu-id="02a12-107">To learn more, see [Overview of Microsoft Azure Data Lake Analytics](/azure/data-lake-analytics/data-lake-analytics-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="02a12-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="02a12-108">Management library</span></span>

<span data-ttu-id="02a12-109">Verwenden Sie die Verwaltungsbibliothek zum Herstellen einer Verbindung mit dem Dienst und Verwalten von Analytics-Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="02a12-109">Use the management library to connect to the service and manage analytics jobs.</span></span>

<span data-ttu-id="02a12-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Analytics) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="02a12-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Analytics) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="02a12-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="02a12-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Analytics
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Analytics
```

### <a name="code-example"></a><span data-ttu-id="02a12-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="02a12-112">Code Example</span></span>

<span data-ttu-id="02a12-113">In diesem Beispiel werden die Clients zum Herstellen einer Verbindung mit einem Analytics-Konto und zu dessen Verwaltung erstellt.</span><span class="sxs-lookup"><span data-stu-id="02a12-113">This example creates the clients to connect with and manage the analytics account.</span></span>

```csharp
/*
using AdlClient 
*/

// Setup authentication for this demo
Authentication auth = new Authentication("microsoft.onmicrosoft.com"); // change this to YOUR tenant
auth.Authenticate();

// Identify the accounts
AnalyticsAccountRef adla_account = new AnalyticsAccountRef(subscriptionId, resourceGroup, userName);

// Create the clients
AzureClient az = new AzureClient(auth);
AnalyticsClient adla = new AnalyticsClient(auth, adla_account);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="02a12-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="02a12-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datalakeanalytics/management)

## <a name="samples"></a><span data-ttu-id="02a12-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="02a12-115">Samples</span></span>
* [<span data-ttu-id="02a12-116">Azure Data Lake-.NET-Client-Beispiel</span><span class="sxs-lookup"><span data-stu-id="02a12-116">Azure Data Lake .NET Client Example</span></span>](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

<span data-ttu-id="02a12-117">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="02a12-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
