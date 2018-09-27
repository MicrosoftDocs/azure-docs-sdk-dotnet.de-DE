---
title: Azure Event Hubs-Bibliotheken für .NET
description: Referenz für Azure Event Hubs-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: event-hubs
ms.openlocfilehash: 74c533bef598b90369009d68a759d35d122a368d
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190273"
---
# <a name="azure-event-hubs-libraries-for-net"></a><span data-ttu-id="e97ac-103">Azure Event Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="e97ac-103">Azure Event Hubs libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="e97ac-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="e97ac-104">Overview</span></span>

<span data-ttu-id="e97ac-105">Azure Event Hubs ist eine extrem skalierbare Datenstreamingplattform und ein Ereigniserfassungsdienst.</span><span class="sxs-lookup"><span data-stu-id="e97ac-105">Azure Event Hubs is a highly scalable data streaming platform and event ingestion service.</span></span>

<span data-ttu-id="e97ac-106">Weitere Informationen zu Azure Event Hubs finden Sie im Artikel [Was ist Event Hubs?](/azure/event-hubs/event-hubs-what-is-event-hubs).</span><span class="sxs-lookup"><span data-stu-id="e97ac-106">To learn more about Azure Event Hubs, read the article [What is Event Hubs?](/azure/event-hubs/event-hubs-what-is-event-hubs).</span></span>  <span data-ttu-id="e97ac-107">Lesen Sie zum Einstieg den [Programmierleitfaden für Event Hubs](/azure/event-hubs/event-hubs-programming-guide).</span><span class="sxs-lookup"><span data-stu-id="e97ac-107">To get started, check out the [Event Hubs Programming Guide](/azure/event-hubs/event-hubs-programming-guide).</span></span>

## <a name="client-library"></a><span data-ttu-id="e97ac-108">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="e97ac-108">Client library</span></span>

<span data-ttu-id="e97ac-109">Verwenden Sie den Event Hubs-Client zum Senden und Empfangen von Nachrichten an und von Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="e97ac-109">Use the Event Hubs client to send and receive messages to and from Event Hubs.</span></span>

<span data-ttu-id="e97ac-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.EventHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="e97ac-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.EventHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="e97ac-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="e97ac-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.EventHubs
```

```bash
dotnet add package Microsoft.Azure.EventHubs
```

### <a name="code-example"></a><span data-ttu-id="e97ac-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="e97ac-112">Code Example</span></span>

<span data-ttu-id="e97ac-113">Der folgende Code erstellt einen Event Hubs-Client und sendet eine Nachricht an den Hub.</span><span class="sxs-lookup"><span data-stu-id="e97ac-113">The following code creates an Event Hubs client and sends a message to the hub.</span></span>

```csharp
EventHubsConnectionStringBuilder connectionStringBuilder = new EventHubsConnectionStringBuilder(eventHubConnectionString)
{
    EntityPath = eventHubEntityPath
};

EventHubClient eventHubClient = EventHubClient.CreateFromConnectionString(connectionStringBuilder.ToString());
string message = $"Message {i}";
Console.WriteLine($"Sending message: {message}");
await eventHubClient.SendAsync(new EventData(Encoding.UTF8.GetBytes(message)));
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="e97ac-114">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="e97ac-114">Explore the client APIs</span></span>](/dotnet/api/overview/azure/eventhub/client)

## <a name="management-library"></a><span data-ttu-id="e97ac-115">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="e97ac-115">Management library</span></span>

<span data-ttu-id="e97ac-116">Verwenden Sie die Event Hubs-Verwaltungsbibliothek zum Erstellen, Aktualisieren und Entfernen von Hubs und Verbrauchergruppen.</span><span class="sxs-lookup"><span data-stu-id="e97ac-116">Use the Event Hubs management library to create, update, and remove hubs and consumer groups.</span></span>

<span data-ttu-id="e97ac-117">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="e97ac-117">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="e97ac-118">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="e97ac-118">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.EventHub
```

```bash
dotnet add package Microsoft.Azure.Management.EventHub
```

### <a name="code-example"></a><span data-ttu-id="e97ac-119">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="e97ac-119">Code Example</span></span>

<span data-ttu-id="e97ac-120">Mit dem folgenden Code wird ein neuer Event Hub erstellt.</span><span class="sxs-lookup"><span data-stu-id="e97ac-120">The following code creates a new event hub.</span></span>

```csharp
TokenCredentials creds = new TokenCredentials(token);
EventHubManagementClient ehClient = new EventHubManagementClient(creds)
{
    SubscriptionId = subscriptionId
};

EventHubCreateOrUpdateParameters ehParams = new EventHubCreateOrUpdateParameters()
{
    Location = location
};

Console.WriteLine("Creating Event Hub...");
await ehClient.EventHubs.CreateOrUpdateAsync(resourceGroupName, namespaceName, EventHubName, ehParams);
Console.WriteLine("Created Event Hub successfully.");
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="e97ac-121">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="e97ac-121">Explore the management APIs</span></span>](/dotnet/api/overview/azure/eventhub/management)

## <a name="tutorials"></a><span data-ttu-id="e97ac-122">Lernprogramme</span><span class="sxs-lookup"><span data-stu-id="e97ac-122">Tutorials</span></span>

* [<span data-ttu-id="e97ac-123">Senden von Ereignissen an Azure Event Hubs mithilfe von .NET Framework</span><span class="sxs-lookup"><span data-stu-id="e97ac-123">Send events to Azure Event Hubs using the .NET Framework</span></span>](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-send)

* [<span data-ttu-id="e97ac-124">Empfangen von Ereignissen von Azure Event Hubs mithilfe von .NET Framework</span><span class="sxs-lookup"><span data-stu-id="e97ac-124">Receive events from Azure Event Hubs using the .NET Framework</span></span>](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-receive-eph)

## <a name="samples"></a><span data-ttu-id="e97ac-125">Beispiele</span><span class="sxs-lookup"><span data-stu-id="e97ac-125">Samples</span></span>

* [<span data-ttu-id="e97ac-126">Azure Event Hubs-Beispiele</span><span class="sxs-lookup"><span data-stu-id="e97ac-126">Azure Event Hubs Samples</span></span>](https://github.com/Azure/azure-event-hubs/tree/master/samples)

<span data-ttu-id="e97ac-127">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="e97ac-127">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
