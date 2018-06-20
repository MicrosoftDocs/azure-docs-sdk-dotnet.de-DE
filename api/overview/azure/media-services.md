---
title: Azure Media Services-Bibliotheken für .NET
description: Referenz für Azure Media Services-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Media Services
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: media-services
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 872ed60363c0c886e9844d0cb0bef07cf41a0242
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
ms.locfileid: "23487443"
---
# <a name="azure-media-services-libraries-for-net"></a><span data-ttu-id="8d0d1-104">Azure Media Services-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="8d0d1-104">Azure Media Services libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="8d0d1-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="8d0d1-105">Overview</span></span>

<span data-ttu-id="8d0d1-106">Microsoft Azure Media Services ist eine erweiterbare, cloudbasierte Plattform, die Entwicklern das Erstellen von skalierbaren Medienverwaltungslösungen und Bereitstellungsanwendungen ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-106">Microsoft Azure Media Services is an extensible cloud-based platform that enables developers to build scalable media management and delivery applications.</span></span> <span data-ttu-id="8d0d1-107">Media Services basiert auf REST-APIs, mit denen Sie auf sichere Weise Video- oder Audioinhalte hochladen, speichern, codieren und verpacken können – sowohl für eine bedarfsgesteuerte als auch für eine auf Livestreaming basierende Bereitstellung auf verschiedenen Clients (z.B. TV, PC und mobile Geräte).</span><span class="sxs-lookup"><span data-stu-id="8d0d1-107">Media Services is based on REST APIs that enable you to securely upload, store, encode, and package video or audio content for both on-demand and live streaming delivery to various clients (for example, TV, PC, and mobile devices).</span></span> 

<span data-ttu-id="8d0d1-108">Weitere Informationen finden Sie unter [Übersicht](/azure/media-services/media-services-overview) und [Media Services-Entwicklung mit .NET](/azure/media-services/media-services-dotnet-how-to-use).</span><span class="sxs-lookup"><span data-stu-id="8d0d1-108">To learn more, see [Overview](/azure/media-services/media-services-overview) and [Getting started with .NET](/azure/media-services/media-services-dotnet-how-to-use).</span></span> 

## <a name="client-library"></a><span data-ttu-id="8d0d1-109">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="8d0d1-109">Client library</span></span>

<span data-ttu-id="8d0d1-110">Die Bibliothek für das Azure Media Services-.NET-SDK ermöglicht Ihnen, unter Verwendung von .NET für Media Services zu programmieren.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-110">The Azure Media Services .NET SDK library enables you to program against Media Services using .NET.</span></span> <span data-ttu-id="8d0d1-111">Verwenden Sie die Azure Media Services-Clientbibliothek, um Verbindungen mit Media Services-APIs herzustellen, sie zu authentifizieren und zu entwickeln.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-111">Use the Azure Media Services client library to connect, authenticate, and develop against Media Services APIs.</span></span>  

<span data-ttu-id="8d0d1-112">Weitere Informationen finden Sie unter [Erste Schritte zum Bereitstellen von Inhalten nach Bedarf mit dem .NET-SDK](/azure/media-services/media-services-dotnet-get-started).</span><span class="sxs-lookup"><span data-stu-id="8d0d1-112">For more information, see [Get started with delivering content on demand using .NET SDK](/azure/media-services/media-services-dotnet-get-started).</span></span>

<span data-ttu-id="8d0d1-113">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/windowsazure.mediaservices) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="8d0d1-113">Install the [NuGet package](https://www.nuget.org/packages/windowsazure.mediaservices) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="8d0d1-114">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="8d0d1-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package windowsazure.mediaservices
```

### <a name="code-example"></a><span data-ttu-id="8d0d1-115">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="8d0d1-115">Code Example</span></span>

<span data-ttu-id="8d0d1-116">Im folgenden Codebeispiel wird das Media Services-.NET-SDK verwendet, um die folgenden Aufgaben auszuführen:</span><span class="sxs-lookup"><span data-stu-id="8d0d1-116">The following code example uses Media Services .NET SDK to perform the following tasks:</span></span>

- <span data-ttu-id="8d0d1-117">Erstellen eines Codierungsauftrags.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-117">Create an encoding job.</span></span>
- <span data-ttu-id="8d0d1-118">Abrufen eines Verweises auf den Media Encoder Standard-Encoder</span><span class="sxs-lookup"><span data-stu-id="8d0d1-118">Get a reference to the Media Encoder Standard encoder.</span></span>
- <span data-ttu-id="8d0d1-119">Geben Sie die Verwendung der Voreinstellung „Adaptives Streaming“ an.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-119">Specify to use the Adaptive Streaming preset.</span></span>
- <span data-ttu-id="8d0d1-120">Fügen Sie eine einzelne Codierungsaufgabe zum Auftrag hinzu.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-120">Add a single encoding task to the job.</span></span>
- <span data-ttu-id="8d0d1-121">Geben Sie das zu codierende Asset an.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-121">Specify the input asset to be encoded.</span></span>
- <span data-ttu-id="8d0d1-122">Erstellen Sie ein Ausgabemedienobjekt, das das codierte Medienobjekt empfängt.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-122">Create an output asset to receive the encoded asset.</span></span>
- <span data-ttu-id="8d0d1-123">Übermitteln des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-123">Submit the job.</span></span>


```csharp
/* Include this 'using' directive:
using Microsoft.WindowsAzure.MediaServices.Client;
*/

CloudMediaContext context = new CloudMediaContext(new Uri(mediaServiceRESTAPIEndpoint), tokenProvider);

// Get an uploaded asset.
IAsset asset = context.Assets.FirstOrDefault();

// Encode and generate the output using the "Adaptive Streaming" preset.
// Declare a new job.
IJob job = context.Jobs.Create("Media Encoder Standard Job");
// Get a media processor reference, and pass to it the name of the 
// processor to use for the specific task.
IMediaProcessor processor = context.MediaProcessors.Where(p => p.Name == mediaProcessorName)
    .ToList().OrderBy(p => new Version(p.Version)).LastOrDefault();
if (processor == null) 
{
    throw new ArgumentException(string.Format("Unknown media processor", mediaProcessorName));
}

// Create a task with the encoding details, using a string preset.
// In this case "Adaptive Streaming" preset is used.
ITask task = job.Tasks.AddNew("My encoding task", processor, "Adaptive Streaming", TaskOptions.None);

// Specify the input asset to be encoded.
task.InputAssets.Add(asset);
// Add an output asset to contain the results of the job. 
// This output is specified as AssetCreationOptions.None, which 
// means the output asset is not encrypted. 
task.OutputAssets.AddNew("Output asset", AssetCreationOptions.None);

job.Submit();
job.GetExecutionProgressTask(CancellationToken.None).Wait();
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="8d0d1-124">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="8d0d1-124">Explore the client APIs</span></span>](/dotnet/api/overview/azure/mediaservices/client)

## <a name="samples"></a><span data-ttu-id="8d0d1-125">Beispiele</span><span class="sxs-lookup"><span data-stu-id="8d0d1-125">Samples</span></span>

- [<span data-ttu-id="8d0d1-126">Geschütztes Streamen von HLS-Inhalten mit Apple FairPlay</span><span class="sxs-lookup"><span data-stu-id="8d0d1-126">Stream your HLS content Protected with Apple FairPlay</span></span>](https://azure.microsoft.com/resources/samples/media-services-dotnet-dynamic-encryption-with-fairplay/)
- <span data-ttu-id="8d0d1-127">[Copy blobs into an Azure Media Services asset](https://azure.microsoft.com/resources/samples/media-services-dotnet-copy-blob-into-asset/) (Kopieren von Blobs in ein Azure Media Services-Asset)</span><span class="sxs-lookup"><span data-stu-id="8d0d1-127">[Copy blob into an Azure Media Services asset using .NET SDK Extensions](https://azure.microsoft.com/resources/samples/media-services-dotnet-copy-blob-into-asset/)</span></span>
- <span data-ttu-id="8d0d1-128">[Encode and Deliver a Live Stream with Azure Media Services using .NET SDK](https://azure.microsoft.com/resources/samples/media-services-dotnet-encode-live-stream-with-ams-clear/) (Codieren und Übermitteln eines Live Streams mit Azure Media Services mit dem .NET-SDK)</span><span class="sxs-lookup"><span data-stu-id="8d0d1-128">[Encode and Deliver a Live Stream with Azure Media Services using .NET SDK](https://azure.microsoft.com/resources/samples/media-services-dotnet-encode-live-stream-with-ams-clear/)</span></span>

<span data-ttu-id="8d0d1-129">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=media-services) von Beispielen für Azure Media Services an.</span><span class="sxs-lookup"><span data-stu-id="8d0d1-129">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=media-services) of Azure Media Services samples.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
