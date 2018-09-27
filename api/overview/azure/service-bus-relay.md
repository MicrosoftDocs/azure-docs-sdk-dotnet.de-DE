---
title: Azure Service Bus Relay-Bibliotheken für .NET
description: Referenz für Azure Service Bus Relay-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-bus
ms.openlocfilehash: 75c481ab23e461c5194a9eeb0ca668af98f4d2d7
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47189983"
---
# <a name="azure-service-bus-relay-libraries-for-net"></a>Azure Service Bus Relay-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Der Azure Relay-Dienst erstellt Hybridanwendungen, indem er Ihnen die Möglichkeit bietet, WCF-Dienste in einem Unternehmensnetzwerk sicher in der öffentlichen Cloud bereitzustellen, ohne dass eine Firewallverbindung geöffnet werden muss oder tiefgreifende Änderungen an der unternehmensinternen Netzwerkinfrastruktur erforderlich werden. Relay unterstützt eine Vielzahl verschiedener Transportprotokolle und Webdienststandards.
          
Weitere Informationen zu [Azure Relay](/azure/service-bus-relay/relay-what-is-it).

## <a name="client-library"></a>Clientbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Relay) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a>Beispiele

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package