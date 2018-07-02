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
ms.openlocfilehash: 922e1a49a2b864d8cd408a8383d7cda27c7f89c2
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065300"
---
# <a name="azure-event-grid-libraries-for-net"></a><span data-ttu-id="6e526-103">Azure Event Grid-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="6e526-103">Azure Event Grid libraries for .NET</span></span>

<span data-ttu-id="6e526-104">Buildereignisgesteuerte Anwendungen, die mit einfacher HTTP-basierter Ereignisbehandlung und Azure Event Grid auf Ereignisse von Azure-Diensten und benutzerdefinierten Quellen lauschen und reagieren</span><span class="sxs-lookup"><span data-stu-id="6e526-104">Build event-driven applications that listen and react to events from Azure services and custom sources using simple HTTP-based event handling with Azure Event Grid.</span></span>

<span data-ttu-id="6e526-105">[Weitere Informationen](/azure/event-grid/overview) zu Azure Event Grid und erste Schritte mit dem [Tutorial zu Azure Blob Storage-Ereignissen](/azure/storage/blobs/storage-blob-event-quickstart-powershell)</span><span class="sxs-lookup"><span data-stu-id="6e526-105">[Learn more](/azure/event-grid/overview) about Azure Event Grid and get started with the [Azure Blob storage event tutorial](/azure/storage/blobs/storage-blob-event-quickstart-powershell).</span></span> 

## <a name="publish-sdk"></a><span data-ttu-id="6e526-106">Veröffentlichungs-SDK</span><span class="sxs-lookup"><span data-stu-id="6e526-106">Publish SDK</span></span>

<span data-ttu-id="6e526-107">Mit dem Veröffentlichungs-SDK von Azure Event Grid können Sie Ereignisse erstellen, die Authentifizierung durchführen und Beiträge in Themen posten.</span><span class="sxs-lookup"><span data-stu-id="6e526-107">Create events, authenticate, and post to topics using the Azure Event Grid publish SDK.</span></span>

<span data-ttu-id="6e526-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="6e526-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6e526-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="6e526-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.EventGrid
```

#### <a name="net-core-cli"></a><span data-ttu-id="6e526-110">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="6e526-110">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.EventGrid 
```

### <a name="sample-usage"></a><span data-ttu-id="6e526-111">Beispielverwendung</span><span class="sxs-lookup"><span data-stu-id="6e526-111">Sample usage</span></span>

<span data-ttu-id="6e526-112">Der folgende Code authentifiziert sich mit Azure und veröffentlicht `List` von `EventGridEvent`-Ereignissen eines benutzerdefinierten Typs (in diesem Beispiel `Contoso.Items.ItemsReceivedEvent`) in einem Thema.</span><span class="sxs-lookup"><span data-stu-id="6e526-112">The following code authenticates with Azure and publishes a `List` of  `EventGridEvent` events of a custom type (in this example, `Contoso.Items.ItemsReceivedEvent` ) to a topic.</span></span> <span data-ttu-id="6e526-113">Der im Beispiel verwendete Schlüssel und die Endpunktadresse des Themas können über Azure PowerShell abgerufen werden:</span><span class="sxs-lookup"><span data-stu-id="6e526-113">The topic key and endpoint address used in the sample can be retrieved from Azure PowerShell:</span></span>

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

<span data-ttu-id="6e526-114">Dieser Codeausschnitt behandelt Ereignisse, die beim Erstellen eines neuen Blobs in [Azure Storage](/azure/storage/blobs/storage-blob-event-overview) veröffentlicht werden.</span><span class="sxs-lookup"><span data-stu-id="6e526-114">This snippet handles events published when creating a new blob in [Azure Storage](/azure/storage/blobs/storage-blob-event-overview).</span></span>

```csharp
string response = string.Empty;
const string SubscriptionValidationEvent = "Microsoft.EventGrid.SubscriptionValidationEvent";
const string StorageBlobCreatedEvent = "Microsoft.Storage.BlobCreated";

string requestContent = await req.Content.ReadAsStringAsync();
EventGridEvent[] eventGridEvents = JsonConvert.DeserializeObject<EventGridEvent[]>(requestContent);

foreach (EventGridEvent eventGridEvent in eventGridEvents)
{
    JObject dataObject = eventGridEvent.Data as JObject;

    // Deserialize the event data into the appropriate type based on event type 
    if (string.Equals(eventGridEvent.EventType, SubscriptionValidationEvent, StringComparison.OrdinalIgnoreCase))
    {
        var eventData = dataObject.ToObject<SubscriptionValidationEventData>();
        log.Info($"Got SubscriptionValidation event data, validation code: {eventData.ValidationCode}, topic: {eventGridEvent.Topic}");

        // Do any additional validation (as required) and then return back the below response
        var responseData = new SubscriptionValidationResponseData();
        responseData.ValidationResponse = eventData.ValidationCode;
        return req.CreateResponse(HttpStatusCode.OK, responseData);
    }

    else if (string.Equals(eventGridEvent.EventType, StorageBlobCreatedEvent, StringComparison.OrdinalIgnoreCase))
    {
        var eventData = dataObject.ToObject<StorageBlobCreatedEventData>();
        log.Info($"Got BlobCreated event data, blob URI {eventData.Url}");
    }
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="6e526-115">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="6e526-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/eventgrid/client)

## <a name="management-sdk"></a><span data-ttu-id="6e526-116">Verwaltungs-SDK</span><span class="sxs-lookup"><span data-stu-id="6e526-116">Management SDK</span></span>

<span data-ttu-id="6e526-117">Das Verwaltungs-SDK ermöglicht Ihnen das Erstellen, Aktualisieren und Löschen von Event Grid-Instanzen, -Themen und -Abonnements.</span><span class="sxs-lookup"><span data-stu-id="6e526-117">Create, update, or delete Event Grid instances, topics, and subscriptions with the management SDK.</span></span>

<span data-ttu-id="6e526-118">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="6e526-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Network.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>


#### <a name="visual-studio-package-manager"></a><span data-ttu-id="6e526-119">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="6e526-119">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.EventGrid
```

#### <a name="net-core-cli"></a><span data-ttu-id="6e526-120">.NET Core CLI</span><span class="sxs-lookup"><span data-stu-id="6e526-120">.NET Core CLI</span></span>

```bash
dotnet add package Microsoft.Azure.Management.EventGrid
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="6e526-121">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="6e526-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/eventgrid/management)

## <a name="learn-more"></a><span data-ttu-id="6e526-122">Weitere Informationen</span><span class="sxs-lookup"><span data-stu-id="6e526-122">Learn more</span></span>

- <span data-ttu-id="6e526-123">[Receive events using the Event Grid SDK](/azure/event-grid/receive-events) (Empfangen von Ereignissen mithilfe des Event Grid SDK)</span><span class="sxs-lookup"><span data-stu-id="6e526-123">[Receive events using the Event Grid SDK](/azure/event-grid/receive-events)</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
