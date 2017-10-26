---
title: "Azure Application Insights-Bibliotheken für .NET"
description: "Referenz für Azure Application Insights-Bibliotheken für .NET"
keywords: Azure .NET, SDK, API, Application Insights
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: application-insights
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 081143eafaeea2954703c337609a67fd5a7941c6
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
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
