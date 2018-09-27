---
title: Azure Application Insights-Bibliotheken für .NET
description: Referenz für Azure Application Insights-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: application-insights
ms.openlocfilehash: 10b65f536c6461959b0be9b8f9bd3ec56a307bea
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190835"
---
# <a name="azure-application-insights-libraries-for-net"></a><span data-ttu-id="9e540-103">Azure Application Insights-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="9e540-103">Azure Application Insights libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="9e540-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="9e540-104">Overview</span></span>

<span data-ttu-id="9e540-105">Application Insights ist ein erweiterbarer Überwachungs- und Diagnosedienst für Webentwickler, der leistungsstarke Funktionen für Ad-hoc-Analysen bietet.</span><span class="sxs-lookup"><span data-stu-id="9e540-105">Application Insights is an extensible monitoring & diagnostics service for web developers with powerful ad-hoc analytics capabilities.</span></span> <span data-ttu-id="9e540-106">Sie können die Klassen im Namespace „ApplicationInsights“ zum Konfigurieren der Sammlung von Telemetriedaten konfigurieren und benutzerdefinierte Telemetriedaten aus Ihren Anwendungen senden, die Sie überwachen möchten.</span><span class="sxs-lookup"><span data-stu-id="9e540-106">You can use the classes in the ApplicationInsights namespace to configure telemetry collection and send any custom telemetry from your applications that you want to monitor.</span></span>

## <a name="client-library"></a><span data-ttu-id="9e540-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="9e540-107">Client library</span></span>

<span data-ttu-id="9e540-108">Das Application Insights-Client-SDK für .NET ermöglicht Ihnen zur künftigen Analyse das Protokollieren von Ereignissen, aggregierten Daten, Ausnahmen, Abhängigkeiten und Metriken in Azure.</span><span class="sxs-lookup"><span data-stu-id="9e540-108">The Application Insights client SDK for .NET allows you to log event, aggregated data, exceptions, dependency, and metrics to Azure for future analysis.</span></span>

<span data-ttu-id="9e540-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="9e540-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="9e540-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="9e540-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.ApplicationInsights 
```

```bash
dotnet add package Microsoft.ApplicationInsights 
```

### <a name="example"></a><span data-ttu-id="9e540-111">Beispiel</span><span class="sxs-lookup"><span data-stu-id="9e540-111">Example</span></span>

<span data-ttu-id="9e540-112">In diesem Beispiel wird ein benutzerdefiniertes Ereignis in Application Insights überwacht.</span><span class="sxs-lookup"><span data-stu-id="9e540-112">This example tracks a custom event to Application Insights.</span></span>

```csharp
TelemetryClient client = new TelemetryClient();
client.TrackEvent("MyCustomEvent");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="9e540-113">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="9e540-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/insights/client)



## <a name="samples"></a><span data-ttu-id="9e540-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="9e540-114">Samples</span></span>

- [<span data-ttu-id="9e540-115">Analysen in Application Insights mit OpenSchema</span><span class="sxs-lookup"><span data-stu-id="9e540-115">Application Insights Analytics with OpenSchema</span></span>](https://azure.microsoft.com/resources/samples/guidance-appinsights-openschema/)

<span data-ttu-id="9e540-116">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) der Azure Application Insights-Beispiele an.</span><span class="sxs-lookup"><span data-stu-id="9e540-116">View the [complete list](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) of Azure Application Insights samples.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
