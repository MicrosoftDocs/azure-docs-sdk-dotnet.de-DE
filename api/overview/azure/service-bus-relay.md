---
title: "Azure Service Bus Relay-Bibliotheken für .NET"
description: "Referenz für Azure Service Bus Relay-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Service Bus Relay
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: service-bus
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 1a869d5939e357c98ec417e6474f711b9ac8c466
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-service-bus-relay-libraries-for-net"></a><span data-ttu-id="20c83-104">Azure Service Bus Relay-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="20c83-104">Azure Service Bus Relay libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="20c83-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="20c83-105">Overview</span></span>

<span data-ttu-id="20c83-106">Der Azure Relay-Dienst erstellt Hybridanwendungen, indem er Ihnen die Möglichkeit bietet, WCF-Dienste in einem Unternehmensnetzwerk sicher in der öffentlichen Cloud bereitzustellen, ohne dass eine Firewallverbindung geöffnet werden muss oder tiefgreifende Änderungen an der unternehmensinternen Netzwerkinfrastruktur erforderlich werden.</span><span class="sxs-lookup"><span data-stu-id="20c83-106">The Azure Relay service creates hybrid applications by enabling you to securely expose services that reside within a corporate enterprise network to the public cloud, without having to open a firewall connection, or require intrusive changes to a corporate network infrastructure.</span></span> <span data-ttu-id="20c83-107">Relay unterstützt eine Vielzahl verschiedener Transportprotokolle und Webdienststandards.</span><span class="sxs-lookup"><span data-stu-id="20c83-107">Relay supports a variety of different transport protocols and web services standards.</span></span>
          
<span data-ttu-id="20c83-108">Weitere Informationen zu [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span><span class="sxs-lookup"><span data-stu-id="20c83-108">Learn more about [Azure Relay](/azure/service-bus-relay/relay-what-is-it).</span></span>

## <a name="client-library"></a><span data-ttu-id="20c83-109">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="20c83-109">Client library</span></span>

<span data-ttu-id="20c83-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Relay) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="20c83-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Relay) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="20c83-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="20c83-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Relay
```

```bash
dotnet add package Microsoft.Azure.Relay
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="20c83-112">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="20c83-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/relay/client)

## <a name="samples"></a><span data-ttu-id="20c83-113">Beispiele</span><span class="sxs-lookup"><span data-stu-id="20c83-113">Samples</span></span>

<span data-ttu-id="20c83-114">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="20c83-114">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package