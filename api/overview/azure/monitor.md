---
title: Azure Monitor-Bibliotheken für .NET
description: Referenz für Azure Monitor-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Monitor
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/27/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 8055b8861f6991e021ff1ea3bfa87cf96f554fa2
ms.sourcegitcommit: 64c9e16e42894e8db8ed088487e55c5e0edd6861
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/31/2017
ms.locfileid: "23639638"
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