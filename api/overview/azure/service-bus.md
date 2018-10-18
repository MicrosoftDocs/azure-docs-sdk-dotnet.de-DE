---
title: Azure Service Bus-Bibliotheken für .NET
description: Referenz für Azure Service Bus-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: service-bus-messaging
ms.openlocfilehash: a7a42b8ec788b944cb519218b0e5b201e5d6ac4f
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348042"
---
# <a name="azure-service-bus-libraries-for-net"></a><span data-ttu-id="a135d-103">Azure Service Bus-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="a135d-103">Azure Service Bus libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="a135d-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="a135d-104">Overview</span></span>

<span data-ttu-id="a135d-105">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) bietet eine Messaginginfrastruktur, über die Anwendungen Nachrichten austauschen können, um die Skalierbarkeit und Ausfallsicherheit zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="a135d-105">[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) is a messaging infrastructure that sits between applications allowing them to exchange messages for improved scale and resiliency.</span></span>

## <a name="client-library"></a><span data-ttu-id="a135d-106">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="a135d-106">Client library</span></span>

<span data-ttu-id="a135d-107">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus.</span><span class="sxs-lookup"><span data-stu-id="a135d-107">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.ServiceBus) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="a135d-108">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="a135d-108">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.ServiceBus
```

### <a name="code-example"></a><span data-ttu-id="a135d-109">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="a135d-109">Code Example</span></span>

<span data-ttu-id="a135d-110">In diesem Beispiel wird eine Nachricht an eine Service Bus-Warteschlange gesendet.</span><span class="sxs-lookup"><span data-stu-id="a135d-110">This example sends a message to a Service Bus queue.</span></span>

```csharp
// using Microsoft.Azure.ServiceBus;
// Microsoft.Azure.ServiceBus 2.0.0 (stable)

byte[] messageBody = System.Text.Encoding.Unicode.GetBytes("Hello, world!");
ServiceBusConnectionStringBuilder builder = new ServiceBusConnectionStringBuilder(connectionString);
QueueClient client = new QueueClient(builder, ReceiveMode.PeekLock);
client.SendAsync(new Message(messageBody));
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="a135d-111">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="a135d-111">Explore the client APIs</span></span>](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a><span data-ttu-id="a135d-112">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="a135d-112">Management library</span></span>

<span data-ttu-id="a135d-113">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="a135d-113">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="a135d-114">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="a135d-114">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ServiceBus.Fluent
```

#### <a name="net-core-cli"></a><span data-ttu-id="a135d-115">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="a135d-115">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.ServiceBus.Fluent
```

### <a name="code-example"></a><span data-ttu-id="a135d-116">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="a135d-116">Code Example</span></span>

<span data-ttu-id="a135d-117">In diesem Beispiel wird eine Service Bus-Warteschlange mit einer maximalen Größe von 1.024 MB erstellt.</span><span class="sxs-lookup"><span data-stu-id="a135d-117">This example creates a Service Bus queue with a maximum size of 1024 MB.</span></span>

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
> [<span data-ttu-id="a135d-118">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="a135d-118">Explore the management APIs</span></span>](/dotnet/api/overview/azure/servicebus/management)

## <a name="samples"></a><span data-ttu-id="a135d-119">Beispiele</span><span class="sxs-lookup"><span data-stu-id="a135d-119">Samples</span></span>

- <span data-ttu-id="a135d-120">[Getting Started with Service – Service Bus Queue Basic – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/) (Erste Schritte mit Dienst – Grundlagen der Service Bus-Warteschlange in .Net)</span><span class="sxs-lookup"><span data-stu-id="a135d-120">[Service Bus Queue Basics - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/)</span></span>
- <span data-ttu-id="a135d-121">[Getting Started with Service – Service Bus Queue Advanced Features – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/) (Erste Schritte mit Dienst – erweiterte Funktionen der Service Bus-Warteschlange in .Net)</span><span class="sxs-lookup"><span data-stu-id="a135d-121">[Service Bus Queue Advanced Features - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/)</span></span>
- <span data-ttu-id="a135d-122">[Getting Started with Service – Service Bus Publish Subscribe Basic – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/) (Erste Schritte mit Dienst – Grundlagen des Veröffentlichens/Abonnierens mit Service Bus – in .Net)</span><span class="sxs-lookup"><span data-stu-id="a135d-122">[Service Bus Publish/Subscribe Basics - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/)</span></span>
- <span data-ttu-id="a135d-123">[Getting Started with Service – Service Bus Publish Subscribe Advance Features – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/) (Erste Schritte mit Dienst – erweiterte Funktionen zum Veröffentlichen/Abonnieren mit Service Bus – in .Net)</span><span class="sxs-lookup"><span data-stu-id="a135d-123">[Service Bus Publish/Subscribe Advanced Features - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/)</span></span>
- <span data-ttu-id="a135d-124">[Getting Started with Service - Service Bus With Claim Based Authorization - in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/) (Erste Schritte mit Dienst – Service Bus mit anspruchsbasierter Autorisierung – in .Net)</span><span class="sxs-lookup"><span data-stu-id="a135d-124">[Service Bus with Claims-Based Authorization - .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/)</span></span>

<span data-ttu-id="a135d-125">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?term=service+bus) von Beispielen für Azure Service Bus an.</span><span class="sxs-lookup"><span data-stu-id="a135d-125">View the [complete list](https://azure.microsoft.com/resources/samples/?term=service+bus) of Azure Service Bus samples.</span></span>


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
