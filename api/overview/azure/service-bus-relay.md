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
# <a name="azure-service-bus-relay-libraries-for-net"></a><span data-ttu-id="f2347-103">Azure Service Bus Relay-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="f2347-103">Azure Service Bus Relay libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="f2347-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="f2347-104">Overview</span></span>

<span data-ttu-id="f2347-105">Der Azure Relay-Dienst erstellt Hybridanwendungen, indem er Ihnen die Möglichkeit bietet, WCF-Dienste in einem Unternehmensnetzwerk sicher in der öffentlichen Cloud bereitzustellen, ohne dass eine Firewallverbindung geöffnet werden muss oder tiefgreifende Änderungen an der unternehmensinternen Netzwerkinfrastruktur erforderlich werden.</span><span class="sxs-lookup"><span data-stu-id="f2347-105">The Azure Relay service creates hybrid applications by enabling you to securely expose services that reside within a corporate enterprise network to the public cloud, without having to open a firewall connection, or require intrusive changes to a corporate network infrastructure.</span></span> <span data-ttu-id="f2347-106">Relay unterstützt eine Vielzahl verschiedener Transportprotokolle und Webdienststandards.</span><span class="sxs-lookup"><span data-stu-id="f2347-106">Relay supports a variety of different transport protocols and web services standards.</span></span>
          
<span data-ttu-id="f2347-107">Weitere Informationen zu [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span><span class="sxs-lookup"><span data-stu-id="f2347-107">Learn more about [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span></span>

## <a name="client-library"></a><span data-ttu-id="f2347-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="f2347-108">Client library</span></span>

<span data-ttu-id="f2347-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Relay) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="f2347-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Relay) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f2347-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="f2347-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="f2347-111">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="f2347-111">Explore the client APIs</span></span>](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a><span data-ttu-id="f2347-112">Beispiele</span><span class="sxs-lookup"><span data-stu-id="f2347-112">Samples</span></span>

<span data-ttu-id="f2347-113">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="f2347-113">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package