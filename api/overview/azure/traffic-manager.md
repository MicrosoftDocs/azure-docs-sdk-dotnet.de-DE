---
title: Azure Traffic Manager-Bibliotheken für .NET
description: Referenz für Azure Traffic Manager-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: traffic-manager
ms.openlocfilehash: a75b5c566496f73475d24d62288a00c7d5775168
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190815"
---
# <a name="azure-traffic-manager-libraries-for-net"></a>Azure Traffic Manager-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Microsoft Azure Traffic Manager ermöglicht die Verteilung von Benutzerdatenverkehr für Dienstendpunkte in unterschiedlichen Rechenzentren. Zu den von Traffic Manager unterstützten Dienstendpunkten zählen virtuelle Azure-Computer, Web-Apps und Clouddienste. Darüber hinaus kann Traffic Manager auch mit externen, Azure-fremden Endpunkten verwendet werden.

Weitere Informationen zu [Azure Traffic Manager](/azure/traffic-manager/traffic-manager-overview).  

## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.TrafficManager.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.TrafficManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.TrafficManager.Fluent
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/trafficmanager/management)

## <a name="samples"></a>Beispiele

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package