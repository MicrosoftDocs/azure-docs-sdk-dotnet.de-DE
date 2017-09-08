---
title: "Azure Stream Analytics-Bibliotheken für .NET"
description: "Referenz für Azure Stream Analytics-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Stream Analytics
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: b812f0948b2153d717987fbc6912ed4665154b3f
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-stream-analytics-libraries-for-net"></a><span data-ttu-id="1afbf-104">Azure Stream Analytics-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="1afbf-104">Azure Stream Analytics libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="1afbf-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="1afbf-105">Overview</span></span>

<span data-ttu-id="1afbf-106">[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) ist ein vollständig verwaltetes Modul für die Ereignisverarbeitung, mit dem Sie analytische Echtzeitberechnungen von Datenströmen einrichten können.</span><span class="sxs-lookup"><span data-stu-id="1afbf-106">[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) is a fully managed event-processing engine that lets you set up real-time analytic computations on streaming data.</span></span> <span data-ttu-id="1afbf-107">Die Daten können von Geräten, Sensoren, Websites, Feeds sozialer Medien, Anwendungen, Infrastruktursystemen usw. stammen.</span><span class="sxs-lookup"><span data-stu-id="1afbf-107">The data can come from devices, sensors, web sites, social media feeds, applications, infrastructure systems, and more.</span></span> 

<span data-ttu-id="1afbf-108">Weitere Informationen zu Azure Stream Analytics finden Sie unter [Erste Schritte mit Azure Stream Analytics: Betrugserkennung in Echtzeit](/azure/stream-analytics/stream-analytics-real-time-fraud-detection).</span><span class="sxs-lookup"><span data-stu-id="1afbf-108">To learn more about Azure Stream Analytics, see [Get started with Azure Stream Analytics Real-time fraud detection](/azure/stream-analytics/stream-analytics-real-time-fraud-detection).</span></span>


## <a name="management-library"></a><span data-ttu-id="1afbf-109">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="1afbf-109">Management library</span></span>

<span data-ttu-id="1afbf-110">Verwenden Sie die Azure Stream Analytics-Verwaltungsbibliothek zum Erstellen, Starten und Beenden von Azure Stream Analytics-Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="1afbf-110">Use the Azure Stream Analytics management library to create, start, and stop Azure Stream Analytics jobs.</span></span>

<span data-ttu-id="1afbf-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="1afbf-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="1afbf-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="1afbf-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.StreamAnalytics
```

```bash
dotnet add package Microsoft.Azure.Management.StreamAnalytics
```

### <a name="code-example"></a><span data-ttu-id="1afbf-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="1afbf-113">Code Example</span></span>

<span data-ttu-id="1afbf-114">In diesem Beispiel wird ein Stream Analytics-Client instanziiert und ein Streamingauftrag erstellt.</span><span class="sxs-lookup"><span data-stu-id="1afbf-114">This example instantiates a Stream Analytics client and creates a streaming job.</span></span>

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
> [<span data-ttu-id="1afbf-115">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="1afbf-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/streamanalytics/management)


## <a name="samples"></a><span data-ttu-id="1afbf-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="1afbf-116">Samples</span></span>

- [<span data-ttu-id="1afbf-117">Management .NET SDK: Einrichten und Ausführen von Analyseaufträgen mit der Azure Stream Analytics-API für .NET</span><span class="sxs-lookup"><span data-stu-id="1afbf-117">Management .NET SDK: Set up and run analytics jobs using the Azure Stream Analytics API for .NET</span></span>](/azure/stream-analytics/stream-analytics-dotnet-management-sdk)

<span data-ttu-id="1afbf-118">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics) von Azure Stream Analytics-Beispielen an.</span><span class="sxs-lookup"><span data-stu-id="1afbf-118">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics) of Azure Stream Analytics samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
