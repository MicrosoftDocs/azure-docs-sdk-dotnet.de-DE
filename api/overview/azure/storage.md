---
title: Azure .NET-Speicher-APIs
description: Referenz für Azure Storage-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: storage
ms.openlocfilehash: 2f278f0e3cb10d11190d529f427fa64040ee8b1d
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47189973"
---
# <a name="azure-storage-apis-for-net"></a><span data-ttu-id="338d6-103">Azure Storage-APIs für .NET</span><span class="sxs-lookup"><span data-stu-id="338d6-103">Azure Storage APIs for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="338d6-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="338d6-104">Overview</span></span>

<span data-ttu-id="338d6-105">Lesen und schreiben Sie mit [Azure Storage](https://docs.microsoft.com/azure/storage/storage-introduction) Dateien, Blob- bzw. Objektdaten, Schlüssel-Wert-Paare und Nachrichten aus Ihren .NET-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="338d6-105">Read and write files, blob (object) data, key-value pairs, and messages from your .NET applications with [Azure Storage](https://docs.microsoft.com/azure/storage/storage-introduction).</span></span>

<span data-ttu-id="338d6-106">Informationen zu den ersten Schritten mit Azure Storage finden Sie unter [Erste Schritte mit Azure Blob Storage mithilfe von .NET](/azure/storage/storage-dotnet-how-to-use-blobs).</span><span class="sxs-lookup"><span data-stu-id="338d6-106">To get started with Azure Storage, see [Get started with Azure Blob storage using .NET](/azure/storage/storage-dotnet-how-to-use-blobs).</span></span>

## <a name="client-library"></a><span data-ttu-id="338d6-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="338d6-107">Client library</span></span>

<span data-ttu-id="338d6-108">Verwenden Sie [Verbindungszeichenfolgen](/azure/storage/storage-create-storage-account#manage-your-storage-account), um eine Verbindung mit einem Azure Storage-Konto herzustellen. Nutzen Sie anschließend die Klassen und Methoden der Clientbibliotheken, um mit Blob-, Tabellen-, Datei- oder Warteschlangenspeicher zu arbeiten.</span><span class="sxs-lookup"><span data-stu-id="338d6-108">Use [connection strings](/azure/storage/storage-create-storage-account#manage-your-storage-account) to connect to an Azure Storage account, then use the client libraries' classes and methods to work with blob, table, file, or queue storage.</span></span>

<span data-ttu-id="338d6-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/WindowsAzure.Storage) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="338d6-109">Install the [NuGet package](https://www.nuget.org/packages/WindowsAzure.Storage) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="338d6-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="338d6-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package WindowsAzure.Storage
```

### <a name="net-core-cli"></a><span data-ttu-id="338d6-111">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="338d6-111">.NET Core CLI</span></span>

```bash
dotnet add package WindowsAzure.Storage
```

### <a name="code-example"></a><span data-ttu-id="338d6-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="338d6-112">Code Example</span></span>

<span data-ttu-id="338d6-113">In diesem Beispiel wird in einem vorhandenen Speicherkonto ein neues Blob in einem neuen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="338d6-113">This example creates a new blob to a new container in an existing storage account.</span></span>

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
> [<span data-ttu-id="338d6-114">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="338d6-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/storage/client)

## <a name="management-apis"></a><span data-ttu-id="338d6-115">Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="338d6-115">Management APIs</span></span>

<span data-ttu-id="338d6-116">Erstellen und verwalten Sie Azure Storage-Konten und -Verbindungsschlüssel mit der Verwaltungs-API.</span><span class="sxs-lookup"><span data-stu-id="338d6-116">Create and manage Azure Storage accounts and connection keys with the management API.</span></span>

<span data-ttu-id="338d6-117">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="338d6-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="338d6-118">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="338d6-118">Visual Studio package manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Storage.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="338d6-119">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="338d6-119">.NET Core CLI</span></span>

````bash
dotnet add package Microsoft.Azure.Management.Storage.Fluent
````

### <a name="code-example"></a><span data-ttu-id="338d6-120">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="338d6-120">Code Example</span></span>

<span data-ttu-id="338d6-121">In diesem Beispiel wird ein Speicherkonto erstellt.</span><span class="sxs-lookup"><span data-stu-id="338d6-121">This example creates a storage account.</span></span>

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
> [<span data-ttu-id="338d6-122">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="338d6-122">Explore the management APIs</span></span>](/dotnet/api/overview/azure/storage/management)

## <a name="samples"></a><span data-ttu-id="338d6-123">Beispiele</span><span class="sxs-lookup"><span data-stu-id="338d6-123">Samples</span></span>

* [<span data-ttu-id="338d6-124">Erste Schritte mit Azure Blob Storage in .NET</span><span class="sxs-lookup"><span data-stu-id="338d6-124">Get started with Azure Blob Storage in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-blob-dotnet-getting-started/) 
* [<span data-ttu-id="338d6-125">Erste Schritte mit Azure Queue Storage in .NET</span><span class="sxs-lookup"><span data-stu-id="338d6-125">Get started with Azure Queue Storage in .NET</span></span>](https://azure.microsoft.com/resources/samples/storage-queue-dotnet-getting-started/)

<span data-ttu-id="338d6-126">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage) von Beispielen für Azure Storage an.</span><span class="sxs-lookup"><span data-stu-id="338d6-126">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage) of Azure Storage samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package