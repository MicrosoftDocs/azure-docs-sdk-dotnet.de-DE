---
title: Azure IoT-Bibliotheken für .NET
description: Referenz für Azure IoT-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: iot-hub
ms.openlocfilehash: 54182d8fabec0d3aee3ca3b58c7315bdf43cc24e
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190183"
---
# <a name="azure-iot-libraries-for-net"></a><span data-ttu-id="96c28-103">Azure IoT-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="96c28-103">Azure IoT libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="96c28-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="96c28-104">Overview</span></span>

<span data-ttu-id="96c28-105">[Azure IoT Hub](https://azure.microsoft.com/services/iot-hub/) ist ein vollständig verwalteter Dienst, der eine zuverlässige und sichere bidirektionale Kommunikation zwischen Millionen von Geräten und einem Lösungs-Back-End ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="96c28-105">[Azure IoT Hub](https://azure.microsoft.com/services/iot-hub/) is a fully managed service that enables reliable and secure bi-directional communications between millions of devices and a solution back end.</span></span>

<span data-ttu-id="96c28-106">Geräte und Datenquellen in einer IoT-Lösung können von einem einfachen, mit dem Netzwerk verbundenen Sensor bis zu einem leistungsstarken, eigenständigen Computinggerät reichen.</span><span class="sxs-lookup"><span data-stu-id="96c28-106">Devices and data sources in an IoT solution can range from a simple network-connected sensor to a powerful, standalone computing device.</span></span> <span data-ttu-id="96c28-107">Verarbeitungsfunktionen, Arbeitsspeicher, Kommunikationsbandbreite und Kommunikationsprotokollunterstützung der Geräte können begrenzt sein.</span><span class="sxs-lookup"><span data-stu-id="96c28-107">Devices may have limited processing capability, memory, communication bandwidth, and communication protocol support.</span></span> <span data-ttu-id="96c28-108">Die IoT-[Geräte-SDKs](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-sdks) ermöglichen Ihnen, Clientanwendungen für eine Vielzahl von Geräten und Back-End-Anwendungen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="96c28-108">The IoT [device SDKs](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-sdks) enable you to implement client applications for a wide variety of devices and back-end applications.</span></span>

<span data-ttu-id="96c28-109">Das Geräte-SDK für .NET erleichtert das Erstellen von .NET ausführenden Geräten, die eine Verbindung mit Azure IoT Hub herstellen können.</span><span class="sxs-lookup"><span data-stu-id="96c28-109">The device SDK for .NET facilitates building devices running .NET that connect to Azure IoT Hub.</span></span>

<span data-ttu-id="96c28-110">Das Dienst-SDK für .NET erleichtert das Erstellen von Back-End-Anwendungen mit .NET, die das Verwalten und Steuern von Geräten aus der Cloud ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="96c28-110">The service SDK for .NET facilitates building back-end applications using .NET that manage and allow controlling devices from the Cloud.</span></span>

<span data-ttu-id="96c28-111">[Dokumentation zu IoT Hub](https://docs.microsoft.com/azure/iot-hub/).</span><span class="sxs-lookup"><span data-stu-id="96c28-111">[Learn more about Azure IoT](https://docs.microsoft.com/azure/iot-hub/).</span></span>


## <a name="client-library"></a><span data-ttu-id="96c28-112">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="96c28-112">Client library</span></span>

<span data-ttu-id="96c28-113">Verwenden Sie den .NET IoT-Geräteclient, um eine Verbindung mit Ihrem IoT Hub herzustellen und Nachrichten an ihn zu senden.</span><span class="sxs-lookup"><span data-stu-id="96c28-113">Use the .NET IoT devices client to connect and send messages to your IoT Hub.</span></span>

<span data-ttu-id="96c28-114">Installieren Sie das [NuGet-Paket]( https://www.nuget.org/packages/Microsoft.Azure.Devices.Client) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="96c28-114">Install the [NuGet package]( https://www.nuget.org/packages/Microsoft.Azure.Devices.Client) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="96c28-115">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="96c28-115">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Devices.Client
```

```bash
dotnet add package Microsoft.Azure.Devices.Client
```
### <a name="code-examples"></a><span data-ttu-id="96c28-116">Codebeispiele</span><span class="sxs-lookup"><span data-stu-id="96c28-116">Code Examples</span></span> 

<span data-ttu-id="96c28-117">In diesem Beispiel wird eine Verbindung mit dem IoT Hub hergestellt und eine Nachricht pro Sekunde gesendet.</span><span class="sxs-lookup"><span data-stu-id="96c28-117">This example connects to the IoT Hub and sends one message per second.</span></span>

```csharp
string deviceKey = "<deviceKey>";
string deviceId = "<deviceId>";
string iotHubHostName = "<IoTHubHostname>";
DeviceAuthenticationWithRegistrySymmetricKeyvar deviceAuthentication = new DeviceAuthenticationWithRegistrySymmetricKey(deviceId, deviceKey);

DeviceClient deviceClient = DeviceClient.Create(iotHubHostName, deviceAuthentication, TransportType.Mqtt);

while (true)
{
    double currentTemperature = 20 + Rand.NextDouble() * 15;
    double currentHumidity = 60 + Rand.NextDouble() * 20;

    var telemetryDataPoint = new
    {
        messageId = _messageId++,
        deviceId = deviceId,
        temperature = currentTemperature,
        humidity = currentHumidity
    };
    string messageString = JsonConvert.SerializeObject(telemetryDataPoint);
    Message message = new Message(Encoding.ASCII.GetBytes(messageString));
    message.Properties.Add("temperatureAlert", (currentTemperature > 30) ? "true" : "false");

    await deviceClient.SendEventAsync(message);
    Console.WriteLine("{0} > Sending message: {1}", DateTime.Now, messageString);

    await Task.Delay(1000);
}
```


> [!div class="nextstepaction"]
> [<span data-ttu-id="96c28-118">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="96c28-118">Explore the client APIs</span></span>](/dotnet/api/overview/azure/iot/client)

## <a name="samples"></a><span data-ttu-id="96c28-119">Beispiele</span><span class="sxs-lookup"><span data-stu-id="96c28-119">Samples</span></span>

- <span data-ttu-id="96c28-120">[Generic Web Service to Event Hub scenario](https://azure.microsoft.com/resources/samples/event-hubs-dotnet-importfromweb/) (Szenario: generischer Webdienst zu Event Hub)</span><span class="sxs-lookup"><span data-stu-id="96c28-120">[Generic Web Service to Event Hub scenario](https://azure.microsoft.com/resources/samples/event-hubs-dotnet-importfromweb/)</span></span>

<span data-ttu-id="96c28-121">Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=iot-hub) von Azure IoT-Upsamples an.</span><span class="sxs-lookup"><span data-stu-id="96c28-121">View the [complete list](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=iot-hub) of Azure IoT Upsamples.</span></span>

<span data-ttu-id="96c28-122">Weitere Informationen finden Sie im [Entwicklungsleitfaden für Azure IoT Hub](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide).</span><span class="sxs-lookup"><span data-stu-id="96c28-122">View the [Azure IoT Hub developer guide](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide) for more guidance.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
