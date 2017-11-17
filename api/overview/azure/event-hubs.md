---
title: "Azure Event Hubs-Bibliotheken für .NET"
description: "Referenz für Azure Event Hubs-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Event Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: event-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2ec234959ffc46d2399d1c763e05f173a311b0d2
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
---
# <a name="azure-event-hubs-libraries-for-net"></a><span data-ttu-id="50d4f-104">Azure Event Hubs-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="50d4f-104">Azure Event Hubs libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="50d4f-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="50d4f-105">Overview</span></span>

<span data-ttu-id="50d4f-106">Azure Event Hubs ist eine extrem skalierbare Datenstreamingplattform und ein Ereigniserfassungsdienst.</span><span class="sxs-lookup"><span data-stu-id="50d4f-106">Azure Event Hubs is a highly scalable data streaming platform and event ingestion service.</span></span>

<span data-ttu-id="50d4f-107">Weitere Informationen zu Azure Event Hubs finden Sie im Artikel [Was ist Event Hubs?](/azure/event-hubs/event-hubs-what-is-event-hubs).</span><span class="sxs-lookup"><span data-stu-id="50d4f-107">To learn more about Azure Event Hubs, read the article [What is Event Hubs?](/azure/event-hubs/event-hubs-what-is-event-hubs).</span></span>  <span data-ttu-id="50d4f-108">Lesen Sie zum Einstieg den [Programmierleitfaden für Event Hubs](/azure/event-hubs/event-hubs-programming-guide).</span><span class="sxs-lookup"><span data-stu-id="50d4f-108">To get started, check out the [Event Hubs Programming Guide](/azure/event-hubs/event-hubs-programming-guide).</span></span>

## <a name="client-library"></a><span data-ttu-id="50d4f-109">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="50d4f-109">Client library</span></span>

<span data-ttu-id="50d4f-110">Verwenden Sie den Event Hubs-Client zum Senden und Empfangen von Nachrichten an und von Event Hubs.</span><span class="sxs-lookup"><span data-stu-id="50d4f-110">Use the Event Hubs client to send and receive messages to and from Event Hubs.</span></span>

<span data-ttu-id="50d4f-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.EventHubs) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="50d4f-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.EventHubs) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="50d4f-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="50d4f-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.EventHubs
```

```bash
dotnet add package Microsoft.Azure.EventHubs
```

### <a name="code-example"></a><span data-ttu-id="50d4f-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="50d4f-113">Code Example</span></span>

<span data-ttu-id="50d4f-114">Der folgende Code erstellt einen Event Hubs-Client und sendet eine Nachricht an den Hub.</span><span class="sxs-lookup"><span data-stu-id="50d4f-114">The following code creates an Event Hubs client and sends a message to the hub.</span></span>

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
> [<span data-ttu-id="50d4f-115">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="50d4f-115">Explore the client APIs</span></span>](/dotnet/api/overview/azure/eventhub/client)

## <a name="management-library"></a><span data-ttu-id="50d4f-116">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="50d4f-116">Management library</span></span>

<span data-ttu-id="50d4f-117">Verwenden Sie die Event Hubs-Verwaltungsbibliothek zum Erstellen, Aktualisieren und Entfernen von Hubs und Verbrauchergruppen.</span><span class="sxs-lookup"><span data-stu-id="50d4f-117">Use the Event Hubs management library to create, update, and remove hubs and consumer groups.</span></span>

<span data-ttu-id="50d4f-118">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="50d4f-118">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="50d4f-119">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="50d4f-119">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.EventHub
```

```bash
dotnet add package Microsoft.Azure.Management.EventHub
```

### <a name="code-example"></a><span data-ttu-id="50d4f-120">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="50d4f-120">Code Example</span></span>

<span data-ttu-id="50d4f-121">Mit dem folgenden Code wird ein neuer Event Hub erstellt.</span><span class="sxs-lookup"><span data-stu-id="50d4f-121">The following code creates a new event hub.</span></span>

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
> [<span data-ttu-id="50d4f-122">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="50d4f-122">Explore the management APIs</span></span>](/dotnet/api/overview/azure/eventhub/management)

## <a name="tutorials"></a><span data-ttu-id="50d4f-123">Lernprogramme</span><span class="sxs-lookup"><span data-stu-id="50d4f-123">Tutorials</span></span>

* [<span data-ttu-id="50d4f-124">Senden von Ereignissen an Azure Event Hubs mithilfe von .NET Framework</span><span class="sxs-lookup"><span data-stu-id="50d4f-124">Send events to Azure Event Hubs using the .NET Framework</span></span>](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-send)

* [<span data-ttu-id="50d4f-125">Empfangen von Ereignissen von Azure Event Hubs mithilfe von .NET Framework</span><span class="sxs-lookup"><span data-stu-id="50d4f-125">Receive events from Azure Event Hubs using the .NET Framework</span></span>](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-receive-eph)

## <a name="samples"></a><span data-ttu-id="50d4f-126">Beispiele</span><span class="sxs-lookup"><span data-stu-id="50d4f-126">Samples</span></span>

* [<span data-ttu-id="50d4f-127">Azure Event Hubs-Beispiele</span><span class="sxs-lookup"><span data-stu-id="50d4f-127">Azure Event Hubs Samples</span></span>](https://github.com/Azure/azure-event-hubs/tree/master/samples)

<span data-ttu-id="50d4f-128">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="50d4f-128">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
