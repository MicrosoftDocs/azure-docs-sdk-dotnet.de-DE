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
# <a name="azure-iot-libraries-for-net"></a>Azure IoT-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

[Azure IoT Hub](https://azure.microsoft.com/services/iot-hub/) ist ein vollständig verwalteter Dienst, der eine zuverlässige und sichere bidirektionale Kommunikation zwischen Millionen von Geräten und einem Lösungs-Back-End ermöglicht.

Geräte und Datenquellen in einer IoT-Lösung können von einem einfachen, mit dem Netzwerk verbundenen Sensor bis zu einem leistungsstarken, eigenständigen Computinggerät reichen. Verarbeitungsfunktionen, Arbeitsspeicher, Kommunikationsbandbreite und Kommunikationsprotokollunterstützung der Geräte können begrenzt sein. Die IoT-[Geräte-SDKs](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide-sdks) ermöglichen Ihnen, Clientanwendungen für eine Vielzahl von Geräten und Back-End-Anwendungen zu implementieren.

Das Geräte-SDK für .NET erleichtert das Erstellen von .NET ausführenden Geräten, die eine Verbindung mit Azure IoT Hub herstellen können.

Das Dienst-SDK für .NET erleichtert das Erstellen von Back-End-Anwendungen mit .NET, die das Verwalten und Steuern von Geräten aus der Cloud ermöglichen.

[Dokumentation zu IoT Hub](https://docs.microsoft.com/azure/iot-hub/).


## <a name="client-library"></a>Clientbibliothek

Verwenden Sie den .NET IoT-Geräteclient, um eine Verbindung mit Ihrem IoT Hub herzustellen und Nachrichten an ihn zu senden.

Installieren Sie das [NuGet-Paket]( https://www.nuget.org/packages/Microsoft.Azure.Devices.Client) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Devices.Client
```

```bash
dotnet add package Microsoft.Azure.Devices.Client
```
### <a name="code-examples"></a>Codebeispiele 

In diesem Beispiel wird eine Verbindung mit dem IoT Hub hergestellt und eine Nachricht pro Sekunde gesendet.

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
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/iot/client)

## <a name="samples"></a>Beispiele

- [Generic Web Service to Event Hub scenario](https://azure.microsoft.com/resources/samples/event-hubs-dotnet-importfromweb/) (Szenario: generischer Webdienst zu Event Hub)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=iot-hub) von Azure IoT-Upsamples an.

Weitere Informationen finden Sie im [Entwicklungsleitfaden für Azure IoT Hub](https://docs.microsoft.com/azure/iot-hub/iot-hub-devguide).

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
