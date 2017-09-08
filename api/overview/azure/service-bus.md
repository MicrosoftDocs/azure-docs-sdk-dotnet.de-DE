---
title: "Azure Service Bus-Bibliotheken für .NET"
description: "Referenz für Azure Service Bus-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Service Bus
author: camsoper
ms.author: casoper
manager: douge
ms.date: 08/01/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: d4d3ac982794fc7533b97fe8c053730b4b39ff58
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-service-bus-libraries-for-net"></a>Azure Service Bus-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview) bietet eine Messaginginfrastruktur, über die Anwendungen Nachrichten austauschen können, um die Skalierbarkeit und Ausfallsicherheit zu verbessern.

## <a name="client-library"></a>Clientbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/WindowsAzure.ServiceBus) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus.

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package WindowsAzure.ServiceBus
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird eine Nachricht an eine Service Bus-Warteschlange gesendet.

```csharp
// using Microsoft.ServiceBus.Messaging;

QueueClient client = QueueClient.CreateFromConnectionString(connectionString, queueName);
BrokeredMessage message = new BrokeredMessage("This is a test message!");
client.Send(message);
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/servicebus/client)


## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ServiceBus.Fluent) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.ServiceBus.Fluent
```

#### <a name="net-core-cli"></a>.NET Core-CLI

```bash
dotnet add package Microsoft.Azure.Management.ServiceBus.Fluent
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird eine Service Bus-Warteschlange mit einer maximalen Größe von 1.024 MB erstellt.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/servicebus/management)

## <a name="samples"></a>Beispiele

- [Getting Started with Service – Service Bus Queue Basic – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-basic-features/) (Erste Schritte mit Dienst – Grundlagen der Service Bus-Warteschlange in .Net)
- [Getting Started with Service – Service Bus Queue Advanced Features – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-queue-with-advanced-features/) (Erste Schritte mit Dienst – erweiterte Funktionen der Service Bus-Warteschlange in .Net)
- [Getting Started with Service – Service Bus Publish Subscribe Basic – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-basic-features/) (Erste Schritte mit Dienst – Grundlagen des Veröffentlichens/Abonnierens mit Service Bus – in .Net)
- [Getting Started with Service – Service Bus Publish Subscribe Advance Features – in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-publish-subscribe-with-advanced-features/) (Erste Schritte mit Dienst – erweiterte Funktionen zum Veröffentlichen/Abonnieren mit Service Bus – in .Net)
- [Getting Started with Service - Service Bus With Claim Based Authorization - in .Net](https://azure.microsoft.com/resources/samples/service-bus-dotnet-manage-with-claims-based-authorization/) (Erste Schritte mit Dienst – Service Bus mit anspruchsbasierter Autorisierung – in .Net)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?term=service+bus) von Beispielen für Azure Service Bus an.


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
