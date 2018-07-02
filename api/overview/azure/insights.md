---
title: Azure Application Insights-Bibliotheken für .NET
description: Referenz für Azure Application Insights-Bibliotheken für .NET
keywords: Azure .NET, SDK, API, Application Insights
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: application-insights
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 3cbd4a874edfa6de26d3edf4d151d2c4006ab9c3
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065840"
---
# <a name="azure-application-insights-libraries-for-net"></a><span data-ttu-id="12a36-104">Azure Application Insights-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="12a36-104">Azure Application Insights libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="12a36-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="12a36-105">Overview</span></span>

<span data-ttu-id="12a36-106">Application Insights ist ein erweiterbarer Überwachungs- und Diagnosedienst für Webentwickler, der leistungsstarke Funktionen für Ad-hoc-Analysen bietet.</span><span class="sxs-lookup"><span data-stu-id="12a36-106">Application Insights is an extensible monitoring & diagnostics service for web developers with powerful ad-hoc analytics capabilities.</span></span> <span data-ttu-id="12a36-107">Sie können die Klassen im Namespace „ApplicationInsights“ zum Konfigurieren der Sammlung von Telemetriedaten konfigurieren und benutzerdefinierte Telemetriedaten aus Ihren Anwendungen senden, die Sie überwachen möchten.</span><span class="sxs-lookup"><span data-stu-id="12a36-107">You can use the classes in the ApplicationInsights namespace to configure telemetry collection and send any custom telemetry from your applications that you want to monitor.</span></span>

## <a name="client-library"></a><span data-ttu-id="12a36-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="12a36-108">Client library</span></span>

<span data-ttu-id="12a36-109">Das Application Insights-Client-SDK für .NET ermöglicht Ihnen zur künftigen Analyse das Protokollieren von Ereignissen, aggregierten Daten, Ausnahmen, Abhängigkeiten und Metriken in Azure.</span><span class="sxs-lookup"><span data-stu-id="12a36-109">The Application Insights client SDK for .NET allows you to log event, aggregated data, exceptions, dependency, and metrics to Azure for future analysis.</span></span>

<span data-ttu-id="12a36-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="12a36-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="12a36-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="12a36-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ApplicationInsights 
```

```bash
dotnet add package Microsoft.ApplicationInsights 
```

### <a name="example"></a><span data-ttu-id="12a36-112">Beispiel</span><span class="sxs-lookup"><span data-stu-id="12a36-112">Example</span></span>

<span data-ttu-id="12a36-113">In diesem Beispiel wird ein benutzerdefiniertes Ereignis in Application Insights überwacht.</span><span class="sxs-lookup"><span data-stu-id="12a36-113">This example tracks a custom event to Application Insights.</span></span>

```csharp
TelemetryClient client = new TelemetryClient();
client.TrackEvent("MyCustomEvent");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="12a36-114">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="12a36-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/insights/client)



## <a name="samples"></a><span data-ttu-id="12a36-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="12a36-115">Samples</span></span>

- [<span data-ttu-id="12a36-116">Analysen in Application Insights mit OpenSchema</span><span class="sxs-lookup"><span data-stu-id="12a36-116">Application Insights Analytics with OpenSchema</span></span>](https://azure.microsoft.com/resources/samples/guidance-appinsights-openschema/)

<span data-ttu-id="12a36-117">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) der Azure Application Insights-Beispiele an.</span><span class="sxs-lookup"><span data-stu-id="12a36-117">View the [complete list](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) of Azure Application Insights samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
