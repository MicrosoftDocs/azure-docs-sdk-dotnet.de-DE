---
title: Migrieren einer ASP.NET-Webanwendung zu einem virtuellen Azure-Computer
description: Hier erfahren Sie, wie Sie eine ASP.NET-Webanwendung aus einer lokalen Umgebung zu einem virtuellen Azure-Computer migrieren.
keywords: Azure .NET, ASP.NET, VM, virtueller Computer, migrieren, Migration
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
layout: LandingPage
ms.topic: landing-page
ms.technology: azure
ms.devlang: dotnet
ms.service: virtual-machines
ms.custom: devcenter
ms.openlocfilehash: 98f24553961793623f8a6aba10dcf45b930101fe
ms.sourcegitcommit: 3e904e6e4f04f1c92d729459434c85faff32e386
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2017
ms.locfileid: "26588483"
---
# <a name="migrate-an-aspnet-web-application-to-an-azure-virtual-machine"></a>Migrieren einer ASP.NET-Webanwendung zu einem virtuellen Azure-Computer

In diesem Übersichtsdokument erfahren Sie, wie Sie eine ASP.NET-Webanwendung aus einer lokalen Umgebung zu einem virtuellen Azure-Computer migrieren.

## <a name="quickstart"></a>Schnellstart

Informationen zum Erstellen eines virtuellen Computers und Veröffentlichen Ihrer App darauf:

<div class="ico48Case">
    <div class="ico48Link">
        <a href="https://tutorials.visualstudio.com/aspnet-vm/intro">
            <img width="48" height="48" alt="Publish to an Azure VM" src="https://docs.microsoft.com/azure/media/index/virtualmachine.svg">
            <span>Veröffentlichen auf einem virtuellen Azure-Computer</span>
        </a>
    </div>
</div>

## <a name="get-started"></a>Erste Schritte

Die folgenden Tutorials zeigen Schritt für Schritt, wie Sie einen virtuellen Computer erstellen (oder migrieren), Ihre Webanwendung für den virtuellen Computer veröffentlichen und andere Aufgaben durchführen, die ggf. erforderlich sind, damit Ihre Anwendung in Azure unterstützt wird.

- Erstellen Sie mithilfe einer der folgenden Optionen einen virtuellen Computer für Ihre ASP.NET-Anwendung in Azure:
    - [Erstellen eines neuen virtuellen Computers für ASP.NET-Anwendungen](https://go.microsoft.com/fwlink/?linkid=863237)
    - [Migrieren eines lokalen virtuellen Computers](https://docs.microsoft.com/azure/site-recovery/tutorial-migrate-on-premises-to-azure)
- [Veröffentlichen Ihrer App mithilfe von Visual Studio](https://go.microsoft.com/fwlink/?linkid=863240)
- [Erstellen eines sicheren virtuellen Netzwerks für Ihre virtuellen Computer](https://docs.microsoft.com/azure/virtual-network/virtual-network-get-started-vnet-subnet)
- [Erstellen einer CI/CD-Pipeline für Ihre Anwendung](https://docs.microsoft.com/vsts/build-release/apps/cd/deploy-webdeploy-iis-deploygroups)
- [Verwenden einer VM-Skalierungsgruppe für hohe Verfügbarkeit und Skalierbarkeit](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app)

## <a name="considerations"></a>Überlegungen

### <a name="benefits"></a>Vorteile

Mit virtuellen Computern lässt sich eine Anwendung am einfachsten aus der lokalen Umgebung zur Cloud migrieren.  Sie ermöglichen die Replizierung der gleichen Umgebung, die Ihre Anwendung auch lokal verwendet, haben aber den Vorteil, dass Sie keine eigenen Rechenzentren mehr verwalten müssen.  VM-Skalierungsgruppen bieten hohe Verfügbarkeit und Skalierbarkeit für Anwendungen, die in Virtual Machines ausgeführt werden.

### <a name="virtual-machine-size"></a>VM-Größe

Wählen Sie eine VM-Größe und einen VM-Typ, die am besten für Ihre Workload geeignet sind.  Weitere Informationen finden Sie unter [Größen für virtuelle Windows-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/windows/sizes).

### <a name="maintenance"></a>Wartung 

Virtuelle Computer müssen genau wie lokale Computer gewartet und aktualisiert werden<sup>&#42;</sup>.  Bei Anwendungen, die in einer PaaS-Umgebung (Plattform-as-a-Service) wie etwa [Azure App Service](https://docs.microsoft.com/azure/app-service/) oder in einem [Container](https://docs.microsoft.com/azure/app-service/containers/) ausgeführt werden können, entfällt diese Aufgabe.

*<sup>&#42;</sup>[Automatische Betriebssystemupgrades für Azure-VM-Skalierungsgruppen](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade) stehen derzeit als Vorschauversion zur Verfügung.*

### <a name="virtual-networks"></a>Virtuelle Netzwerke

Virtuelle Azure-Netzwerke ermöglichen Folgendes:
- Erstellen einer von Ihnen kontrollierten Hybridinfrastruktur
- Verwenden eigener IP-Adressen und DNS-Server
- Schaffen einer isolierten und hochsicheren Umgebung für Ihre Anwendungen
- Herstellen einer Verbindung zwischen Ihrem virtuellen Computer und Ihrem lokalen Netzwerk über eine der verfügbaren [Verbindungsoptionen](https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-about-vpngateways#s2smulti)
- Integrieren Ihres virtuellen Computers in Ihr lokales Netzwerk mithilfe von [ExpressRoute](https://azure.microsoft.com/services/expressroute/)

Informationen zu den ersten Schritten finden Sie in der [Dokumentation zu Virtual Network](https://docs.microsoft.com/azure/virtual-network/).

### <a name="active-directory"></a>Active Directory
Viele Anwendungen verwenden Active Directory für die Authentifizierung und Identitätsverwaltung.  
- Mit Azure AD Connect können Sie Ihre lokalen Verzeichnisse in Azure Active Directory integrieren.  Informationen zu den ersten Schritten finden Sie unter [Integrieren Ihrer lokalen Verzeichnisse in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).  
- Alternativ können Sie Ihrer Anwendung mit [ExpressRoute](https://azure.microsoft.com/services/expressroute/) den Zugriff auf Ihr lokales Active Directory ermöglichen.

### <a name="sql-databases"></a>SQL-DATENBANKEN

Wenn Ihre Anwendung eine lokale Datenbank verwendet, kann sie standardmäßig nicht mit ihr kommunizieren. Sie haben folgende Möglichkeiten:
- Konfigurieren Sie ein Hybridnetzwerk, über das Ihre Anwendung auf die lokal ausgeführte Datenbank zugreifen kann.  
- Migrieren Sie Ihre Datenbank zu Azure.  Weitere Informationen zum Migrieren einer SQL Server-Datenbank zu Azure finden Sie [hier](dotnet-howto-migrate-sql.md).

### <a name="high-availability-and-scalability"></a>Hochverfügbarkeit und Skalierbarkeit

#### <a name="virtual-machine-scale-sets"></a>Skalierungsgruppen für virtuelle Computer
Wenn Ihre Anwendung hochverfügbar und skalierbar sein soll, empfiehlt es sich, das VM-Image zu einer Azure-VM-Skalierungsgruppe zu migrieren, um die Verfügbarkeit und Skalierbarkeit der Anwendung zu verbessern.  Mit VM-Skalierungsgruppen können Sie einen bereits konfigurierten virtuellen Computer verwenden oder eine Buildpipeline für die Erstellung eines Images mit Ihrer Anwendung einrichten.  

Informationen zu den ersten Schritten finden Sie unter [Bereitstellen der App in VM-Skalierungsgruppen](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app).

#### <a name="centralized-logging"></a>Zentralisierte Protokollierung
Wenn Ihre Anwendung über mehrere Instanzen hinweg ausgeführt wird, empfiehlt es sich unter Umständen, die Protokolle an einem zentralen Ort zu speichern – beispielsweise in [Azure Storage](https://docs.microsoft.com/azure/storage/).

## <a name="next-steps"></a>Nächste Schritte

> [!div class="nextstepaction"]
> [Migrieren einer SQL Server-Datenbank zu Azure](dotnet-howto-migrate-sql.md)