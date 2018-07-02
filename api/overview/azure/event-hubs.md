---
title: Azure Event Hubs-Bibliotheken für .NET
description: Referenz für Azure Event Hubs-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Event Hubs
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: event-hubs
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 5502ae24574c7883c34522ae18ca81bb516a33d2
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065310"
---
# <a name="azure-event-hubs-libraries-for-net"></a>Azure Event Hubs-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Event Hubs ist eine extrem skalierbare Datenstreamingplattform und ein Ereigniserfassungsdienst.

Weitere Informationen zu Azure Event Hubs finden Sie im Artikel [Was ist Event Hubs?](/azure/event-hubs/event-hubs-what-is-event-hubs).  Lesen Sie zum Einstieg den [Programmierleitfaden für Event Hubs](/azure/event-hubs/event-hubs-programming-guide).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie den Event Hubs-Client zum Senden und Empfangen von Nachrichten an und von Event Hubs.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.EventHubs) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.EventHubs
```

```bash
dotnet add package Microsoft.Azure.EventHubs
```

### <a name="code-example"></a>Codebeispiel

Der folgende Code erstellt einen Event Hubs-Client und sendet eine Nachricht an den Hub.

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
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/eventhub/client)

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Event Hubs-Verwaltungsbibliothek zum Erstellen, Aktualisieren und Entfernen von Hubs und Verbrauchergruppen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.EventHub) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.EventHub
```

```bash
dotnet add package Microsoft.Azure.Management.EventHub
```

### <a name="code-example"></a>Codebeispiel

Mit dem folgenden Code wird ein neuer Event Hub erstellt.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/eventhub/management)

## <a name="tutorials"></a>Tutorials

* [Senden von Ereignissen an Azure Event Hubs mithilfe von .NET Framework](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-send)

* [Empfangen von Ereignissen von Azure Event Hubs mithilfe von .NET Framework](/azure/event-hubs/event-hubs-dotnet-framework-getstarted-receive-eph)

## <a name="samples"></a>Beispiele

* [Azure Event Hubs-Beispiele](https://github.com/Azure/azure-event-hubs/tree/master/samples)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
