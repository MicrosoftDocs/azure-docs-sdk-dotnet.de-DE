---
title: Auswählen der passenden Azure-Hostingoption
description: Hier erfahren Sie, welcher Azure-Migrationspfad für Ihre ASP.NET-Webanwendung der richtige ist.
keywords: Azure .NET, ASP.NET, App Service, VM, virtueller Computer, Web-App, migrieren, Migration
author: CESARDELATORRE
manager: wpickett
ms.author: cesardl
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, casoper
ms.openlocfilehash: dbf54bb1a6e3d612ef8363a6b30e06b388b4490f
ms.sourcegitcommit: 3e904e6e4f04f1c92d729459434c85faff32e386
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2017
ms.locfileid: "26588463"
---
# <a name="choose-the-right-azure-hosting-option"></a>Auswählen der passenden Azure-Hostingoption

Dieses Dokument enthält Informationen zu verschiedenen Aspekten und stellt die Optionen gegenüber, die Ihnen in Azure zur Verfügung stehen, wenn Sie Ihre vorhandenen .NET Framework-Anwendungen aus Ihrer lokalen Umgebung zu Azure migrieren möchten.

Bei der Migration vorhandener .NET-Anwendungen zu Azure sind grundsätzlich folgende Bereiche zu berücksichtigen:

1.  Computeoptionen
2.  Datenbankoptionen
3.  Netzwerk- und Sicherheitsaspekte
4.  Authentifizierungs- und Autorisierungsaspekte

## <a name="compute-choices"></a>Computeoptionen

Bei der Migration vorhandener .NET Framework-Anwendungen zu Azure stehen Ihnen mehrere Optionen zur Verfügung.  Da .NET Framework allerdings auf Windows basiert, beschränken sich die im Anschluss angegebenen Optionen auf Windows-basierte Computedienste.

Die folgende Tabelle enthält verschiedene Gegenüberstellungen und Empfehlungen, um Sie bei der Wahl des passenden Computemigrationspfads für Ihre vorhandene .NET-Anwendung zu unterstützen:

|                 | Virtuelle Azure-Computer | Azure App Service | Windows-Container |
|-----------------|-----------|-------------------|--------------------|
|Einsatzgebiete      |<ul><li>Die Anwendung ist stark vom Server und von lokalen MSI-Installationen abhängig.</li><li>Sie möchten den einfachsten Migrationspfad für die Anwendung nutzen.</li></ul>|Die App ist nicht vom Server abhängig, sondern einfach eine reine ASP.NET-Web-App (MVC, WebForm) oder N-Tier-App (Web-API, WCf), die auf einen Datenbankserver zugreift. |<ul><li>Die Anwendung ist zwar vom Ursprungsserver abhängig, diese Abhängigkeiten können aber in das Docker-Windows-Image aufgenommen werden.</li><li>Sie möchten die App zur Vorbereitung auf [Cloud-DevOps](https://docs.microsoft.com/dotnet/standard/modernize-with-azure-and-containers/lift-and-shift-existing-apps-devops/reasons-to-lift-and-shift-existing-net-apps-to-cloud-devops-ready-applications) modernisieren.</li></ul>|
|Vorteile  |<ul><li>Einfachster Migrationspfad</li><li>Vertraute Umgebung. Die Bereitstellungsumgebung ist ein virtueller Computer und ähnelt somit stark lokalen Servern.</li></ul> |Laufende PaaS-Wartung, einfachste Methode für die Verwaltung und Skalierung von Apps in Azure |<ul><li>Zukunftssicher, für Cloud-DevOps geeignet (mit Abhängigkeiten, die in die Container der App integriert sind)</li><li>Nahezu keine Überarbeitung von .NET-/C#-Code erforderlich</li></ul> |
|Nachteile             |IaaS. Teure Wartung. Sie müssen Netzwerk, Lastenausgleich, horizontale Skalierung, IIS und Ähnliches für die VM-Infrastruktur verwalten. |<ul><li>Nicht alle Apps werden [unterstützt](http://www.migratetoazure.net/ReadinessAssessment).</li><li>Einige Apps müssen zur Unterstützung von Azure App Service möglicherweise überarbeitet werden. Gegebenenfalls muss sogar die Architektur geringfügig angepasst werden.</li></ul> |<ul><li>Lernkurve für Docker</li><li>Änderungen am Code und an den App-Konfigurationseinstellungen</li></ul>|
|Anforderungen |Virtueller Windows Server-Computer mit den gleichen Anforderungen wie bei der App für die lokale Umgebung | Azure App Service-Anforderungen aus der [Kompatibilitätsanalyse für Azure App Service](https://www.migratetoazure.net/Resources) |<ul><li>[Windows Server 2016 mit Containern – virtueller Azure-Computer](https://azuremarketplace.microsoft.com/marketplace/apps/Microsoft.WindowsServer?tab=Overview)<br />oder</li><li>[Azure Container Service (AKS)](https://azure.microsoft.com/services/container-service/) (also Kubernetes-Orchestrator)<br />oder<li>[Azure Service Fabric](https://azure.microsoft.com/services/service-fabric/)-Orchestrator</li></ul> |
|Vorgehensweise zum Migrieren |[Migrieren einer ASP.NET-Webanwendung zu einem virtuellen Azure-Computer](https://go.microsoft.com/fwlink/?linkid=862531) | [Migrieren einer ASP.NET-Webanwendung zu Azure App Service](https://go.microsoft.com/fwlink/?linkid=862532) | Überlegungen, Szenarien und exemplarische Vorgehensweisen finden Sie im E-Book [Modernizing existing .NET apps with Azure and Windows Containers](https://aka.ms/liftandshiftwithcontainersebook) (Modernisieren vorhandener .NET-Apps mit Azure und Windows-Containern). |

 Das folgende Flussdiagramm zeigt eine Entscheidungsstruktur zur Planung einer Migration zu Azure für Ihre vorhandenen .NET Framework-Anwendungen. Option A ist zwar die erste Option, die Sie in Betracht ziehen sollten, Option B ist allerdings einfacher umzusetzen.

![Flussdiagramm mit Hosting-Entscheidungsstruktur](media/dotnet-howto-choose-migration/decision-tree.png)

## <a name="database-choices"></a>Datenbankoptionen

Wenn Sie relationale Datenbanken zu Azure migrieren möchten, haben Sie mehrere Möglichkeiten. Hilfreiche Informationen zur Wahl des passenden Datenbankmigrationspfads für Ihre vorhandene .NET-Anwendung finden Sie unter [Migrieren einer SQL Server-Datenbank zu Azure](https://go.microsoft.com/fwlink/?linkid=862533).

## <a name="networking-and-security-considerations"></a>Netzwerk- und Sicherheitsaspekte

Wenn Sie Anwendungen in einer öffentlichen Cloud wie Microsoft Azure bereitstellen, empfiehlt es sich unter Umständen, bestimmte Netzwerke durch [Erstellen von Netzwerk-DMZs](https://docs.microsoft.com/azure/architecture/reference-architectures/dmz/) zu isolieren und zu schützen – etwa durch eine [DMZ zwischen Azure und Ihrem lokalen Datencenter](https://docs.microsoft.com/azure/architecture/reference-architectures/dmz/secure-vnet-hybrid) oder durch eine [ DMZ zwischen Azure und dem Internet](https://docs.microsoft.com/azure/architecture/reference-architectures/dmz/secure-vnet-dmz). DMZs können mit [Azure Virtual Network](https://docs.microsoft.com/azure/virtual-network/virtual-networks-overview) implementiert werden.
Virtuelle Azure-Netzwerke ermöglichen Folgendes:

- Erstellen einer von Ihnen kontrollierten Hybridinfrastruktur
- Verwenden eigener IP-Adressen und DNS-Server
- Schützen von Verbindungen mit einem IPsec-VPN oder mit ExpressRoute
- Differenzierte Kontrolle über den Datenverkehr zwischen Subnetzen
- Erstellen durchdachter Netzwerktopologien mit virtuellen Geräten
- Schaffen einer isolierten und hochsicheren Umgebung für Ihre Anwendungen
 
Informationen zu den ersten Schritten beim Erstellen eines eigenen virtuellen Netzwerks finden Sie in der [Dokumentation zu Azure Virtual Network](https://docs.microsoft.com/azure/virtual-network/).

## <a name="authentication-and-authorization-considerations-when-migrating-to-azure"></a>Authentifizierungs- und Autorisierungsaspekte bei der Migration zu Azure

Die Sicherheit ist eines der Hauptanliegen von Organisationen, die eine Migration in die Cloud durchführen. Die meisten Unternehmen haben viel Zeit, Geld und Know-how in die Gestaltung und Entwicklung eines Sicherheitsmodells investiert. Daher ist es wichtig, dass ihre Investitionen in Maßnahmen wie Identitätsspeicher und Lösungen für einmaliges Anmelden nicht umsonst waren.

Viele lokal ausgeführte B2E-.NET-Unternehmensanwendungen nutzen zur Authentifizierung und Identitätsverwaltung Active Directory.  Mit Azure AD Connect können Sie Ihre lokalen Verzeichnisse in Azure Active Directory integrieren.  Informationen zu den ersten Schritten finden Sie unter [Integrieren Ihrer lokalen Verzeichnisse in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).

Ausführlichere Informationen zur Azure Active Directory-Planung finden Sie unter [Ermitteln der Identitätsanforderungen für Ihre Hybrid-Identitätslösung](https://docs.microsoft.com/azure/active-directory/active-directory-hybrid-identity-design-considerations-business-needs).

Als Authentifizierungsprotokolle stehen außerdem [OAuth](https://en.wikipedia.org/wiki/OAuth) und [OpenID](https://en.wikipedia.org/wiki/OpenID) zur Verfügung, die häufig in kundenorientierten Anwendungen zum Einsatz kommen.  Bei Verwendung autonomer Identitätsdatenbanken (etwa eine SQL-basierte ASP.NET-Identitätsdatenbank, die unter Verwendung von OAuth in IdentityServer4 eingeschlossen ist) ist in der Regel keine Verbindung mit lokalen Datenbanken oder Verzeichnissen erforderlich.

## <a name="next-steps"></a>Nächste Schritte

> [!div class="nextstepaction"]
> [Migrieren einer ASP.NET-Webanwendung zu Azure App Service](dotnet-howto-migrate-app-service.md)