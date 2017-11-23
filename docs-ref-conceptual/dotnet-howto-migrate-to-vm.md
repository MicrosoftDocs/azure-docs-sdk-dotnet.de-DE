---
title: Migrieren einer ASP.NET-Webanwendung zu einem virtuellen Azure-Computer
description: Hier erfahren Sie, wie Sie eine ASP.NET-Webanwendung aus einer lokalen Umgebung zu einem virtuellen Azure-Computer migrieren.
keywords: Azure .NET, ASP.NET, VM, virtueller Computer, migrieren, Migration
author: camsoper
manager: wpickett
ms.author: casoper
ms.date: 11/15/2017
ms.topic: article
ms.technology: azure
ms.devlang: dotnet
ms.service: virtual-machines
ms.custom: devcenter
ms.openlocfilehash: 718d91b98180a7584f78a2383d430c4700743306
ms.sourcegitcommit: c360a22d5bff6eedd714b28b847d2f26b06665f4
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/15/2017
---
# <a name="migrate-an-aspnet-web-application-to-an-azure-virtual-machine"></a><span data-ttu-id="442b5-104">Migrieren einer ASP.NET-Webanwendung zu einem virtuellen Azure-Computer</span><span class="sxs-lookup"><span data-stu-id="442b5-104">Migrate an ASP.NET Web application to an Azure Virtual Machine</span></span>

<span data-ttu-id="442b5-105">In diesem Übersichtsdokument erfahren Sie, wie Sie eine ASP.NET-Webanwendung aus einer lokalen Umgebung zu einem virtuellen Azure-Computer migrieren.</span><span class="sxs-lookup"><span data-stu-id="442b5-105">This document provides an overview of how to migrate an ASP.NET web application from on-premises to an Azure Virtual Machine.</span></span>

## <a name="get-started"></a><span data-ttu-id="442b5-106">Erste Schritte</span><span class="sxs-lookup"><span data-stu-id="442b5-106">Get Started</span></span>

<span data-ttu-id="442b5-107">Die folgenden Tutorials zeigen Schritt für Schritt, wie Sie einen virtuellen Computer erstellen (oder migrieren), Ihre Webanwendung für den virtuellen Computer veröffentlichen und andere Aufgaben durchführen, die ggf. erforderlich sind, damit Ihre Anwendung in Azure unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="442b5-107">These tutorials demonstrate the steps to create (or migrate) a virtual machine, publish your web application to it, and other tasks that may be required to support your application in Azure.</span></span>

- <span data-ttu-id="442b5-108">Erstellen Sie mithilfe einer der folgenden Optionen einen virtuellen Computer für Ihre ASP.NET-Anwendung in Azure:</span><span class="sxs-lookup"><span data-stu-id="442b5-108">Create a virtual machine for your ASP.NET application in Azure using one of the following two options:</span></span>
    - [<span data-ttu-id="442b5-109">Erstellen eines neuen virtuellen Computers für ASP.NET-Anwendungen</span><span class="sxs-lookup"><span data-stu-id="442b5-109">Create a new virtual machine for ASP.NET Applications</span></span>](https://go.microsoft.com/fwlink/?linkid=863237)
    - [<span data-ttu-id="442b5-110">Migrieren eines lokalen virtuellen Computers</span><span class="sxs-lookup"><span data-stu-id="442b5-110">Migrate an existing on-premises virtual machine</span></span>](https://docs.microsoft.com/azure/site-recovery/tutorial-migrate-on-premises-to-azure)
- [<span data-ttu-id="442b5-111">Veröffentlichen Ihrer App mithilfe von Visual Studio</span><span class="sxs-lookup"><span data-stu-id="442b5-111">Publish your app using Visual Studio</span></span>](https://go.microsoft.com/fwlink/?linkid=863240)
- [<span data-ttu-id="442b5-112">Erstellen eines sicheren virtuellen Netzwerks für Ihre virtuellen Computer</span><span class="sxs-lookup"><span data-stu-id="442b5-112">Create a secure virtual network for your VMs</span></span>](https://docs.microsoft.com/azure/virtual-network/virtual-network-get-started-vnet-subnet)
- [<span data-ttu-id="442b5-113">Erstellen einer CI/CD-Pipeline für Ihre Anwendung</span><span class="sxs-lookup"><span data-stu-id="442b5-113">Create a CI/CD pipeline for your application</span></span>](https://docs.microsoft.com/vsts/build-release/apps/cd/deploy-webdeploy-iis-deploygroups)
- [<span data-ttu-id="442b5-114">Verwenden einer VM-Skalierungsgruppe für hohe Verfügbarkeit und Skalierbarkeit</span><span class="sxs-lookup"><span data-stu-id="442b5-114">Move to a VM scale set for high availability and scalability</span></span>](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app)

## <a name="considerations"></a><span data-ttu-id="442b5-115">Überlegungen</span><span class="sxs-lookup"><span data-stu-id="442b5-115">Considerations</span></span>

### <a name="benefits"></a><span data-ttu-id="442b5-116">Vorteile</span><span class="sxs-lookup"><span data-stu-id="442b5-116">Benefits</span></span>

<span data-ttu-id="442b5-117">Mit virtuellen Computern lässt sich eine Anwendung am einfachsten aus der lokalen Umgebung zur Cloud migrieren.</span><span class="sxs-lookup"><span data-stu-id="442b5-117">Virtual machines offer the easiest path to migrate an application from on-premises to the cloud.</span></span>  <span data-ttu-id="442b5-118">Sie ermöglichen die Replizierung der gleichen Umgebung, die Ihre Anwendung auch lokal verwendet, haben aber den Vorteil, dass Sie keine eigenen Rechenzentren mehr verwalten müssen.</span><span class="sxs-lookup"><span data-stu-id="442b5-118">They enable you to replicate the same environment your application uses on-premises, while removing the need to maintain your own data centers.</span></span>  <span data-ttu-id="442b5-119">VM-Skalierungsgruppen bieten hohe Verfügbarkeit und Skalierbarkeit für Anwendungen, die in Virtual Machines ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="442b5-119">Virtual Machine Scale Sets provide high availability and scalability for applications running in Virtual Machines.</span></span>

### <a name="virtual-machine-size"></a><span data-ttu-id="442b5-120">VM-Größe</span><span class="sxs-lookup"><span data-stu-id="442b5-120">Virtual Machine Size</span></span>

<span data-ttu-id="442b5-121">Wählen Sie eine VM-Größe und einen VM-Typ, die am besten für Ihre Workload geeignet sind.</span><span class="sxs-lookup"><span data-stu-id="442b5-121">Choose the virtual machine size and type that is best optimized for your workload.</span></span>  <span data-ttu-id="442b5-122">Weitere Informationen finden Sie unter [Größen für virtuelle Windows-Computer in Azure](https://docs.microsoft.com/azure/virtual-machines/windows/sizes).</span><span class="sxs-lookup"><span data-stu-id="442b5-122">See [sizes for Windows virtual machines in Azure](https://docs.microsoft.com/azure/virtual-machines/windows/sizes) for more information.</span></span>

### <a name="maintenance"></a><span data-ttu-id="442b5-123">Wartung</span><span class="sxs-lookup"><span data-stu-id="442b5-123">Maintenance</span></span>

<span data-ttu-id="442b5-124">Virtuelle Computer müssen genau wie lokale Computer gewartet und aktualisiert werden<sup>&#42;</sup>.</span><span class="sxs-lookup"><span data-stu-id="442b5-124">Just like an on-premises machine, you are responsible for maintaining and updating the virtual machine<sup>&#42;</sup>.</span></span>  <span data-ttu-id="442b5-125">Bei Anwendungen, die in einer PaaS-Umgebung (Plattform-as-a-Service) wie etwa [Azure App Service](https://docs.microsoft.com/azure/app-service/) oder in einem [Container](https://docs.microsoft.com/azure/app-service/containers/) ausgeführt werden können, entfällt diese Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="442b5-125">If your application can run in a Platform as a Service (PaaS) environment such as [Azure App Service](https://docs.microsoft.com/azure/app-service/) or in a [container](https://docs.microsoft.com/azure/app-service/containers/), that will remove this need.</span></span>

<span data-ttu-id="442b5-126">*<sup>&#42; </sup>[Automatische Betriebssystemupgrades für Azure-VM-Skalierungsgruppen](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade) stehen derzeit als Vorschauversion zur Verfügung.*</span><span class="sxs-lookup"><span data-stu-id="442b5-126">*<sup>&#42;</sup>[Automatic OS upgrades for virtual machine scale sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-automatic-upgrade) is currently available as a Preview service.*</span></span>

### <a name="virtual-networks"></a><span data-ttu-id="442b5-127">Virtuelle Netzwerke</span><span class="sxs-lookup"><span data-stu-id="442b5-127">Virtual Networks</span></span>

<span data-ttu-id="442b5-128">Virtuelle Azure-Netzwerke ermöglichen Folgendes:</span><span class="sxs-lookup"><span data-stu-id="442b5-128">Azure Virtual Networks enable you to:</span></span>
- <span data-ttu-id="442b5-129">Erstellen einer von Ihnen kontrollierten Hybridinfrastruktur</span><span class="sxs-lookup"><span data-stu-id="442b5-129">Build a hybrid infrastructure that you control</span></span>
- <span data-ttu-id="442b5-130">Verwenden eigener IP-Adressen und DNS-Server</span><span class="sxs-lookup"><span data-stu-id="442b5-130">Bring your own IP addresses and DNS servers</span></span>
- <span data-ttu-id="442b5-131">Schaffen einer isolierten und hochsicheren Umgebung für Ihre Anwendungen</span><span class="sxs-lookup"><span data-stu-id="442b5-131">Create an isolated and highly-secure environment for your applications</span></span>
- <span data-ttu-id="442b5-132">Herstellen einer Verbindung zwischen Ihrem virtuellen Computer und Ihrem lokalen Netzwerk über eine der verfügbaren [Verbindungsoptionen](https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-about-vpngateways#s2smulti)</span><span class="sxs-lookup"><span data-stu-id="442b5-132">Connect your VM to your on-premises network using one of several [connectivity options](https://docs.microsoft.com/azure/vpn-gateway/vpn-gateway-about-vpngateways#s2smulti)</span></span>
- <span data-ttu-id="442b5-133">Integrieren Ihres virtuellen Computers in Ihr lokales Netzwerk mithilfe von [ExpressRoute](https://azure.microsoft.com/services/expressroute/)</span><span class="sxs-lookup"><span data-stu-id="442b5-133">Integrate your virtual machine into your on-premises network using [ExpressRoute](https://azure.microsoft.com/services/expressroute/)</span></span>

<span data-ttu-id="442b5-134">Informationen zu den ersten Schritten finden Sie in der [Dokumentation zu Virtual Network](https://docs.microsoft.com/azure/virtual-network/).</span><span class="sxs-lookup"><span data-stu-id="442b5-134">To get started, see the [Virtual Network documentation](https://docs.microsoft.com/azure/virtual-network/)</span></span>

### <a name="active-directory"></a><span data-ttu-id="442b5-135">Active Directory</span><span class="sxs-lookup"><span data-stu-id="442b5-135">Active Directory</span></span>
<span data-ttu-id="442b5-136">Viele Anwendungen verwenden Active Directory für die Authentifizierung und Identitätsverwaltung.</span><span class="sxs-lookup"><span data-stu-id="442b5-136">Many applications use Active Directory for authentication and identity management.</span></span>  
- <span data-ttu-id="442b5-137">Mit Azure AD Connect können Sie Ihre lokalen Verzeichnisse in Azure Active Directory integrieren.</span><span class="sxs-lookup"><span data-stu-id="442b5-137">Azure AD Connect enables you to integrate your on-premises directories with Azure Active Directory.</span></span>  <span data-ttu-id="442b5-138">Informationen zu den ersten Schritten finden Sie unter [Integrieren Ihrer lokalen Verzeichnisse in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).</span><span class="sxs-lookup"><span data-stu-id="442b5-138">To get started, see [Integrate your on-premises directories with Azure Active Directory](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect).</span></span>  
- <span data-ttu-id="442b5-139">Alternativ können Sie Ihrer Anwendung mit [ExpressRoute](https://azure.microsoft.com/services/expressroute/) den Zugriff auf Ihr lokales Active Directory ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="442b5-139">Alternatively, [ExpressRoute](https://azure.microsoft.com/services/expressroute/) enables your application to access your on-premises Active Directory.</span></span>

### <a name="sql-databases"></a><span data-ttu-id="442b5-140">SQL-DATENBANKEN</span><span class="sxs-lookup"><span data-stu-id="442b5-140">SQL Databases</span></span>

<span data-ttu-id="442b5-141">Wenn Ihre Anwendung eine lokale Datenbank verwendet, kann sie standardmäßig nicht mit ihr kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="442b5-141">If your application is using an on-premises database, your app will not be able to talk to it by default.</span></span> <span data-ttu-id="442b5-142">Sie haben folgende Möglichkeiten:</span><span class="sxs-lookup"><span data-stu-id="442b5-142">You can either:</span></span>
- <span data-ttu-id="442b5-143">Konfigurieren Sie ein Hybridnetzwerk, über das Ihre Anwendung auf die lokal ausgeführte Datenbank zugreifen kann.</span><span class="sxs-lookup"><span data-stu-id="442b5-143">Configure a hybrid network that enables your application to access your database running on-premises.</span></span>  
- <span data-ttu-id="442b5-144">Migrieren Sie Ihre Datenbank zu Azure.</span><span class="sxs-lookup"><span data-stu-id="442b5-144">Migrate your database to the Azure.</span></span>  <span data-ttu-id="442b5-145">Weitere Informationen zum Migrieren einer SQL Server-Datenbank zu Azure finden Sie [hier](dotnet-howto-migrate-sql.md).</span><span class="sxs-lookup"><span data-stu-id="442b5-145">See [Migrate your SQL Server database to Azure](dotnet-howto-migrate-sql.md) for more information.</span></span>

### <a name="high-availability-and-scalability"></a><span data-ttu-id="442b5-146">Hochverfügbarkeit und Skalierbarkeit</span><span class="sxs-lookup"><span data-stu-id="442b5-146">High Availability and Scalability</span></span>

#### <a name="virtual-machine-scale-sets"></a><span data-ttu-id="442b5-147">Skalierungsgruppen für virtuelle Computer</span><span class="sxs-lookup"><span data-stu-id="442b5-147">Virtual Machine Scale Sets</span></span>
<span data-ttu-id="442b5-148">Wenn Ihre Anwendung hochverfügbar und skalierbar sein soll, empfiehlt es sich, das VM-Image zu einer Azure-VM-Skalierungsgruppe zu migrieren, um die Verfügbarkeit und Skalierbarkeit der Anwendung zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="442b5-148">You want to make sure that your application is highly available and can scale, migrate your VM image to an Azure Virtual Machine Scale Set to improve the availability and scalability of your application.</span></span>  <span data-ttu-id="442b5-149">Mit VM-Skalierungsgruppen können Sie einen bereits konfigurierten virtuellen Computer verwenden oder eine Buildpipeline für die Erstellung eines Images mit Ihrer Anwendung einrichten.</span><span class="sxs-lookup"><span data-stu-id="442b5-149">VM Scale Sets provide the ability to use an existing VM you’ve already configured or set up a build pipeline to build an image with your application.</span></span>  

<span data-ttu-id="442b5-150">Informationen zu den ersten Schritten finden Sie unter [Bereitstellen der App in VM-Skalierungsgruppen](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app).</span><span class="sxs-lookup"><span data-stu-id="442b5-150">To get started, see [Deploy your application on virtual machine scale sets](https://docs.microsoft.com/azure/virtual-machine-scale-sets/virtual-machine-scale-sets-deploy-app).</span></span>

#### <a name="centralized-logging"></a><span data-ttu-id="442b5-151">Zentralisierte Protokollierung</span><span class="sxs-lookup"><span data-stu-id="442b5-151">Centralized Logging</span></span>
<span data-ttu-id="442b5-152">Wenn Ihre Anwendung über mehrere Instanzen hinweg ausgeführt wird, empfiehlt es sich unter Umständen, die Protokolle an einem zentralen Ort zu speichern – beispielsweise in [Azure Storage](https://docs.microsoft.com/azure/storage/).</span><span class="sxs-lookup"><span data-stu-id="442b5-152">When running your application across multiple instances, consider storing your logs in a centralized location such as [Azure Storage](https://docs.microsoft.com/azure/storage/).</span></span>

## <a name="next-steps"></a><span data-ttu-id="442b5-153">Nächste Schritte</span><span class="sxs-lookup"><span data-stu-id="442b5-153">Next steps</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="442b5-154">Migrieren einer SQL Server-Datenbank zu Azure</span><span class="sxs-lookup"><span data-stu-id="442b5-154">Migrate a SQL Server database to Azure</span></span>](dotnet-howto-migrate-sql.md)