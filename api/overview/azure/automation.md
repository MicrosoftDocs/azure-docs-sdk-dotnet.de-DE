---
title: Azure Automation-Bibliotheken für .NET
description: Referenz für Azure Automation-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Automation
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: automation
ms.custom: devcenter, svc-overview
ms.openlocfilehash: e45db49fa71e5ad16ab1e4f26d76cd9b0146ac5f
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065760"
---
# <a name="azure-automation-libraries-for-net"></a>Azure Automation-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Microsoft Azure Automation ermöglicht Benutzern, Aufgaben zu automatisieren, die in einer Cloud- und Unternehmensumgebung normalerweise ausgeführt werden. 

Um mehr zu erfahren, lesen Sie [Azure Automation – Übersicht](/azure/automation/automation-intro).

## <a name="management-library"></a>Verwaltungsbibliothek

Verwalten Sie mit der Verwaltungsbibliothek Runbooks und Aufträge sowie Desired State Configuration-Einstellungen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Automation) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Automation
```

```bash
dotnet add package Microsoft.Azure.Management.Automation
```

### <a name="code-example"></a>Codebeispiel

Das folgende Beispiel veranschaulicht, wie Sie einen neuen Auftrag anhand eines vorhandenen Runbooks starten.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/automation/management)

## <a name="samples"></a>Beispiele

* [AzureBot](https://github.com/Microsoft/AzureBot) verwendet die Automatisierungsbibliothek mit [Bot Framework](https://docs.microsoft.com/bot-framework/) und [Cognitive Services](/cognitive-services), um die Entwicklerproduktivität in Azure zu verbessern.

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
