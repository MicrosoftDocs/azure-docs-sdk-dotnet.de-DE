---
title: Azure .NET-Speicher-APIs
description: Referenz für Azure Storage-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Speicher, Blob
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: storage
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 8f6e0414b54698d0a1dbe3d4c074456a6ad7b7be
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2018
---
# <a name="azure-storage-apis-for-net"></a><span data-ttu-id="a38e3-104">Azure Storage-APIs für .NET</span><span class="sxs-lookup"><span data-stu-id="a38e3-104">Azure Storage APIs for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="a38e3-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="a38e3-105">Overview</span></span>

<span data-ttu-id="a38e3-106">Lesen und schreiben Sie mit [Azure Storage](https://review.docs.microsoft.com/azure/storage/storage-introduction) Dateien, Blob- bzw. Objektdaten, Schlüssel-Wert-Paare und Nachrichten aus Ihren .NET-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="a38e3-106">Read and write files, blob (object) data, key-value pairs, and messages from your .NET applications with [Azure Storage](https://review.docs.microsoft.com/azure/storage/storage-introduction).</span></span>

<span data-ttu-id="a38e3-107">Informationen zu den ersten Schritten mit Azure Storage finden Sie unter [Erste Schritte mit Azure Blob Storage mithilfe von .NET](/azure/storage/storage-dotnet-how-to-use-blobs).</span><span class="sxs-lookup"><span data-stu-id="a38e3-107">To get started with Azure Storage, see [Get started with Azure Blob storage using .NET](/azure/storage/storage-dotnet-how-to-use-blobs).</span></span>

## <a name="client-library"></a><span data-ttu-id="a38e3-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="a38e3-108">Client library</span></span>

<span data-ttu-id="a38e3-109">Verwenden Sie [Verbindungszeichenfolgen](/azure/storage/storage-create-storage-account#manage-your-storage-account), um eine Verbindung mit einem Azure Storage-Konto herzustellen. Nutzen Sie anschließend die Klassen und Methoden der Clientbibliotheken, um mit Blob-, Tabellen-, Datei- oder Warteschlangenspeicher zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="a38e3-109">Use [connection strings](/azure/storage/storage-create-storage-account#manage-your-storage-account) to connect to an Azure Storage account, then use the client libraries' classes and methods to work with blob, table, file, or queue storage.</span></span>

<span data-ttu-id="a38e3-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/WindowsAzure.Storage) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="a38e3-110">Install the [NuGet package](https://www.nuget.org/packages/WindowsAzure.Storage) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="a38e3-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="a38e3-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package WindowsAzure.Storage
```

### <a name="net-core-cli"></a><span data-ttu-id="a38e3-112">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="a38e3-112">.NET Core CLI</span></span>

```bash
dotnet add package WindowsAzure.Storage
```

### <a name="code-example"></a><span data-ttu-id="a38e3-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="a38e3-113">Code Example</span></span>

<span data-ttu-id="a38e3-114">In diesem Beispiel wird in einem vorhandenen Speicherkonto ein neues Blob in einem neuen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="a38e3-114">This example creates a new blob to a new container in an existing storage account.</span></span>

```csharp
/* Include these "using" directives...
using Microsoft.WindowsAzure.Storage;
using Microsoft.WindowsAzure.Storage.Blob;
*/

string storageConnectionString = "DefaultEndpointsProtocol=https;"
    + "AccountName=[Storage Account Name]"
    + ";AccountKey=[Storage Account Key]"
    + ";EndpointSuffix=core.windows.net";

CloudStorageAccount account = CloudStorageAccount.Parse(storageConnectionString);
CloudBlobClient serviceClient = account.CreateCloudBlobClient();

// Create container. Name must be lower case.
Console.WriteLine("Creating container...");
var container = serviceClient.GetContainerReference("mycontainer");
container.CreateIfNotExistsAsync().Wait();

// write a blob to the container
CloudBlockBlob blob = container.GetBlockBlobReference("helloworld.txt");
blob.UploadTextAsync("Hello, World!").Wait();
```

> [!div class="nextstepactions"]
> [<span data-ttu-id="a38e3-115">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="a38e3-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/storage/client)

## <a name="management-apis"></a><span data-ttu-id="a38e3-116">Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="a38e3-116">Management APIs</span></span>

<span data-ttu-id="a38e3-117">Erstellen und verwalten Sie Azure Storage-Konten und -Verbindungsschlüssel mit der Verwaltungs-API.</span><span class="sxs-lookup"><span data-stu-id="a38e3-117">Create and manage Azure Storage accounts and connection keys with the management API.</span></span>

<span data-ttu-id="a38e3-118">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="a38e3-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="a38e3-119">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="a38e3-119">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Storage.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="a38e3-120">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="a38e3-120">.NET Core CLI</span></span>

````bash
dotnet add package Microsoft.Azure.Management.Storage.Fluent
````

### <a name="code-example"></a><span data-ttu-id="a38e3-121">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="a38e3-121">Code Example</span></span>

<span data-ttu-id="a38e3-122">In diesem Beispiel wird ein Speicherkonto erstellt.</span><span class="sxs-lookup"><span data-stu-id="a38e3-122">This example creates a storage account.</span></span>

```csharp
/* Include this "using" directive...
using Microsoft.Azure.Management.Storage.Fluent
*/

IStorageAccount storage = azure.StorageAccounts.Define(storageAccountName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .Create();
```

> [!div class="nextstepactions"]
> [<span data-ttu-id="a38e3-123">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="a38e3-123">Explore the management APIs</span></span>](/dotnet/api/overview/azure/storage/management)

## <a name="samples"></a><span data-ttu-id="a38e3-124">Beispiele</span><span class="sxs-lookup"><span data-stu-id="a38e3-124">Samples</span></span>

* [<span data-ttu-id="a38e3-125">Erste Schritte mit Azure Blob Storage in .NET</span><span class="sxs-lookup"><span data-stu-id="a38e3-125">Get started with Azure Blob Storage in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-blob-dotnet-getting-started/) 
* [<span data-ttu-id="a38e3-126">Erste Schritte mit Azure Queue Storage in .NET</span><span class="sxs-lookup"><span data-stu-id="a38e3-126">Get started with Azure Queue Storage in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-queue-dotnet-getting-started/)

<span data-ttu-id="a38e3-127">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage) von Beispielen für Azure Storage an.</span><span class="sxs-lookup"><span data-stu-id="a38e3-127">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage) of Azure Storage samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package