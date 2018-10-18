---
title: Azure Service Bus Relay-Bibliotheken für .NET
description: Referenz für Azure Service Bus Relay-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-bus-relay
ms.openlocfilehash: 9190e8efdebe1c352b4fb2c98be189089b0975d2
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348122"
---
# <a name="azure-service-bus-relay-libraries-for-net"></a><span data-ttu-id="6b0ec-103">Azure Service Bus Relay-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="6b0ec-103">Azure Service Bus Relay libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="6b0ec-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="6b0ec-104">Overview</span></span>

<span data-ttu-id="6b0ec-105">Der Azure Relay-Dienst erstellt Hybridanwendungen, indem er Ihnen die Möglichkeit bietet, WCF-Dienste in einem Unternehmensnetzwerk sicher in der öffentlichen Cloud bereitzustellen, ohne dass eine Firewallverbindung geöffnet werden muss oder tiefgreifende Änderungen an der unternehmensinternen Netzwerkinfrastruktur erforderlich werden.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-105">The Azure Relay service creates hybrid applications by enabling you to securely expose services that reside within a corporate enterprise network to the public cloud, without having to open a firewall connection, or require intrusive changes to a corporate network infrastructure.</span></span> <span data-ttu-id="6b0ec-106">Relay unterstützt eine Vielzahl verschiedener Transportprotokolle und Webdienststandards.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-106">Relay supports a variety of different transport protocols and web services standards.</span></span>
          
<span data-ttu-id="6b0ec-107">Weitere Informationen zu [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span><span class="sxs-lookup"><span data-stu-id="6b0ec-107">Learn more about [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span></span>

## <a name="client-library"></a><span data-ttu-id="6b0ec-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="6b0ec-108">Client library</span></span>

<span data-ttu-id="6b0ec-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Relay) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="6b0ec-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Relay) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6b0ec-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="6b0ec-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="6b0ec-111">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="6b0ec-111">Explore the client APIs</span></span>](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a><span data-ttu-id="6b0ec-112">Beispiele</span><span class="sxs-lookup"><span data-stu-id="6b0ec-112">Samples</span></span>

<span data-ttu-id="6b0ec-113">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="6b0ec-113">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package