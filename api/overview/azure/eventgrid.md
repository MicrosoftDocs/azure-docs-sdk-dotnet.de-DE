---
title: Azure Event Grid-Bibliotheken für .NET
description: Referenz für Azure Event Grid-Bibliotheken für .NET
author: rloutlaw
ms.author: routlaw
manager: angerobe
ms.date: 04/16/2018
ms.topic: reference
ms.devlang: dotnet
ms.service: event-grid
ms.custom: devcenter
ms.openlocfilehash: 894b8a5beaf0507ab50e8eed6a5ab20d10a71ba6
ms.sourcegitcommit: 61638b504b6c4d96b357894835c80c2680a99fe6
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/17/2018
ms.locfileid: "45750598"
---
# <a name="azure-event-grid-libraries-for-net"></a>Azure Event Grid-Bibliotheken für .NET

Buildereignisgesteuerte Anwendungen, die mit einfacher HTTP-basierter Ereignisbehandlung und Azure Event Grid auf Ereignisse von Azure-Diensten und benutzerdefinierten Quellen lauschen und reagieren

[Weitere Informationen](/azure/event-grid/overview) zu Azure Event Grid und erste Schritte mit dem [Tutorial zu Azure Blob Storage-Ereignissen](/azure/storage/blobs/storage-blob-event-quickstart-powershell) 

## <a name="client-sdk"></a>Client-SDK

Mit dem Client-SDK von Azure Event Grid können Sie Ereignisse erstellen, die Authentifizierung durchführen und Beiträge in Themen posten.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.EventGrid
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.EventGrid 
```

### <a name="publish-events"></a>Veröffentlichen von Ereignissen

Der folgende Code authentifiziert sich mit Azure und veröffentlicht `List` von `EventGridEvent`-Ereignissen eines benutzerdefinierten Typs (in diesem Beispiel `Contoso.Items.ItemsReceivedEvent`) in einem Thema. Der im Beispiel verwendete Schlüssel und die Endpunktadresse des Themas können über Azure PowerShell abgerufen werden:

```powershell
$endpoint = (Get-AzureRmEventGridTopic -ResourceGroupName gridResourceGroup -Name <topic-name>).Endpoint
$keys = Get-AzureRmEventGridTopicKey -ResourceGroupName gridResourceGroup -Name <topic-name>
```

```csharp
string topicEndpoint = "https://<topic-name>.<region>-1.eventgrid.azure.net/api/events";
string topicKey = "<topic-key>";
string topicHostname = new Uri(topicEndpoint).Host;

TopicCredentials topicCredentials = new TopicCredentials(topicKey);
EventGridClient client = new EventGridClient(topicCredentials);

client.PublishEventsAsync(topicHostname, GetEventsList()).GetAwaiter().GetResult();
Console.Write("Published events to Event Grid.");

static IList<EventGridEvent> GetEventsList()
{
    List<EventGridEvent> eventsList = new List<EventGridEvent>();
    for (int i = 0; i < 1; i++)
    {
        eventsList.Add(new EventGridEvent()
        {
            Id = Guid.NewGuid().ToString(),
            EventType = "Contoso.Items.ItemReceivedEvent",
            Data = new ContosoItemReceivedEventData()
            {
                ItemUri = "ContosoSuperItemUri"
            },

            EventTime = DateTime.Now,
            Subject = "Door1",
            DataVersion = "2.0"
        });
    }
    return eventsList;
}
```

### <a name="consume-events"></a>Nutzen von Ereignissen

In diesem Codeausschnitt werden Ereignisse genutzt, z.B. das benutzerdefinierte Ereignis `Contoso.Items.ItemsReceived` sowie Ereignisse, die über andere Azure-Dienste, z.B. Blob Storage, ausgelöst werden.

```csharp
string response = string.Empty;
string requestContent = await req.Content.ReadAsStringAsync();

EventGridSubscriber eventGridSubscriber = new EventGridSubscriber();

// Optionally add one or more custom event type mappings
eventGridSubscriber.AddOrUpdateCustomEventMapping("Contoso.Items.ItemReceived", typeof(ContosoItemReceivedEventData));

var events = eventGridSubscriber.DeserializeEventGridEvents(requestContent);            
 
foreach (EventGridEvent receivedEvent in events)
{
    if (receivedEvent.Data is SubscriptionValidationEventData)
    {
        SubscriptionValidationEventData eventData = (SubscriptionValidationEventData)receivedEvent.Data;
        log.Info($"Got SubscriptionValidation event data, validationCode: {eventData.ValidationCode},  validationUrl: {eventData.ValidationUrl}, topic: {eventGridEvent.Topic}");
        // Handle subscription validation
    }
    else if (receivedEvent.Data is StorageBlobCreatedEventData)
    {
        StorageBlobCreatedEventData eventData = (StorageBlobCreatedEventData)receivedEvent.Data;
        log.Info($"Got BlobCreated event data, blob URI {eventData.Url}");
        // Handle StorageBlobCreatedEventData
    }
    else if (receivedEvent.Data is ContosoItemReceivedEventData)
    {
        ContosoItemReceivedEventData eventData = (ContosoItemReceivedEventData)receivedEvent.Data;
    }
}
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/eventgrid/client)

## <a name="management-sdk"></a>Verwaltungs-SDK

Das Verwaltungs-SDK ermöglicht Ihnen das Erstellen, Aktualisieren und Löschen von Event Grid-Instanzen, -Themen und -Abonnements.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].


#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.EventGrid
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.EventGrid
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/eventgrid/management)

## <a name="learn-more"></a>Weitere Informationen

- [Receive events using the Event Grid SDK](/azure/event-grid/receive-events) (Empfangen von Ereignissen mithilfe des Event Grid SDK)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
