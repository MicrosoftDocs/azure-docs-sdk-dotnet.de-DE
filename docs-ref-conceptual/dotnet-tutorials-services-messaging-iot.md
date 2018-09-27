---
title: Tutorials für Messaging und IoT mit .NET in Azure | Microsoft-Dokumentation
description: Senden von Nachrichten zwischen Cloudanwendungen und zwischen Geräten und der Cloud mit .NET und Azure-Diensten.
ms.date: 10/19/2017
ms.openlocfilehash: 92cb78b34706a453630dbf36913d53400962ff25
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190773"
---
# <a name="net-tutorials-for-enterprise-messaging-and-internet-of-things-iot"></a><span data-ttu-id="762de-103">.NET-Tutorials für Unternehmensmessaging und Internet der Dinge (Internet of Things, IoT)</span><span class="sxs-lookup"><span data-stu-id="762de-103">.NET tutorials for enterprise messaging and Internet of Things (IoT)</span></span>

<span data-ttu-id="762de-104">Die folgende Tabelle enthält Links zu ausführlichen Tutorials zum Senden und Lesen von Nachrichten zwischen Anwendungen und Geräten in Ihrem .NET Code mithilfe von Azure-Diensten.</span><span class="sxs-lookup"><span data-stu-id="762de-104">The following table links to in-depth tutorials for sending and reading messages between applications and devices in from your .NET code using Azure services.</span></span>

<span data-ttu-id="762de-105">Beispielquellcode finden Sie in der Liste der [Beispiele für Azure-Dienste](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span><span class="sxs-lookup"><span data-stu-id="762de-105">For sample source code, see the list of [Azure service samples](https://azure.microsoft.com/resources/samples/?platform=dotnet).</span></span>


| | |
|---|---|
| <span data-ttu-id="762de-106">**Service Bus**</span><span class="sxs-lookup"><span data-stu-id="762de-106">**Service Bus**</span></span> | |
| <span data-ttu-id="762de-107">[Verwenden von Service Bus-Warteschlangen][1]</span><span class="sxs-lookup"><span data-stu-id="762de-107">[How to use Service Bus queues][1]</span></span> | <span data-ttu-id="762de-108">Erstellen von Warteschlangen, Senden und Empfangen von Nachrichten und Löschen von Warteschlangen.</span><span class="sxs-lookup"><span data-stu-id="762de-108">Create queues, send and receive messages, and delete queues.</span></span> | 
| <span data-ttu-id="762de-109">[Verwenden von Service Bus-Themen und -Abonnements][2]</span><span class="sxs-lookup"><span data-stu-id="762de-109">[How to use Service Bus topics and subscriptions][2]</span></span> | <span data-ttu-id="762de-110">Erfahren Sie, wie Sie das Kommunikationsmodell zum Veröffentlichen/Abonnieren mit Service Bus verwenden.</span><span class="sxs-lookup"><span data-stu-id="762de-110">Learn how to use publish/subscribe communication model with Service Bus.</span></span>
| <span data-ttu-id="762de-111">[Verwenden von Service Bus aus .NET mit AMQP 1.0][3]</span><span class="sxs-lookup"><span data-stu-id="762de-111">[Using Service Bus from .NET with AMQP 1.0][3]</span></span> | <span data-ttu-id="762de-112">Erfahren Sie, wie Sie AMQP in Ihren Service Bus-Anwendungen verwenden.</span><span class="sxs-lookup"><span data-stu-id="762de-112">Learn how to use AMQP in you Service Bus applications.</span></span>
|<span data-ttu-id="762de-113">**IoT Hub**</span><span class="sxs-lookup"><span data-stu-id="762de-113">**IoT Hub**</span></span>|
| <span data-ttu-id="762de-114">[Herstellen einer Verbindung zwischen einem simulierten Gerät und Ihrem IoT Hub][4]</span><span class="sxs-lookup"><span data-stu-id="762de-114">[Connect a simulated device to your IoT Hub][4]</span></span> | <span data-ttu-id="762de-115">Erstellen einer Geräteidentität, Senden von Nachrichten und Verarbeiten von Telemetriedaten aus Ihrem IoT Hub.</span><span class="sxs-lookup"><span data-stu-id="762de-115">Create a device identity, send messages, and process telemetry from your IoT Hub.</span></span> |   
| <span data-ttu-id="762de-116">[Verarbeiten von Gerät-zu-Cloud-Nachrichten][5]</span><span class="sxs-lookup"><span data-stu-id="762de-116">[Process device-to-cloud messages][5]</span></span> | <span data-ttu-id="762de-117">Senden von Nachrichten von einem simulierten Gerät und deren Verarbeitung in der Cloud.</span><span class="sxs-lookup"><span data-stu-id="762de-117">Send messages from a simulated device and process them in the cloud.</span></span> |
|<span data-ttu-id="762de-118">**Event Hub**</span><span class="sxs-lookup"><span data-stu-id="762de-118">**Event Hub**</span></span>|
| <span data-ttu-id="762de-119">[Senden von Ereignissen an einen Event Hub][6]</span><span class="sxs-lookup"><span data-stu-id="762de-119">[Send events to an Event Hub][6]</span></span> | <span data-ttu-id="762de-120">Senden von Ereignissen an einen Event Hub über eine Konsolenanwendung.</span><span class="sxs-lookup"><span data-stu-id="762de-120">Send events to Event hub from a console application.</span></span>
| <span data-ttu-id="762de-121">[Empfangen von Ereignissen von Event Hubs][7]</span><span class="sxs-lookup"><span data-stu-id="762de-121">[Receive events from Event Hubs][7]</span></span> | <span data-ttu-id="762de-122">Empfangen Sie Nachrichten, und verarbeiten Sie sie parallel.</span><span class="sxs-lookup"><span data-stu-id="762de-122">Receive messages and process them in parallel.</span></span>


[1]: /azure/service-bus-messaging/service-bus-dotnet-get-started-with-queues
[2]: /azure/service-bus-messaging/service-bus-dotnet-how-to-use-topics-subscriptions
[3]: /azure/service-bus-messaging/service-bus-amqp-dotnet
[4]: /azure/iot-hub/iot-hub-csharp-csharp-getstarted
[5]: /azure/iot-hub/iot-hub-csharp-csharp-process-d2c
[6]: /azure/event-hubs/event-hubs-dotnet-standard-getstarted-send
[7]: /azure/event-hubs/event-hubs-dotnet-standard-getstarted-receive-eph


