---
title: Versionshinweise zu Azure-Verwaltungsbibliotheken für .NET | Microsoft-Dokumentation
description: Informieren Sie sich über Neuerungen und wichtige Änderungen in den Azure-Verwaltungsbibliotheken für .NET.
keywords: Azure, .NET, API, Referenz, Hinweise, Updates, veraltet
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: 48ff29507268f6b38acb24217801cf7b0227e444
ms.sourcegitcommit: e1a0e91988bb849c75e9583a80e3e6d712083785
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/14/2018
ms.locfileid: "31005907"
---
# <a name="release-notes"></a><span data-ttu-id="181a2-104">Versionsinformationen</span><span class="sxs-lookup"><span data-stu-id="181a2-104">Release Notes</span></span> 

## <a name="feature-availability-and-road-map-as-of-version-100"></a><span data-ttu-id="181a2-105">Verfügbarkeit von Funktionen und Fahrplan ab Version 1.0.0</span><span class="sxs-lookup"><span data-stu-id="181a2-105">Feature Availability and Road Map as of Version 1.0.0</span></span> ##
### <a name="april-26-2017"></a><span data-ttu-id="181a2-106">26. April 2017</span><span class="sxs-lookup"><span data-stu-id="181a2-106">April 26, 2017</span></span>

<table>
  <tr>
    <th align="left"><span data-ttu-id="181a2-107">Dienst | Funktion</span><span class="sxs-lookup"><span data-stu-id="181a2-107">Service | feature</span></span></th>
    <th align="left"><span data-ttu-id="181a2-108">Allgemein verfügbar</span><span class="sxs-lookup"><span data-stu-id="181a2-108">Available as GA</span></span></th>
    <th align="left"><span data-ttu-id="181a2-109">Als Vorschauversion verfügbar</span><span class="sxs-lookup"><span data-stu-id="181a2-109">Available as Preview</span></span></th>
    <th align="left"><span data-ttu-id="181a2-110">In Kürze verfügbar</span><span class="sxs-lookup"><span data-stu-id="181a2-110">Coming soon</span></span></th>
  </tr>
  <tr>
    <td><span data-ttu-id="181a2-111">Compute</span><span class="sxs-lookup"><span data-stu-id="181a2-111">Compute</span></span></td>
    <td><span data-ttu-id="181a2-112">VMs und VM-Erweiterungen</span><span class="sxs-lookup"><span data-stu-id="181a2-112">Virtual machines and VM extensions</span></span><br><span data-ttu-id="181a2-113">VM-Skalierungsgruppen</span><span class="sxs-lookup"><span data-stu-id="181a2-113">Virtual machine scale sets</span></span><br><span data-ttu-id="181a2-114">Verwaltete Datenträger</span><span class="sxs-lookup"><span data-stu-id="181a2-114">Managed disks</span></span></td>
    <td></td>
    <td valign="top"><span data-ttu-id="181a2-115">Azure Container Service</span><span class="sxs-lookup"><span data-stu-id="181a2-115">Azure container services</span></span><br><span data-ttu-id="181a2-116">Azure-Containerregistrierung</span><span class="sxs-lookup"><span data-stu-id="181a2-116">Azure container registry</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="181a2-117">Speicher</span><span class="sxs-lookup"><span data-stu-id="181a2-117">Storage</span></span></td>
    <td><span data-ttu-id="181a2-118">Speicherkonten</span><span class="sxs-lookup"><span data-stu-id="181a2-118">Storage accounts</span></span></td>
    <td></td>
    <td><span data-ttu-id="181a2-119">Verschlüsselung</span><span class="sxs-lookup"><span data-stu-id="181a2-119">Encryption</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="181a2-120">SQL-Datenbank</span><span class="sxs-lookup"><span data-stu-id="181a2-120">SQL Database</span></span></td>
    <td><span data-ttu-id="181a2-121">Datenbanken</span><span class="sxs-lookup"><span data-stu-id="181a2-121">Databases</span></span><br><span data-ttu-id="181a2-122">Firewalls</span><span class="sxs-lookup"><span data-stu-id="181a2-122">Firewalls</span></span><br><span data-ttu-id="181a2-123">Pools für elastische Datenbanken</span><span class="sxs-lookup"><span data-stu-id="181a2-123">Elastic pools</span></span></td>
    <td></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="181a2-124">Netzwerk</span><span class="sxs-lookup"><span data-stu-id="181a2-124">Networking</span></span></td>
    <td><span data-ttu-id="181a2-125">Virtuelle Netzwerke</span><span class="sxs-lookup"><span data-stu-id="181a2-125">Virtual networks</span></span><br><span data-ttu-id="181a2-126">Netzwerkschnittstellen</span><span class="sxs-lookup"><span data-stu-id="181a2-126">Network interfaces</span></span><br><span data-ttu-id="181a2-127">IP-Adressen</span><span class="sxs-lookup"><span data-stu-id="181a2-127">IP addresses</span></span><br><span data-ttu-id="181a2-128">Routingtabelle</span><span class="sxs-lookup"><span data-stu-id="181a2-128">Routing table</span></span><br><span data-ttu-id="181a2-129">Netzwerksicherheitsgruppen</span><span class="sxs-lookup"><span data-stu-id="181a2-129">Network security groups</span></span><br><span data-ttu-id="181a2-130">DNS</span><span class="sxs-lookup"><span data-stu-id="181a2-130">DNS</span></span><br><span data-ttu-id="181a2-131">Traffic Manager</span><span class="sxs-lookup"><span data-stu-id="181a2-131">Traffic managers</span></span></td>
    <td valign="top"><span data-ttu-id="181a2-132">Load Balancer</span><span class="sxs-lookup"><span data-stu-id="181a2-132">Load balancers</span></span><br><span data-ttu-id="181a2-133">Anwendungsgateways</span><span class="sxs-lookup"><span data-stu-id="181a2-133">Application gateways</span></span></td>
    <td valign="top"></td>
  </tr>
  <tr>
    <td><span data-ttu-id="181a2-134">Weitere Dienste</span><span class="sxs-lookup"><span data-stu-id="181a2-134">More services</span></span></td>
    <td><span data-ttu-id="181a2-135">Ressourcen-Manager</span><span class="sxs-lookup"><span data-stu-id="181a2-135">Resource Manager</span></span><br><span data-ttu-id="181a2-136">Schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="181a2-136">Key Vault</span></span><br><span data-ttu-id="181a2-137">Redis</span><span class="sxs-lookup"><span data-stu-id="181a2-137">Redis</span></span><br><span data-ttu-id="181a2-138">CDN</span><span class="sxs-lookup"><span data-stu-id="181a2-138">CDN</span></span><br><span data-ttu-id="181a2-139">Batch</span><span class="sxs-lookup"><span data-stu-id="181a2-139">Batch</span></span></td>
    <td valign="top"><span data-ttu-id="181a2-140">App Service (Web-Apps)</span><span class="sxs-lookup"><span data-stu-id="181a2-140">App service - Web apps</span></span><br><span data-ttu-id="181a2-141">Funktionen</span><span class="sxs-lookup"><span data-stu-id="181a2-141">Functions</span></span><br><span data-ttu-id="181a2-142">Service Bus</span><span class="sxs-lookup"><span data-stu-id="181a2-142">Service bus</span></span></td>
    <td valign="top"><span data-ttu-id="181a2-143">Überwachen</span><span class="sxs-lookup"><span data-stu-id="181a2-143">Monitor</span></span><br><span data-ttu-id="181a2-144">Graph (rollenbasierte Zugriffssteuerung)</span><span class="sxs-lookup"><span data-stu-id="181a2-144">Graph RBAC</span></span><br><span data-ttu-id="181a2-145">Azure Cosmos DB</span><span class="sxs-lookup"><span data-stu-id="181a2-145">Azure Cosmos DB</span></span><br><span data-ttu-id="181a2-146">Scheduler</span><span class="sxs-lookup"><span data-stu-id="181a2-146">Scheduler</span></span></td>
  </tr>
  <tr>
    <td><span data-ttu-id="181a2-147">Grundlagen</span><span class="sxs-lookup"><span data-stu-id="181a2-147">Fundamentals</span></span></td>
    <td><span data-ttu-id="181a2-148">Authentifizierung (Core)</span><span class="sxs-lookup"><span data-stu-id="181a2-148">Authentication - core</span></span></td>
    <td><span data-ttu-id="181a2-149">Asynchrone Methoden</span><span class="sxs-lookup"><span data-stu-id="181a2-149">Async methods</span></span></td>
    <td valign="top"></td>
  </tr>
</table>

> [!WARNING] 
> <span data-ttu-id="181a2-150">Funktionen in der *Vorschau* sind in Dokumentationskommentaren in Bibliotheken gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="181a2-150">*Preview* features are flagged in documentation comments in libraries.</span></span> <span data-ttu-id="181a2-151">Bei diesen Funktionen sind Änderungen vorbehalten.</span><span class="sxs-lookup"><span data-stu-id="181a2-151">These features are subject to change.</span></span> <span data-ttu-id="181a2-152">Sie können in Zukunft auf beliebige Weise geändert (oder sogar entfernt) werden.</span><span class="sxs-lookup"><span data-stu-id="181a2-152">They can be modified in any way (or even removed) in the future.</span></span>

[!include[Contribute and community](includes/contribute.md)]
