---
title: Erste Schritte mit Azure und .NET
description: Lernen Sie die erforderlichen Grundlagen von Azure und .NET kennen.
ms.date: 09/19/2018
ms.openlocfilehash: 63587d7d5ccb79eee47185ff1f3ccb9cbd09c0ea
ms.sourcegitcommit: 0de939648fa01698016fed633200f8eb07c96eb7
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/08/2018
ms.locfileid: "51276580"
---
# <a name="get-started-with-azure-and-net"></a>Erste Schritte mit Azure und .NET

Dieses Dokument bietet eine Übersicht über wichtige Konzepte und Dienste, mit denen .NET Entwickler für den Einstieg in die Entwicklung von Apps mit Azure-Diensten vertraut sein müssen.

## <a name="key-concepts"></a>Wichtige Begriffe

**Azure-Konto**: Mit Ihrem Azure-Konto melden Sie sich bei Azure-Diensten wie dem [Azure-Portal](https://portal.azure.com) oder [Cloud Shell](https://shell.azure.com) an. Falls Sie kein Azure-Konto besitzen, können Sie [kostenlos eines erstellen](https://azure.microsoft.com/free/dotnet/).

**Azure-Abonnement**: Ein Abonnement ist der Abrechnungsplan, in dem Azure-Ressourcen erstellt werden. Bei Abonnements kann es sich um einzelne Abonnements oder um Enterprise-Abonnements handeln, die von Ihrem Unternehmen verwaltet werden. Ihr Azure-Konto kann mehreren Abonnements zugeordnet sein. Achten Sie in diesem Fall beim Erstellen von Ressourcen auf die Auswahl des richtigen Abonnements. Weitere Informationen finden Sie unter [Grundlegendes zu Konten, Abonnements und Abrechnung](https://docs.microsoft.com/azure/guides/developer/azure-developer-guide#understanding-accounts-subscriptions-and-billing).

> [!TIP]
> Wenn Sie ein Visual Studio-Abonnement haben, [verfügen Sie über monatliche Azure-Gutschriften, die zur Aktivierung bereit sind](https://azure.microsoft.com/pricing/member-offers/credit-for-visual-studio-subscribers/).

**Ressourcengruppe**: Ressourcengruppen sind eine Möglichkeit zum Organisieren Ihrer Azure-Ressourcen in Gruppen für die Verwaltung. In Azure erstellte Ressourcen werden in einer Ressourcengruppe gespeichert, ähnlich wie beim Speichern einer Datei in einem Ordner auf einem Computer.

**Hosting**: Zum Ausführen von Code in Azure muss dieser in einem Dienst gehostet sein, der vom Benutzer bereitgestellten Code unterstützt.

**Verwaltete Dienste**: Azure bietet einige Dienste, mit denen Sie Daten oder Informationen in Azure bereitstellen und die Azure Implementierung die entsprechende Aktion ausführt. Ein Beispiel dafür ist der Azure Blob Storage-Dienst, in dem Sie Dateien bereitstellen, die von Azure gelesen, geschrieben und gespeichert werden.

## <a name="choosing-a-hosting-option"></a>Auswählen einer Hostingoption

Hosting in Azure lässt sich in drei Kategorien unterteilen.

* **Infrastructure-as-a-Service (IaaS)**: Bei IaaS stellen Sie die benötigten virtuellen Computer zusammen mit den zugeordneten Netzwerk- und Speicherkomponenten bereit. Anschließend stellen Sie die Software und Anwendungen bereit, die für diese virtuellen Computer jeweils vorgesehen sind. Dieses Modell weist die größte Ähnlichkeit mit einer herkömmlichen lokalen Umgebung auf – mit der Ausnahme, dass die Infrastruktur von Microsoft verwaltet wird. Sie verwalten weiterhin die einzelnen virtuellen Computer, einschließlich Betriebssystem, benutzerdefinierte Software und Sicherheitsupdates.

* **Platform-as-a-Service (PaaS)**: Bei PaaS ist eine verwaltete Hostingumgebung vorhanden, in der Sie Ihre Anwendung bereitstellen, ohne virtuelle Computer oder Netzwerkressourcen verwalten zu müssen. Anstatt beispielsweise einzelne VMs zu erstellen, geben Sie eine Instanzanzahl an, und der Dienst übernimmt das Bereitstellen, Konfigurieren und Verwalten der erforderlichen Ressourcen. Azure App Service ist ein Beispiel für einen PaaS-Dienst.
  
* **Functions-as-a-Service (FaaS)**: FaaS wird gemeinhin als „serverloses Computing“ bezeichnet und geht beim Abstrahieren der Aspekte der Hostingumgebung sogar noch weiter als PaaS. Anstatt Computeinstanzen zu erstellen und dann Code auf diesen Instanzen bereitzustellen, stellen Sie Ihren Code bereit, der vom Dienst dann automatisch ausgeführt wird. Sie müssen die Computeressourcen nicht verwalten. Die Plattform skaliert Ihren Code nahtlos auf die jeweilige Ebene herauf oder herunter, die zum Verarbeiten des Datenverkehrs erforderlich ist, und Sie bezahlen nur, wenn Ihr Code ausgeführt wird. Azure Functions ist ein FaaS-Dienst.

Allgemein gilt: Je mehr Ihre Anwendung FaaS- und PaaS-Modelle begünstigt, desto mehr Vorteile der Ausführung in der Cloud bemerken Sie. Nachstehend finden Sie eine Zusammenfassung dreier gängiger Hostingoptionen in Azure und erfahren, wann Sie diese auswählen sollten.

* [Azure App Service](https://docs.microsoft.com/azure/app-service/app-service-value-prop-what-is): Wenn Sie eine Webanwendung oder einen Dienst hosten möchten, sehen Sie sich zuerst App Service an. Informationen zum Einstieg in App Service und ASP.NET, WCF und ASP.NET Core-Apps finden Sie unter [Erstellen von ASP.NET Core-Web-Apps in Azure](https://docs.microsoft.com/azure/app-service/app-service-web-get-started-dotnet).

* [Azure Functions](https://docs.microsoft.com/azure/azure-functions/functions-overview): Azure Functions eignet sich hervorragend für ereignisgesteuerte Workflows. Beispiele hierfür sind das Antworten auf Webhooks, die Verarbeitung von Elementen in Warteschlangen oder im Blobspeicher sowie Zeitgeber. Informationen zum Einstieg in Azure Functions finden Sie unter [Erstellen Ihrer ersten Funktion mit Visual Studio](https://docs.microsoft.com/azure/azure-functions/functions-create-your-first-function-visual-studio).

* [Azure Virtual Machines](https://docs.microsoft.com/azure/virtual-machines/): Wenn App Service Ihren Anforderungen für das Hosten einer vorhandenen Anwendung aufgrund von bestimmten Abhängigkeiten nicht entspricht, ist Virtual Machines für den Anfang am besten geeignet. Informationen zu den ersten Schritten mit Virtual Machines und ASP.NET oder WCF finden Sie unter [Deploy an ASP.NET app to an Azure virtual machine](https://tutorials.visualstudio.com/aspnet-vm/intro) (Bereitstellen einer ASP.NET-App auf einem virtuellen Azure-Computer).

> [!TIP]
> Eine vollständige Liste der Azure-Dienste finden Sie unter [Übersicht über Azure-Computeoptionen](https://docs.microsoft.com/azure/architecture/guide/technology-choices/compute-overview#azure-compute-options). Weitere Informationen zur Auswahl eines Diensts finden Sie unter [Entscheidungsstruktur für Azure-Computedienste](https://docs.microsoft.com/azure/architecture/guide/technology-choices/compute-decision-tree).

## <a name="choosing-a-data-storage-service"></a>Auswählen eines Datenspeicherdiensts

Azure bietet je nach Ihren Anforderungen verschiedene Dienste zum Speichern von Daten. Die am häufigsten verwendeten Datendienste für .NET-Entwickler sind:

* [Azure SQL-Datenbank](https://docs.microsoft.com/azure/sql-database/): Wenn Sie eine Anwendung in die Cloud migrieren möchten, die bereits SQL Server verwendet wird, bietet sich natürlich Azure SQL-Datenbank als Ausgangspunkt an. Informationen zum Einstieg finden Sie unter [Tutorial: Erstellen einer ASP.NET-App in Azure mit SQL-Datenbank](https://docs.microsoft.com/azure/app-service/app-service-web-tutorial-dotnet-sqldatabase).

* [Azure Cosmos DB](https://docs.microsoft.com/azure/cosmos-db/): Azure Cosmos DB ist eine moderne Datenbank, die für die Cloud entwickelt wurde. Wenn Sie eine neue Anwendung starten, die noch keine bestimmte Datenbankabhängigkeit aufweist, sollten Sie sich Azure Cosmos DB ansehen. Cosmos DB ist eine gute Wahl für neue Web-, Mobil-, Gaming- und IoT-Anwendungen, bei denen Dinge wie automatische Skalierung, vorhersagbare Leistung, kurze Reaktionszeiten und die Möglichkeit zum Abfragen von schemafreien Daten wichtig sind. Informationen zum Einstieg finden Sie unter [Schnellstart: Erstellen einer .NET-Web-App mit Azure Cosmos DB unter Verwendung der SQL-API und des Azure-Portals](https://docs.microsoft.com/azure/cosmos-db/create-sql-api-dotnet).

* [Azure Blob Storage](https://docs.microsoft.com/azure/storage/): Azure Blob Storage ist für das Speichern und Abrufen großer binärer Objekte wie Bilder, Dateien und Streams optimiert. Objektspeicher ermöglichen die Verwaltung extrem großer Mengen unstrukturierter Daten. Informationen zum Einstieg finden Sie unter [Schnellstart: Hochladen, Herunterladen und Auflisten von Blobs mit .NET](https://docs.microsoft.com/azure/storage/blobs/storage-quickstart-blobs-dotnet).

> [!TIP]
> Informationen finden Sie unter [Auswählen des richtigen Datenspeichers](https://docs.microsoft.com/azure/architecture/guide/technology-choices/data-store-overview).

## <a name="connecting-to-azure-services"></a>Herstellen einer Verbindung mit Azure-Diensten

Wenn Sie Visual Studio verwenden, können Sie Ihren Projekten Unterstützung für bestimmte Azure-Dienste hinzufügen.  Über das Dialogfeld **Verbundene Dienste** in Visual Studio können Ihren Projekten ganz einfach alle erforderlichen Verweise, Verbindungscode und Konfigurationseinstellungen hinzugefügt werden.  Einige häufig verwendete Azure-Dienste werden standardmäßig unterstützt, etwa [Storage](/azure/vs-azure-tools-connected-services-storage), [Azure Active Directory](/azure/active-directory/develop/vs-active-directory-add-connected-service)-Authentifizierung, [Azure Key Vault](/azure/key-vault/vs-key-vault-add-connected-service) und [Cognitive Services](/azure/cognitive-services/) (beispielsweise [Maschinelles Sehen](/azure/cognitive-services/computer-vision/vs-computer-vision-connected-service)).  Weitere Dienste, einschließlich Dienste von Drittanbietern, sind als Erweiterungen im [Visual Studio Marketplace](https://marketplace.visualstudio.com/search?term=connected%20service&target=VS&category=Tools&vsVersion=&subCategory=All&sortBy=Relevance) verfügbar.

## <a name="diagnosing-problems-in-the-cloud"></a>Diagnostizieren von Problemen in der Cloud
Beim Bereitstellen Ihrer Anwendung in Azure kann es vorkommen, dass Dinge nicht mehr funktionieren, die in der Entwicklung keine Probleme bereitet haben. Nachstehend finden Sie zwei gute Einstiegspunkte in das Diagnostizieren von Probleme:

* **Remotedebuggen über Visual Studio**: Die meisten Azure-Computedienste (einschließlich der in diesem Dokument behandelten Dienste) unterstützen Remotedebuggen mit Visual Studio and das Abrufen von Protokollen. Zum Erkunden der Funktionen von Visual Studio mit Ihrer Anwendung öffnen Sie das Toolfenster „Cloud-Explorer“, indem Sie „Cloud-Explorer“ in die Schnellstart-Symbolleiste (rechts oben) von Visual Studio eingeben und dann in der Struktur Ihre Anwendung auswählen. Ausführliche Informationen finden Sie unter [Problembehandlung von Web-Apps in Azure App Service in Visual Studio](https://docs.microsoft.com/azure/app-service/web-sites-dotnet-troubleshoot-visual-studio#remotedebug).

* **Application Insights**: [Application Insights](https://docs.microsoft.com/azure/application-insights/) ist eine umfassende Lösung zur Leistungsüberwachung einer Anwendung (Application Performance Monitoring, APM), die Diagnose-, Telemetrie- und Leistungsdaten von Anwendungen automatisch erfasst. Informationen zum Einstieg das Sammeln von Diagnosedaten für Ihre App finden Sie unter [Starten der Überwachung Ihrer ASP.NET-Webanwendung](https://docs.microsoft.com/azure/application-insights/quick-monitor-portal).

## <a name="next-steps"></a>Nächste Schritte

* [Bereitstellen Ihrer ersten ASP.NET Core-Web-App in Azure](https://docs.microsoft.com/azure/app-service/app-service-web-get-started-dotnet)
* [Informationen zur Authentifizierung bei den Azure-APIs für .NET](dotnet-sdk-azure-authenticate.md)
* [Diagnostizieren von Fehlern in Ihren Cloud-Apps](https://blogs.msdn.microsoft.com/webdev/2018/02/07/diagnosing-errors-on-your-cloud-apps)
* Kostenloses E-Book [Azure-Schnellstarthandbuch für .NET-Entwickler](https://www.microsoft.com/net/download/thank-you/azure-quick-start-ebook) herunterladen
