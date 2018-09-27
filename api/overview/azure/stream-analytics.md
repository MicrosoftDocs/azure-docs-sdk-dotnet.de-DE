---
title: Azure Stream Analytics-Bibliotheken für .NET
description: Referenz für Azure Stream Analytics-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: stream-analytics
ms.openlocfilehash: c04a5c8a7b1d7e0f283d4fb81bd772de24f195eb
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190453"
---
# <a name="azure-stream-analytics-libraries-for-net"></a><span data-ttu-id="6c869-103">Azure Stream Analytics-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="6c869-103">Azure Stream Analytics libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="6c869-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="6c869-104">Overview</span></span>

<span data-ttu-id="6c869-105">[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) ist eine vollständig verwaltete Engine für die Ereignisverarbeitung, mit der Sie analytische Echtzeitberechnungen von Datenströmen einrichten können.</span><span class="sxs-lookup"><span data-stu-id="6c869-105">[Azure Stream Analytics](/azure/stream-analytics/stream-analytics-introduction) is a fully managed event-processing engine that lets you set up real-time analytic computations on streaming data.</span></span> <span data-ttu-id="6c869-106">Die Daten können von Geräten, Sensoren, Websites, Feeds sozialer Medien, Anwendungen, Infrastruktursystemen usw. stammen.</span><span class="sxs-lookup"><span data-stu-id="6c869-106">The data can come from devices, sensors, web sites, social media feeds, applications, infrastructure systems, and more.</span></span> 

<span data-ttu-id="6c869-107">Weitere Informationen zu Azure Stream Analytics finden Sie unter [Erste Schritte mit Azure Stream Analytics: Betrugserkennung in Echtzeit](/azure/stream-analytics/stream-analytics-real-time-fraud-detection).</span><span class="sxs-lookup"><span data-stu-id="6c869-107">To learn more about Azure Stream Analytics, see [Get started with Azure Stream Analytics Real-time fraud detection](/azure/stream-analytics/stream-analytics-real-time-fraud-detection).</span></span>


## <a name="management-library"></a><span data-ttu-id="6c869-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="6c869-108">Management library</span></span>

<span data-ttu-id="6c869-109">Verwenden Sie die Azure Stream Analytics-Verwaltungsbibliothek zum Erstellen, Starten und Beenden von Azure Stream Analytics-Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="6c869-109">Use the Azure Stream Analytics management library to create, start, and stop Azure Stream Analytics jobs.</span></span>

<span data-ttu-id="6c869-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="6c869-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.StreamAnalytics) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6c869-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="6c869-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.StreamAnalytics
```

```bash
dotnet add package Microsoft.Azure.Management.StreamAnalytics
```

### <a name="code-example"></a><span data-ttu-id="6c869-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="6c869-112">Code Example</span></span>

<span data-ttu-id="6c869-113">In diesem Beispiel wird ein Stream Analytics-Client instanziiert und ein Streamingauftrag erstellt.</span><span class="sxs-lookup"><span data-stu-id="6c869-113">This example instantiates a Stream Analytics client and creates a streaming job.</span></span>

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
> [<span data-ttu-id="6c869-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="6c869-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/streamanalytics/management)


## <a name="samples"></a><span data-ttu-id="6c869-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="6c869-115">Samples</span></span>

- [<span data-ttu-id="6c869-116">Management .NET SDK: Einrichten und Ausführen von Analyseaufträgen mit der Azure Stream Analytics-API für .NET</span><span class="sxs-lookup"><span data-stu-id="6c869-116">Management .NET SDK: Set up and run analytics jobs using the Azure Stream Analytics API for .NET</span></span>](/azure/stream-analytics/stream-analytics-dotnet-management-sdk)

<span data-ttu-id="6c869-117">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics) von Azure Stream Analytics-Beispielen an.</span><span class="sxs-lookup"><span data-stu-id="6c869-117">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=stream-analytics) of Azure Stream Analytics samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
