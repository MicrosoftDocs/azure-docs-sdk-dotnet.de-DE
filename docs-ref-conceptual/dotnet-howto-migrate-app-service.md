---
title: Migrieren einer ASP.NET-Webanwendung zu Azure App Service
description: Hier erfahren Sie, wie Sie eine ASP.NET-Webanwendung aus einer lokalen Umgebung zu Azure App Service migrieren.
keywords: Azure .NET, ASP.NET, App Service, Web-App, migrieren, Migration
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: app-service
ms.custom: devcenter
ms.openlocfilehash: 8ad1bcd11a823c1b6f7e592a5990dd6f7ed06e97
ms.sourcegitcommit: ccc95adb96cf7d56ebce5e09bedf10c2d48f5e1f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/21/2017
---
# <a name="migrate-an-aspnet-web-application-to-azure-app-service"></a>Migrieren einer ASP.NET-Webanwendung zu Azure App Service

Bei [App Service](https://docs.microsoft.com/azure/app-service/app-service-web-overview#why-use-web-apps) handelt es sich um einen vollständig verwalteten Computeplattformdienst, der für das Hosten skalierbarer Websites und Webanwendungen optimiert ist. In diesem Dokument erfahren Sie, wie Sie eine vorhandene Anwendung per Lift & Shift zu Azure App Service migrieren, welche Änderungen ggf. erforderlich sind und welche zusätzlichen Ressourcen für den Umzug in die Cloud benötigt werden.

Wollen Sie loslegen? [Veröffentlichen Sie Ihre ASP.NET- und SQL-Anwendung in Azure App Service.](https://go.microsoft.com/fwlink/?linkid=863214)

# <a name="preparation"></a>Vorbereitung   
* [Bestimmen, ob Ihre App für App Service geeignet ist](https://azure.microsoft.com/downloads/migration-assistant/)
* [Verschieben Ihrer Datenbank in die Cloud](https://go.microsoft.com/fwlink/?linkid=863217)

# <a name="considerations"></a>Überlegungen
Vor der Migration Ihrer Anwendung sind verschiedene Faktoren zu berücksichtigen. Im Anschluss finden Sie eine Liste mit Änderungen, die Sie unter Umständen für Ihre Anwendung vornehmen müssen, sowie Informationen zur jeweiligen Vorgehensweise.

## <a name="sql-database-configuration"></a>SQL-Datenbankkonfiguration
Falls Ihre Anwendung eine lokale Datenbank verwendet, stehen Ihnen mehrere Optionen für Ihre Web-App zur Verfügung. Weitere Informationen zum Migrieren von SQL-Datenbanken zu Azure finden Sie [hier](https://go.microsoft.com/fwlink/?linkid=863217).

## <a name="iis"></a>IIS
Alles, was in Ihrer Anwendung üblicherweise über „applicationHost.config“ konfiguriert wurde, kann jetzt über das Azure-Portal konfiguriert werden. Das gilt beispielsweise für die AppPool-Bitanzahl, für das Aktivieren/Deaktivieren von Websockets, für die verwaltete Pipelineversion und für die .NET Framework-Version (2.0/4.0). Öffnen Sie zum Ändern Ihrer [Anwendungseinstellungen](https://docs.microsoft.com/en-us/azure/app-service/web-sites-configure) im [Azure-Portal](https://portal.azure.com) das Blatt für Ihre Web-App, und klicken Sie auf die Registerkarte **Anwendungseinstellungen**.

## <a name="authentication"></a>Authentifizierung
Wenn Ihre Anwendung eine Benutzerauthentifizierung durchführt, müssen Sie diese Funktion anpassen, damit sie auch nach der Bereitstellung der Anwendung in Azure-Web-Apps funktioniert. Hierzu können Sie beispielsweise mithilfe von Azure AD Connect Ihre lokalen Verzeichnisse in Azure Active Directory integrieren. Weitere Informationen zum Integrieren Ihrer lokalen Verzeichnisse in Azure Active Directory finden Sie [hier](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).

## <a name="virtual-network-modification"></a>Anpassung des virtuellen Netzwerks
Bei Verwendung mehrerer Azure-Dienste kann für die sichere Kommunikation zwischen den Diensten ein virtuelles Netzwerk verwendet werden. Zwischen Ihrem lokalen Netzwerk und einem [virtuellen Azure-Netzwerk](https://docs.microsoft.com/en-us/azure/app-service/web-sites-integrate-with-vnet) können Sie eine VPN- oder eine ExpressRoute-Verbindung herstellen.

## <a name="monitoring-and-diagnostics"></a>Überwachung und Diagnose
Ihre aktuellen lokalen Überwachungs- und Diagnoselösungen funktionieren in der Cloud wahrscheinlich nicht. Azure bietet jedoch Tools für die Protokollierung, Überwachung und Diagnose, um Probleme mit Web-Apps identifizieren und debuggen zu können. Die Diagnose für Ihre Web-App kann ganz einfach in der App-Konfiguration aktiviert werden, und die erfassten Protokolle können in Azure Application Insights angezeigt werden. Weitere Informationen zum Aktivieren der Diagnoseprotokollierung für Web-Apps finden Sie [hier](https://docs.microsoft.com/azure/app-service/web-sites-enable-diagnostic-log).

## <a name="connection-strings-and-application-settings"></a>Verbindungszeichenfolgen und Anwendungseinstellungen
Eine Möglichkeit zum Schutz von Informationen ist die Verwendung von [Azure Key Vault](https://docs.microsoft.com/azure/key-vault/). Hierbei handelt es sich um einen Dienst zum sicheren Speichern vertraulicher Informationen Ihrer Anwendung. Alternativ können Sie die Daten als App Service-Einstellung speichern.

## <a name="dns"></a>DNS
Abhängig von den Anforderungen Ihrer Anwendung ist unter Umständen eine Aktualisierung von DNS-Konfigurationen erforderlich. Diese DNS-Einstellungen können in den [App Service-Einstellungen für die benutzerdefinierte Domäne](https://docs.microsoft.com/azure/app-service/app-service-web-tutorial-custom-domain) konfiguriert werden. Darüber hinaus muss das [Binden eines vorhandenen benutzerdefinierten SSL-Zertifikats an Azure-Web-Apps](https://docs.microsoft.com/en-us/azure/app-service/app-service-web-tutorial-custom-ssl) berücksichtigt werden.

## <a name="file-system-and-storage"></a>Dateisystem und Speicher
Wenn Ihre Anwendung Daten speichert, müssen Sie sie aktualisieren, sodass sie Azure Storage verwendet. Der Azure Storage-Dienst stellt Dateifreigaben für die Freigabe per SMB-Protokoll, Blobspeicher, einfachen Warteschlangen und nicht relationalen Tabellen bereit. Weitere Informationen zu Azure Storage-Dateifreigaben finden Sie [hier](https://docs.microsoft.com/azure/storage/files/storage-files-introduction).

## <a name="next-steps"></a>Nächste Schritte

> [!div class="nextstepaction"]
> [Migrieren einer ASP.NET-Webanwendung zu Azure App Service](https://aka.ms/azure-webapp-migrate)
