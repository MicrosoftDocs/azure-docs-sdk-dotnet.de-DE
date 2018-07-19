---
title: Azure Data Lake Store-Bibliotheken für .NET
description: Referenz für Azure Data Lake Store-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Data Lake Store
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: data-lake-store
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 7bbc8c6c5a71d16372d7ab756a5188d90503f52a
ms.sourcegitcommit: 512e031ead61a578ac96835c8ea01829842740bf
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/18/2018
ms.locfileid: "39116686"
---
# <a name="azure-data-lake-store-libraries-for-net"></a><span data-ttu-id="de52f-104">Azure Data Lake Store-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="de52f-104">Azure Data Lake Store libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="de52f-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="de52f-105">Overview</span></span>

<span data-ttu-id="de52f-106">Azure Data Lake-Speicher ist ein unternehmensweites riesiges Repository für Big Data-Analyseworkloads.</span><span class="sxs-lookup"><span data-stu-id="de52f-106">Azure Data Lake Store is an enterprise-wide hyper-scale repository for big data analytic workloads.</span></span> <span data-ttu-id="de52f-107">Azure Data Lake bietet Ihnen die Möglichkeit, Daten von beliebiger Größe, Art und Erfassungsgeschwindigkeit zur Durchführung operativer und explorativer Analysen an einem einzigen Ort zu erfassen.</span><span class="sxs-lookup"><span data-stu-id="de52f-107">Azure Data Lake enables you to capture data of any size, type, and ingestion speed in one single place for operational and exploratory analytics.</span></span>

<span data-ttu-id="de52f-108">Weitere Informationen finden Sie in der [Übersicht über Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).</span><span class="sxs-lookup"><span data-stu-id="de52f-108">To learn more, see [Overview of Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).</span></span>

## <a name="client-library"></a><span data-ttu-id="de52f-109">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="de52f-109">Client library</span></span>

<span data-ttu-id="de52f-110">Verwenden Sie die Clientbibliothek zum Ausführen von Dateisystemvorgängen in Data Lake Store, etwa zum Erstellen von Ordnern in einem Data Lake Store-Konto und Hochladen bzw. Herunterladen von Dateien.</span><span class="sxs-lookup"><span data-stu-id="de52f-110">Use the client library to perform filesystem operations on Data Lake Store, such as creating folders in a Data Lake Store account, uploading files, and downloading files.</span></span>  <span data-ttu-id="de52f-111">Ein vollständiges Tutorial zur Verwendung von Data Lake Store mit .NET finden Sie unter [Dateisystemvorgänge in Azure Data Lake Store per .NET SDK](/azure/data-lake-store/data-lake-store-data-operations-net-sdk).</span><span class="sxs-lookup"><span data-stu-id="de52f-111">For a full tutorial on using Data Lake Store with .NET, see [Filesystem operations on Azure Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-data-operations-net-sdk).</span></span>

<span data-ttu-id="de52f-112">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="de52f-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="de52f-113">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="de52f-113">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.DataLake.Store
```
### <a name="authentication"></a><span data-ttu-id="de52f-114">Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="de52f-114">Authentication</span></span>

* <span data-ttu-id="de52f-115">Informationen zur Authentifizierung von Endbenutzern für Ihre Anwendung finden Sie unter [End-user authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-end-user-authenticate-net-sdk) (Authentifizierung von Endbenutzern mit Data Lake Store per .NET SDK).</span><span class="sxs-lookup"><span data-stu-id="de52f-115">For end-user authentication for your application, see [End-user authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-end-user-authenticate-net-sdk).</span></span>
* <span data-ttu-id="de52f-116">Informationen zur Dienst-zu-Dienst-Authentifizierung für Ihre Anwendung finden Sie unter [Service-to-service authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-service-to-service-authenticate-net-sdk) (Dienst-zu-Dienst-Authentifizierung mit Data Lake Store per .NET SDK).</span><span class="sxs-lookup"><span data-stu-id="de52f-116">For service-to-service authentication for your application, see [Service-to-service authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-service-to-service-authenticate-net-sdk).</span></span>

### <a name="code-example"></a><span data-ttu-id="de52f-117">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="de52f-117">Code Example</span></span>

<span data-ttu-id="de52f-118">Mit dem folgenden Codeausschnitt wird das Data Lake Store-Dateisystem-Clientobjekt erstellt, das zum Ausführen von Anforderungen für den Dienst genutzt wird.</span><span class="sxs-lookup"><span data-stu-id="de52f-118">The following snippet creates the Data Lake Store filesystem client object, which is used to issue requests to the service.</span></span>

```csharp
// Create client objects
AdlsClient client = AdlsClient.CreateClient(_adlsAccountName, adlCreds);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="de52f-119">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="de52f-119">Explore the client APIs</span></span>](/dotnet/api/overview/azure/datalakestore/client)


## <a name="management-library"></a><span data-ttu-id="de52f-120">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="de52f-120">Management library</span></span>

<span data-ttu-id="de52f-121">Verwenden Sie die Verwaltungsbibliothek, um die Verbindung mit Ihren Big Data-Repositorys herzustellen und sie zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="de52f-121">Use the management library to connect to and manage your big data repositories.</span></span>

<span data-ttu-id="de52f-122">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="de52f-122">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="de52f-123">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="de52f-123">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Store
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="de52f-124">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="de52f-124">Explore the client APIs</span></span>](/dotnet/api/overview/azure/datalakestore/management)


## <a name="samples"></a><span data-ttu-id="de52f-125">Beispiele</span><span class="sxs-lookup"><span data-stu-id="de52f-125">Samples</span></span>

* [<span data-ttu-id="de52f-126">Azure Data Lake-.NET-Client-Beispiel</span><span class="sxs-lookup"><span data-stu-id="de52f-126">Azure Data Lake .NET Client Example</span></span>](https://azure.microsoft.com/resources/samples/data-lake-dotnet-client/)

<span data-ttu-id="de52f-127">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="de52f-127">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
