---
title: Azure Monitor-Bibliotheken für .NET
description: Referenz für Azure Monitor-Bibliotheken für .NET
ms.date: 10/27/2017
ms.topic: reference
ms.service: monitoring-alerts
ms.openlocfilehash: dbfeb845edf513cf2b4ce102ecdae7d008076641
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348182"
---
# <a name="azure-monitor-libraries-for-net"></a>Azure Monitor-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Monitor dient zum Nachverfolgen der Leistung, Aufrechterhalten der Sicherheit und Identifizieren von Trends.

Weitere Informationen zu Azure Monitor finden Sie [hier](/azure/monitoring-and-diagnostics/).   

## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Monitor.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Monitor.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Monitor.Fluent
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/monitor/management)

## <a name="samples"></a>Beispiele

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package