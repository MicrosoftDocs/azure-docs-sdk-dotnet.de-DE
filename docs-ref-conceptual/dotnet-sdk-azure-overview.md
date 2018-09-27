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
# <a name="azure-net-apis"></a><span data-ttu-id="ce625-103">Azure .NET-APIs</span><span class="sxs-lookup"><span data-stu-id="ce625-103">Azure .NET APIs</span></span>

<span data-ttu-id="ce625-104">Die Azure .NET-APIs ermöglichen Ihnen das Nutzen von Azure-Diensten und Verwalten von Azure-Ressourcen mithilfe Ihres Anwendungscodes.</span><span class="sxs-lookup"><span data-stu-id="ce625-104">The Azure .NET APIs let you use Azure services and manage Azure resources from your application code.</span></span> <span data-ttu-id="ce625-105">Die APIs stehen als [NuGet-Pakete](/dotnet/api/overview/azure/) für die Verwendung in Ihren .NET-Projekten zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="ce625-105">The APIs are available as [NuGet packages](/dotnet/api/overview/azure/) for use in your .NET projects.</span></span> 

## <a name="manage-azure-resources"></a><span data-ttu-id="ce625-106">Verwalten von Azure-Ressourcen</span><span class="sxs-lookup"><span data-stu-id="ce625-106">Manage Azure resources</span></span>

<span data-ttu-id="ce625-107">Der Azure-Bibliotheken für .NET ermöglichen Ihnen das Erstellen und Verwalten von Azure-Ressourcen mithilfe Ihrer .NET-Anwendungen.</span><span class="sxs-lookup"><span data-stu-id="ce625-107">The Azure libraries for .NET let you create and manage Azure resources from your .NET applications.</span></span>

<span data-ttu-id="ce625-108">Viele der Pakete für die Verwaltung von Azure-Ressourcen verfügen über eine [Fluent](dotnet-sdk-azure-concepts.md)-Benutzeroberfläche, um Ressourcen genau Ihren Anforderungen entsprechend zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="ce625-108">Many of the packages for managing Azure resources have a [fluent](dotnet-sdk-azure-concepts.md) interface to configure resources exactly to your specifications.</span></span> <span data-ttu-id="ce625-109">Zum Erstellen eines virtuellen Windows-Computers müssen Sie beispielsweise den folgenden Code schreiben:</span><span class="sxs-lookup"><span data-stu-id="ce625-109">For example, to create a Windows VM you would write the following code:</span></span>

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

<span data-ttu-id="ce625-110">Überprüfen Sie die [.NET-Dienstliste](/dotnet/api/overview/azure/), um sofort mit dem Einsatz der Bibliotheken in Ihren Projekten zu beginnen.</span><span class="sxs-lookup"><span data-stu-id="ce625-110">Review the [.NET service list](/dotnet/api/overview/azure/) to start using the libraries immediately with your projects.</span></span> <span data-ttu-id="ce625-111">Lesen Sie dann den [Artikel mit den ersten Schritten](dotnet-sdk-azure-get-started.md) zum Einrichten der Authentifizierung und Ausführung von Beispielcode in Ihrem eigenen Azure-Abonnement.</span><span class="sxs-lookup"><span data-stu-id="ce625-111">Then read the [get started article](dotnet-sdk-azure-get-started.md) to set up authentication and run sample code against your own Azure subscription.</span></span>  <span data-ttu-id="ce625-112">Im [Artikel zu den Konzepten](dotnet-sdk-azure-concepts.md) werden die Konventionen behandelt, die das SDK befolgt, und wie Sie diese zum Vereinfachen Ihres Anwendungscode nutzen können.</span><span class="sxs-lookup"><span data-stu-id="ce625-112">The [concepts article](dotnet-sdk-azure-concepts.md) goes into the conventions the SDK uses and how to leverage them to simplify your application code.</span></span> <span data-ttu-id="ce625-113">Neue Funktionen, wichtige Änderungen und Migrationsanweisungen finden Sie in den [Versionshinweisen](dotnet-sdk-azure-release-notes.md).</span><span class="sxs-lookup"><span data-stu-id="ce625-113">New features, breaking changes, and migration instructions are available in the [release notes](dotnet-sdk-azure-release-notes.md).</span></span>

## <a name="consume-azure-services"></a><span data-ttu-id="ce625-114">Nutzen von Azure-Diensten</span><span class="sxs-lookup"><span data-stu-id="ce625-114">Consume Azure services</span></span>

<span data-ttu-id="ce625-115">Zusätzlich zur Nutzung von .NET-APIs zum Erstellen und programmgesteuerten Verwalten von Ressourcen in Azure können Sie auch mithilfe der .NET-APIs Ihre Anwendungen mit diesen Ressourcen verbinden und sie zur Laufzeit verwenden.</span><span class="sxs-lookup"><span data-stu-id="ce625-115">In addition to using .NET APIs to create and programmatically manage resources within Azure, you can also then use .NET APIs to connect your applications to these resources and use them at runtime.</span></span>  <span data-ttu-id="ce625-116">Sie können z.B. eine Verbindung mit einer SQL-Datenbank herstellen oder Daten in Azure Storage speichern.</span><span class="sxs-lookup"><span data-stu-id="ce625-116">For example, you might connect to a SQL Database or store data within Azure Storage.</span></span>  <span data-ttu-id="ce625-117">Sie können ermitteln, welches NuGet-Paket für einen bestimmten Azure-Dienst verwendet werden soll, indem Sie unsere [vollständige Liste der Dienst-APIs](/dotnet/api/overview/azure/) durchsuchen.</span><span class="sxs-lookup"><span data-stu-id="ce625-117">You can identify which NuGet package to use for a particular Azure service by browsing our [full list of service APIs](/dotnet/api/overview/azure/).</span></span>  

## <a name="samples"></a><span data-ttu-id="ce625-118">Beispiele</span><span class="sxs-lookup"><span data-stu-id="ce625-118">Samples</span></span>

<span data-ttu-id="ce625-119">Die folgenden Beispiele decken allgemeine Automatisierungsaufgaben mit den Azure-Bibliotheken für .NET ab:</span><span class="sxs-lookup"><span data-stu-id="ce625-119">The following samples cover common automation tasks with the Azure libraries for .NET:</span></span>

- [<span data-ttu-id="ce625-120">Virtuelle Computer</span><span class="sxs-lookup"><span data-stu-id="ce625-120">Virtual machines</span></span>](dotnet-sdk-azure-virtual-machine-samples.md)
- [<span data-ttu-id="ce625-121">Web-Apps</span><span class="sxs-lookup"><span data-stu-id="ce625-121">Web apps</span></span>](dotnet-sdk-azure-web-apps-samples.md)
- [<span data-ttu-id="ce625-122">SQL-Datenbank</span><span class="sxs-lookup"><span data-stu-id="ce625-122">SQL Database</span></span>](dotnet-sdk-azure-sql-database-samples.md)

<span data-ttu-id="ce625-123">Sowohl in den Dienst- als auch den Verwaltungsbibliotheken ist eine vereinheitlichte [Referenz](/dotnet/api/overview/azure/?view=azure-dotnet) für alle Pakete verfügbar.</span><span class="sxs-lookup"><span data-stu-id="ce625-123">A unified [reference](/dotnet/api/overview/azure/?view=azure-dotnet) is available for all packages in both the service and management libraries.</span></span> <span data-ttu-id="ce625-124">Neue Funktionen, wichtige Änderungen und Migrationsanweisungen finden Sie in den [Versionshinweisen](dotnet-sdk-azure-release-notes.md).</span><span class="sxs-lookup"><span data-stu-id="ce625-124">New features, breaking changes, and migration instructions are available in the [release notes](dotnet-sdk-azure-release-notes.md).</span></span>

[!include[Contribute and community](includes/contribute.md)]