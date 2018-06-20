---
title: Azure Stream Analytics-Bibliotheken für .NET
description: Referenz für Azure Stream Analytics-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Stream Analytics
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: stream-analytics
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2a5e8b8481548d6cfebc5104eb459f8772f51462
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
ms.locfileid: "23487133"
---
# <a name="azure-stream-analytics-libraries-for-net"></a>Azure Stream Analytics-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) ist ein vollständig verwaltetes Modul für die Ereignisverarbeitung, mit dem Sie analytische Echtzeitberechnungen von Datenströmen einrichten können. Die Daten können von Geräten, Sensoren, Websites, Feeds sozialer Medien, Anwendungen, Infrastruktursystemen usw. stammen. 

Weitere Informationen zu Azure Stream Analytics finden Sie unter [Erste Schritte mit Azure Stream Analytics: Betrugserkennung in Echtzeit](/azure/stream-analytics/stream-analytics-real-time-fraud-detection).


## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Azure Stream Analytics-Verwaltungsbibliothek zum Erstellen, Starten und Beenden von Azure Stream Analytics-Aufträgen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.StreamAnalytics
```

```bash
dotnet add package Microsoft.Azure.Management.StreamAnalytics
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird ein Stream Analytics-Client instanziiert und ein Streamingauftrag erstellt.

```csharp
/* Include these 'using' directives:
using Microsoft.Azure.Management.StreamAnalytics;
*/
SynchronizationContext.SetSynchronizationContext(new SynchronizationContext());

// Get credentials
ServiceClientCredentials credentials = GetCredentials().Result;

// Create Stream Analytics management client
StreamAnalyticsManagementClient streamAnalyticsManagementClient = new StreamAnalyticsManagementClient(credentials)
{
    SubscriptionId = subscriptionId
};

// Create a streaming job
StreamingJob streamingJob = new StreamingJob()
{
    Tags = new Dictionary<string, string>()
    {
        { "Origin", ".NET SDK" },
        { "ReasonCreated", "Getting started tutorial" }
    },
    Location = "West US",
    EventsOutOfOrderPolicy = EventsOutOfOrderPolicy.Drop,
    EventsOutOfOrderMaxDelayInSeconds = 5,
    EventsLateArrivalMaxDelayInSeconds = 16,
    OutputErrorPolicy = OutputErrorPolicy.Drop,
    DataLocale = "en-US",
    CompatibilityLevel = CompatibilityLevel.OneFullStopZero,
    Sku = new Sku()
    {
        Name = SkuName.Standard
    }
};
StreamingJob createStreamingJobResult = streamAnalyticsManagementClient.StreamingJobs.CreateOrReplace(streamingJob, resourceGroupName, streamingJobName);
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/streamanalytics/management)


## <a name="samples"></a>Beispiele

- [Management .NET SDK: Einrichten und Ausführen von Analyseaufträgen mit der Azure Stream Analytics-API für .NET](/azure/stream-analytics/stream-analytics-dotnet-management-sdk)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics) von Azure Stream Analytics-Beispielen an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
