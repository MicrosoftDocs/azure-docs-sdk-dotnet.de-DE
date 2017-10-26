---
title: "Azure Media Services-Bibliotheken für .NET"
description: "Referenz für Azure Media Services-Bibliotheken für .NET"
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
---
# <a name="azure-media-services-libraries-for-net"></a>Azure Media Services-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Microsoft Azure Media Services ist eine erweiterbare, cloudbasierte Plattform, die Entwicklern das Erstellen von skalierbaren Medienverwaltungslösungen und Bereitstellungsanwendungen ermöglicht. Media Services basiert auf REST-APIs, mit denen Sie auf sichere Weise Video- oder Audioinhalte hochladen, speichern, codieren und verpacken können – sowohl für eine bedarfsgesteuerte als auch für eine auf Livestreaming basierende Bereitstellung auf verschiedenen Clients (z.B. TV, PC und mobile Geräte). 

Weitere Informationen finden Sie unter [Übersicht](/azure/media-services/media-services-overview) und [Media Services-Entwicklung mit .NET](/azure/media-services/media-services-dotnet-how-to-use). 

## <a name="client-library"></a>Clientbibliothek

Die Bibliothek für das Azure Media Services-.NET-SDK ermöglicht Ihnen, unter Verwendung von .NET für Media Services zu programmieren. Verwenden Sie die Azure Media Services-Clientbibliothek, um Verbindungen mit Media Services-APIs herzustellen, sie zu authentifizieren und zu entwickeln.  

Weitere Informationen finden Sie unter [Erste Schritte zum Bereitstellen von Inhalten nach Bedarf mit dem .NET-SDK](/azure/media-services/media-services-dotnet-get-started).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/windowsazure.mediaservices) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package windowsazure.mediaservices
```

### <a name="code-example"></a>Codebeispiel

Im folgenden Codebeispiel wird das Media Services-.NET-SDK verwendet, um die folgenden Aufgaben auszuführen:

- Erstellen eines Codierungsauftrags.
- Abrufen eines Verweises auf den Media Encoder Standard-Encoder
- Geben Sie die Verwendung der Voreinstellung „Adaptives Streaming“ an.
- Fügen Sie eine einzelne Codierungsaufgabe zum Auftrag hinzu.
- Geben Sie das zu codierende Asset an.
- Erstellen Sie ein Ausgabemedienobjekt, das das codierte Medienobjekt empfängt.
- Übermitteln des Auftrags.


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
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/mediaservices/client)

## <a name="samples"></a>Beispiele

- [Geschütztes Streamen von HLS-Inhalten mit Apple FairPlay](https://azure.microsoft.com/resources/samples/media-services-dotnet-dynamic-encryption-with-fairplay/)
- [Copy blobs into an Azure Media Services asset](https://azure.microsoft.com/resources/samples/media-services-dotnet-copy-blob-into-asset/) (Kopieren von Blobs in ein Azure Media Services-Asset)
- [Encode and Deliver a Live Stream with Azure Media Services using .NET SDK](https://azure.microsoft.com/resources/samples/media-services-dotnet-encode-live-stream-with-ams-clear/) (Codieren und Übermitteln eines Live Streams mit Azure Media Services mit dem .NET-SDK)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=media-services) von Beispielen für Azure Media Services an.


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
