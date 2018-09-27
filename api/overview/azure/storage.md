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
# <a name="azure-storage-apis-for-net"></a>Azure Storage-APIs für .NET

## <a name="overview"></a>Übersicht

Lesen und schreiben Sie mit [Azure Storage](https://docs.microsoft.com/azure/storage/storage-introduction) Dateien, Blob- bzw. Objektdaten, Schlüssel-Wert-Paare und Nachrichten aus Ihren .NET-Anwendungen.

Informationen zu den ersten Schritten mit Azure Storage finden Sie unter [Erste Schritte mit Azure Blob Storage mithilfe von .NET](/azure/storage/storage-dotnet-how-to-use-blobs).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie [Verbindungszeichenfolgen](/azure/storage/storage-create-storage-account#manage-your-storage-account), um eine Verbindung mit einem Azure Storage-Konto herzustellen. Nutzen Sie anschließend die Klassen und Methoden der Clientbibliotheken, um mit Blob-, Tabellen-, Datei- oder Warteschlangenspeicher zu arbeiten.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/WindowsAzure.Storage) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package WindowsAzure.Storage
```

### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package WindowsAzure.Storage
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird in einem vorhandenen Speicherkonto ein neues Blob in einem neuen Container erstellt.

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
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/storage/client)

## <a name="management-apis"></a>Verwaltungs-APIs

Erstellen und verwalten Sie Azure Storage-Konten und -Verbindungsschlüssel mit der Verwaltungs-API.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Storage.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Storage.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

````bash
dotnet add package Microsoft.Azure.Management.Storage.Fluent
````

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird ein Speicherkonto erstellt.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/storage/management)

## <a name="samples"></a>Beispiele

* [Erste Schritte mit Azure Blob Storage in .NET](https://azure.microsoft.com/resources/samples/storage-blob-dotnet-getting-started/) 
* [Erste Schritte mit Azure Queue Storage in .NET](https://azure.microsoft.com/resources/samples/storage-queue-dotnet-getting-started/)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=storage) von Beispielen für Azure Storage an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package