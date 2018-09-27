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
# <a name="azure-application-insights-libraries-for-net"></a>Azure Application Insights-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Application Insights ist ein erweiterbarer Überwachungs- und Diagnosedienst für Webentwickler, der leistungsstarke Funktionen für Ad-hoc-Analysen bietet. Sie können die Klassen im Namespace „ApplicationInsights“ zum Konfigurieren der Sammlung von Telemetriedaten konfigurieren und benutzerdefinierte Telemetriedaten aus Ihren Anwendungen senden, die Sie überwachen möchten.

## <a name="client-library"></a>Clientbibliothek

Das Application Insights-Client-SDK für .NET ermöglicht Ihnen zur künftigen Analyse das Protokollieren von Ereignissen, aggregierten Daten, Ausnahmen, Abhängigkeiten und Metriken in Azure.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.ApplicationInsights ) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.ApplicationInsights 
```

```bash
dotnet add package Microsoft.ApplicationInsights 
```

### <a name="example"></a>Beispiel

In diesem Beispiel wird ein benutzerdefiniertes Ereignis in Application Insights überwacht.

```csharp
TelemetryClient client = new TelemetryClient();
client.TrackEvent("MyCustomEvent");
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/insights/client)



## <a name="samples"></a>Beispiele

- [Analysen in Application Insights mit OpenSchema](https://azure.microsoft.com/resources/samples/guidance-appinsights-openschema/)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?service=application-insights&platform=dotnet) der Azure Application Insights-Beispiele an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
