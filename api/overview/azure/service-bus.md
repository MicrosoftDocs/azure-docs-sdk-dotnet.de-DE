---
title: "Azure Service Bus-Bibliotheken für .NET"
description: "Referenz für Azure Service Bus-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Service Bus
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
ms.openlocfilehash: c2019fd39f42f9bc4a39dd4e642db9f90b7a917c
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
---
# <a name="azure-service-bus-libraries-for-net"></a><span data-ttu-id="bb52f-104">Azure Service Bus-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="bb52f-104">Azure Service Bus libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="bb52f-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="bb52f-105">Overview</span></span>

<span data-ttu-id="bb52f-106">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) bietet eine Messaginginfrastruktur, über die Anwendungen Nachrichten austauschen können, um die Skalierbarkeit und Ausfallsicherheit zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="bb52f-106">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) is a messaging infrastructure that sits between applications allowing them to exchange messages for improved scale and resiliency.</span></span>

## <a name="client-library"></a><span data-ttu-id="bb52f-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="bb52f-107">Client library</span></span>

<span data-ttu-id="bb52f-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/WindowsAzure.ServiceBus) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus.</span><span class="sxs-lookup"><span data-stu-id="bb52f-108">Install the [NuGet package](https://www.nuget.org/packages/WindowsAzure.ServiceBus) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="bb52f-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="bb52f-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package WindowsAzure.ServiceBus
```

### <a name="code-example"></a><span data-ttu-id="bb52f-110">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="bb52f-110">Code Example</span></span>

<span data-ttu-id="bb52f-111">In diesem Beispiel wird eine Nachricht an eine Service Bus-Warteschlange gesendet.</span><span class="sxs-lookup"><span data-stu-id="bb52f-111">This example sends a message to a Service Bus queue.</span></span>

```csharp
// using Microsoft.ServiceBus.Messaging;

QueueClient client = QueueClient.CreateFromConnectionString(connectionString, queueName);
BrokeredMessage message = new BrokeredMessage("This is a test message!");
client.Send(message);
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="bb52f-112">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="bb52f-112">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a><span data-ttu-id="bb52f-113">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="bb52f-113">Management library</span></span>

<span data-ttu-id="bb52f-114">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="bb52f-114">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="bb52f-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="bb52f-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceBus.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="bb52f-116">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="bb52f-116">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.ServiceBus.Fluent
```

### <a name="code-example"></a><span data-ttu-id="bb52f-117">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="bb52f-117">Code Example</span></span>

<span data-ttu-id="bb52f-118">In diesem Beispiel wird eine Service Bus-Warteschlange mit einer maximalen Größe von 1.024 MB erstellt.</span><span class="sxs-lookup"><span data-stu-id="bb52f-118">This example creates a Service Bus queue with a maximum size of 1024 MB.</span></span>

```csharp
// using Microsoft.Azure.Management.ServiceBus.Fluent;
// using Microsoft.Azure.Management.ServiceBus.Fluent.Models;

using (ServiceBusManagementClient client = new ServiceBusManagementClient(credentials))
{
    client.SubscriptionId = subscriptionId;
    QueueInner parameters = new QueueInner
    {
        MaxSizeInMegabytes = 1024
    };
    await client.Queues.CreateOrUpdateAsync(resourceGroupName, namespaceName, queueName, parameters);
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="bb52f-119">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="bb52f-119">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicebus/management)

## <a name="samples"></a><span data-ttu-id="bb52f-120">Beispiele</span><span class="sxs-lookup"><span data-stu-id="bb52f-120">Samples</span></span>

- <span data-ttu-id="bb52f-121">[Getting Started with Service – Service Bus Queue Basic – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/) (Erste Schritte mit Dienst – Grundlagen der Service Bus-Warteschlange in .Net)</span><span class="sxs-lookup"><span data-stu-id="bb52f-121">[Service Bus Queue Basics - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/)</span></span>
- <span data-ttu-id="bb52f-122">[Getting Started with Service – Service Bus Queue Advanced Features – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/) (Erste Schritte mit Dienst – erweiterte Funktionen der Service Bus-Warteschlange in .Net)</span><span class="sxs-lookup"><span data-stu-id="bb52f-122">[Service Bus Queue Advanced Features - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/)</span></span>
- <span data-ttu-id="bb52f-123">[Getting Started with Service – Service Bus Publish Subscribe Basic – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/) (Erste Schritte mit Dienst – Grundlagen des Veröffentlichens/Abonnierens mit Service Bus – in .Net)</span><span class="sxs-lookup"><span data-stu-id="bb52f-123">[Service Bus Publish/Subscribe Basics - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/)</span></span>
- <span data-ttu-id="bb52f-124">[Getting Started with Service – Service Bus Publish Subscribe Advance Features – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/) (Erste Schritte mit Dienst – erweiterte Funktionen zum Veröffentlichen/Abonnieren mit Service Bus – in .Net)</span><span class="sxs-lookup"><span data-stu-id="bb52f-124">[Service Bus Publish/Subscribe Advanced Features - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/)</span></span>
- <span data-ttu-id="bb52f-125">[Getting Started with Service - Service Bus With Claim Based Authorization - in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/) (Erste Schritte mit Dienst – Service Bus mit anspruchsbasierter Autorisierung – in .Net)</span><span class="sxs-lookup"><span data-stu-id="bb52f-125">[Service Bus with Claims-Based Authorization - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/)</span></span>

<span data-ttu-id="bb52f-126">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?term=service+bus) von Beispielen für Azure Service Bus an.</span><span class="sxs-lookup"><span data-stu-id="bb52f-126">View the [complete list](https://azure.microsoft.com/resources/samples/?term=service+bus) of Azure Service Bus samples.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
