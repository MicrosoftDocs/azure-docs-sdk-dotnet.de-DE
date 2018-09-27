---
title: Azure .NET-APIs
description: Übersicht über die Azure-APIs für .NET
ms.date: 10/19/2017
ms.openlocfilehash: 04997caa99ed60db6ad98cabbc72b36bfbf99f4d
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190133"
---
# <a name="azure-net-apis"></a>Azure .NET-APIs

Die Azure .NET-APIs ermöglichen Ihnen das Nutzen von Azure-Diensten und Verwalten von Azure-Ressourcen mithilfe Ihres Anwendungscodes. Die APIs stehen als [NuGet-Pakete](/dotnet/api/overview/azure/) für die Verwendung in Ihren .NET-Projekten zur Verfügung. 

## <a name="manage-azure-resources"></a>Verwalten von Azure-Ressourcen

Der Azure-Bibliotheken für .NET ermöglichen Ihnen das Erstellen und Verwalten von Azure-Ressourcen mithilfe Ihrer .NET-Anwendungen.

Viele der Pakete für die Verwaltung von Azure-Ressourcen verfügen über eine [Fluent](dotnet-sdk-azure-concepts.md)-Benutzeroberfläche, um Ressourcen genau Ihren Anforderungen entsprechend zu konfigurieren. Zum Erstellen eines virtuellen Windows-Computers müssen Sie beispielsweise den folgenden Code schreiben:

```csharp
var windowsVM = azure.VirtualMachines.Define(windowsVmName)
    .WithRegion(Region.USEast)
    .WithNewResourceGroup(rgName)
    .WithNewPrimaryNetwork("10.0.0.0/28")
    .WithPrimaryPrivateIPAddressDynamic()
    .WithNewPrimaryPublicIPAddress(publicIpDnsLabel)
    .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
    .WithAdminUsername(username)
    .WithAdminPassword(password)
    .WithSize(VirtualMachineSizeTypes.StandardD3V2)
    .Create();
 ```

Überprüfen Sie die [.NET-Dienstliste](/dotnet/api/overview/azure/), um sofort mit dem Einsatz der Bibliotheken in Ihren Projekten zu beginnen. Lesen Sie dann den [Artikel mit den ersten Schritten](dotnet-sdk-azure-get-started.md) zum Einrichten der Authentifizierung und Ausführung von Beispielcode in Ihrem eigenen Azure-Abonnement.  Im [Artikel zu den Konzepten](dotnet-sdk-azure-concepts.md) werden die Konventionen behandelt, die das SDK befolgt, und wie Sie diese zum Vereinfachen Ihres Anwendungscode nutzen können. Neue Funktionen, wichtige Änderungen und Migrationsanweisungen finden Sie in den [Versionshinweisen](dotnet-sdk-azure-release-notes.md).

## <a name="consume-azure-services"></a>Nutzen von Azure-Diensten

Zusätzlich zur Nutzung von .NET-APIs zum Erstellen und programmgesteuerten Verwalten von Ressourcen in Azure können Sie auch mithilfe der .NET-APIs Ihre Anwendungen mit diesen Ressourcen verbinden und sie zur Laufzeit verwenden.  Sie können z.B. eine Verbindung mit einer SQL-Datenbank herstellen oder Daten in Azure Storage speichern.  Sie können ermitteln, welches NuGet-Paket für einen bestimmten Azure-Dienst verwendet werden soll, indem Sie unsere [vollständige Liste der Dienst-APIs](/dotnet/api/overview/azure/) durchsuchen.  

## <a name="samples"></a>Beispiele

Die folgenden Beispiele decken allgemeine Automatisierungsaufgaben mit den Azure-Bibliotheken für .NET ab:

- [Virtuelle Computer](dotnet-sdk-azure-virtual-machine-samples.md)
- [Web-Apps](dotnet-sdk-azure-web-apps-samples.md)
- [SQL-Datenbank](dotnet-sdk-azure-sql-database-samples.md)

Sowohl in den Dienst- als auch den Verwaltungsbibliotheken ist eine vereinheitlichte [Referenz](/dotnet/api/overview/azure/?view=azure-dotnet) für alle Pakete verfügbar. Neue Funktionen, wichtige Änderungen und Migrationsanweisungen finden Sie in den [Versionshinweisen](dotnet-sdk-azure-release-notes.md).

[!include[Contribute and community](includes/contribute.md)]