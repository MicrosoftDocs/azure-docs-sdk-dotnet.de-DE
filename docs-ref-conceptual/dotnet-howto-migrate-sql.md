---
title: Migrieren einer SQL Server-Datenbank zu Azure
description: Hier erfahren Sie, wie Sie eine SQL Server-Datenbank aus einer lokalen SQL Server-Instanz zu Azure migrieren.
keywords: Azure .NET, ASP.NET, SQL, SQL Server, SQL-Datenbank, migrieren, Migration
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: sql-database
ms.custom: devcenter
ms.openlocfilehash: d118d39e2168686c851f0daa6cb611f0a0c9d2fc
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2018
---
## <a name="migrate-a-sql-server-database-to-azure"></a>Migrieren einer SQL Server-Datenbank zu Azure

In diesem Artikel werden kurz zwei Optionen zum Migrieren einer SQL Server-Datenbank zu Azure erläutert.

Für die Migration einer SQL Server-Produktionsdatenbank stehen in Azure grundsätzlich zwei Optionen zur Verfügung:

1. [SQL Server auf virtuellen Azure-Computern:](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-iaas-overview) Eine SQL Server-Instanz, die auf einem virtuellen Windows-Computer in Azure installiert und gehostet wird. Wird auch als Infrastructure-as-a-Service (IaaS) bezeichnet.
2. [Azure SQL-Datenbank:](https://docs.microsoft.com/azure/sql-database/sql-database-technical-overview) Ein vollständig verwalteter Azure SQL-Datenbankdienst. Wird auch als Platform-as-a-Service (PaaS) bezeichnet.

Beide haben ihre Vor- und Nachteile, die Sie vor der Migration bewerten müssen.

## <a name="get-started"></a>Erste Schritte

Je nach verwendetem Dienst sind die folgenden Migrationshandbücher nützlich:

* [Migrieren einer SQL Server-Datenbank zu SQL Server auf einem virtuellen Azure-Computer](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-migrate-sql)
* [Migrieren einer SQL Server-Datenbank zu Azure SQL-Datenbank](https://docs.microsoft.com/azure/sql-database/sql-database-migrate-your-sql-server-database)

Unter den folgenden Links zu konzeptionellen Inhalten finden Sie darüber hinaus Informationen zum besseren Verständnis virtueller Computer:

* [Hochverfügbarkeit und Notfallwiederherstellung für SQL Server auf virtuellen Azure-Computern](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr)
* [Optimale Verfahren für die Leistung für SQL Server auf virtuellen Computern in Azure](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-performance)
* [Anwendungsmuster und Entwicklungsstrategien für SQL Server in Azure Virtual Machines](https://docs.microsoft.com/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-server-app-patterns-dev-strategies)

Unter den folgenden Links finden Sie Informationen zum besseren Verständnis von Azure SQL-Datenbank:

* [Erstellen und Verwalten von Azure SQL-Datenbankservern und -datenbanken](https://docs.microsoft.com/azure/sql-database/sql-database-servers-databases)
* [Datenbanktransaktionseinheiten (DTUs) und elastische Datenbanktransaktionseinheiten (eDTUs)](https://docs.microsoft.com/azure/sql-database/sql-database-what-is-a-dtu)
* [Ressourceneinschränkungen für Azure SQL-Datenbanken](https://docs.microsoft.com/azure/sql-database/sql-database-resource-limits)

## <a name="choosing-iaas-or-paas"></a>IaaS oder PaaS?

Überlegen Sie beim Auswerten des Migrationsziels für Ihre Datenbank, ob IaaS oder PaaS besser geeignet ist.

**Entscheiden Sie sich für SQL Server auf virtuellen Azure-Computern, wenn Folgendes zutrifft:**

* Sie möchten Ihre Datenbank und Anwendungen per Lift & Shift migrieren und dabei möglichst wenig oder gar nichts ändern.
* Sie möchten uneingeschränkte Kontrolle über Ihren Datenbankserver und den virtuellen Computer, auf dem er ausgeführt wird.
* Sie verfügen bereits über SQL Server- und Windows Server-Lizenzen, die Sie verwenden möchten.

**Entscheiden Sie sich für Azure SQL-Datenbank, wenn Folgendes zutrifft:**

* Sie möchten Ihre Anwendungen modernisieren und eine Migration durchführen, um andere PaaS-Dienste in Azure verwenden zu können.
* Sie möchten sich nicht um die Verwaltung Ihres Datenbankservers und des virtuellen Computers kümmern, auf dem er ausgeführt wird.
* Sie verfügen über keine SQL Server- oder Windows Server-Lizenzen oder möchten ggf. vorhandene Lizenzen ablaufen lassen.

In der folgenden Tabelle werden die Unterschiede zwischen den einzelnen Diensten anhand von verschiedenen Szenarien erläutert:

| Szenario | SQL Server auf virtuellen Azure-Computern | Azure SQL-Datenbank |
|----------|-------------------------|--------------------|
| Migration | Erfordert nur minimale Änderungen an der Datenbank. | Erfordert unter Umständen Änderungen an der Datenbank, wenn Sie Features verwenden, die in Azure SQL nicht verfügbar sind (kann mit dem [Datenmigrations-Assistenten](https://www.microsoft.com/download/details.aspx?id=53595) ermittelt werden), oder wenn andere Abhängigkeiten wie etwa lokal installierte ausführbaren Dateien vorhanden sind.|
| Verwaltung von Verfügbarkeit, Wiederherstellung und Upgrades | Verfügbarkeit und Wiederherstellung werden manuell konfiguriert. Upgrades können mit [VM Scale Sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade) automatisiert werden. | Automatisch verwaltet |
| Konfiguration des zugrunde liegenden Betriebssystems | Manuelle Konfiguration | Automatisch verwaltet |
| Verwaltung der Datenbankgröße | Unterstützt bis zu 64 TB Speicher pro SQL Server-Instanz. | Unterstützt 4 TB Speicher. Danach wird eine horizontale Partition benötigt. |
| Kostenverwaltung | Sie müssen SQL Server-Lizenzierungskosten, Windows Server-Lizenzierungskosten und Kosten für virtuelle Computer (auf der Grundlage von Kernen, Arbeitsspeicher und Speicher) verwalten. | Sie müssen die Dienstkosten auf der Grundlage von [eDTUs oder DTUs](https://docs.microsoft.com/azure/sql-database/sql-database-what-is-a-dtu), Speicher und Anzahl von Datenbanken (bei Verwendung eines Pools für elastische Datenbanken) verwalten.  Außerdem müssen Sie die Kosten für ggf. vorhandene SLAs verwalten. |

Weitere Informationen zu den Unterschieden zwischen den beiden Optionen finden Sie unter [Wählen Sie eine SQL Server-Cloudoption: Azure SQL-Datenbank (PaaS) oder SQL Server auf Azure-VMs (IaaS)](https://docs.microsoft.com/azure/sql-database/sql-database-paas-vs-sql-server-iaas).

## <a name="faq"></a>Häufig gestellte Fragen

* **Kann ich mit SQL Server auf virtuellen Azure-Computern oder in Azure SQL-Datenbank weiterhin Tools wie SQL Server Management Studio und SQL Server Reporting Services (SSRS) verwenden?**

    Ja. Alle SQL-Tools von Microsoft können mit beiden Diensten verwendet werden. SSRS ist allerdings nicht Teil von Azure SQL-Datenbank. Wir empfehlen, es auf einem virtuellen Azure-Computer auszuführen und auf Ihre Datenbankinstanz zu verweisen.
    
* **Ich möchte auf PaaS umsteigen, bin mir aber nicht sicher, ob meine Datenbank kompatibel ist. Gibt es Tools, die mir hier weiterhelfen?**

    Ja. Der [Datenmigrations-Assistent](https://www.microsoft.com/download/details.aspx?id=53595) wird im Rahmen der Migration zu Azure SQL-Datenbank verwendet.  Der [Azure Database Migration Service](https://azure.microsoft.com/campaigns/database-migration/) ist ein Vorschaudienst, den Sie für IaaS oder PaaS verwenden können.

* **Kann ich eine Kostenschätzung erstellen?**

    Ja.  Mit dem [Azure-Preisrechner](https://azure.microsoft.com/pricing/calculator/) können Sie die voraussichtlichen Kosten für alle Azure-Dienste berechnen – auch für virtuelle Computer und Datenbankdienste.
    
## <a name="next-steps"></a>Nächste Schritte

> [!div class="nextstepaction"]
> [Auswählen der passenden Azure-Hostingoption](dotnet-howto-choose-migration.md)
