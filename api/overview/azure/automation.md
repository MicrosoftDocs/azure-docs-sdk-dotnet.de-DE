---
title: "Azure Automation-Bibliotheken für .NET"
description: "Referenz für Azure Automation-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Automation
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: automation
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 2055a5e24d445468763c049c34a5055cea108688
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
---
# <a name="azure-automation-libraries-for-net"></a><span data-ttu-id="662cb-104">Azure Automation-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="662cb-104">Azure Automation libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="662cb-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="662cb-105">Overview</span></span>

<span data-ttu-id="662cb-106">Microsoft Azure Automation ermöglicht Benutzern, Aufgaben zu automatisieren, die in einer Cloud- und Unternehmensumgebung normalerweise ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="662cb-106">Microsoft Azure Automation provides a way for users to automate the tasks that are commonly performed in a cloud and enterprise environment.</span></span> 

<span data-ttu-id="662cb-107">Um mehr zu erfahren, lesen Sie [Azure Automation – Übersicht](/azure/automation/automation-intro).</span><span class="sxs-lookup"><span data-stu-id="662cb-107">Learn more by reading the [Azure Automation Overview](/azure/automation/automation-intro).</span></span>

## <a name="management-library"></a><span data-ttu-id="662cb-108">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="662cb-108">Management library</span></span>

<span data-ttu-id="662cb-109">Verwalten Sie mit der Verwaltungsbibliothek Runbooks und Aufträge sowie Desired State Configuration-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="662cb-109">Using the management library to manage runbooks and jobs and manage Desired State Configuration settings.</span></span>

<span data-ttu-id="662cb-110">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="662cb-110">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="662cb-111">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="662cb-111">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Automation
```

```bash
dotnet add package Microsoft.Azure.Management.Automation
```

### <a name="code-example"></a><span data-ttu-id="662cb-112">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="662cb-112">Code Example</span></span>

<span data-ttu-id="662cb-113">Das folgende Beispiel veranschaulicht, wie Sie einen neuen Auftrag anhand eines vorhandenen Runbooks starten.</span><span class="sxs-lookup"><span data-stu-id="662cb-113">The following example illustrates how to start a new job based on an existing runbook.</span></span>

```csharp
/*
  using Microsoft.Azure.Management.Automation;
*/
AutomationManagementClient client =
    new AutomationManagementClient(new CertificateCloudCredentials(subscriptionId, cert));

// Create job create parameters
JobCreateParameters jcParam = new JobCreateParameters
{
    Properties = new JobCreateProperties
    {
        Runbook = new RunbookAssociationProperty
        {
            Name = runbookName
        },
        Parameters = null // optional parameters here
    }
};

// create runbook job. This gives back the Job
Job job = automationManagementClient.Jobs.Create(automationAccountName, jcParam).Job;
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="662cb-114">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="662cb-114">Explore the management APIs</span></span>](/dotnet/api/overview/azure/automation/management)

## <a name="samples"></a><span data-ttu-id="662cb-115">Beispiele</span><span class="sxs-lookup"><span data-stu-id="662cb-115">Samples</span></span>

* <span data-ttu-id="662cb-116">[AzureBot](https://github.com/Microsoft/AzureBot) verwendet die Automatisierungsbibliothek mit [Bot Framework](https://docs.microsoft.com/bot-framework/) und [Cognitive Services](/cognitive-services), um die Entwicklerproduktivität in Azure zu verbessern.</span><span class="sxs-lookup"><span data-stu-id="662cb-116">[AzureBot](https://github.com/Microsoft/AzureBot) uses the automation library with the [Bot Framework](https://docs.microsoft.com/bot-framework/) and [Cognitive Services](/cognitive-services) to improve developer productivity on Azure</span></span>

<span data-ttu-id="662cb-117">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="662cb-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
