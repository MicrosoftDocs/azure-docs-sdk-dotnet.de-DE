---
title: "Azure Data Factory-Bibliotheken für .NET"
description: "Referenz für Azure Data Factory-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Data Factory
author: camsoper
ms.author: casoper
manager: douge
ms.date: 07/20/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.openlocfilehash: e0b85d7d3988febca6dce7f4038825d74e4b8d2e
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-data-factory-libraries-for-net"></a>Azure Data Factory-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Data Factory ist ein cloudbasierter Datenintegrationsdienst. Er ermöglicht Ihnen das Erstellen datengesteuerter Workflows in der Cloud zum Orchestrieren und Automatisieren von Datenverschiebung und Datentransformation.

Weitere Informationen finden Sie unter [Einführung in Azure Data Factory](/azure/data-factory/data-factory-introduction).

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Planen datengesteuerter Workflows (Pipelines).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a>Codebeispiel

Das folgende Beispiel verwendet die Verwaltungsbibliothek zum Erstellen einer Data Factory.

```csharp
DataFactoryManagementClient client = new DataFactoryManagementClient(aadTokenCredentials, resourceManagerUri);
client.DataFactories.CreateOrUpdate(resourceGroupName,
    new DataFactoryCreateOrUpdateParameters()
    {
        DataFactory = new DataFactory()
        {
            Name = dataFactoryName,
            Location = "westus",
            Properties = new DataFactoryProperties()
        }
    }
);
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a>Beispiele

* [MyDriving – eine Azure IOT- und Mobilbeispielanwendung](https://azure.microsoft.com/resources/samples/mydriving/), die mittels Data Factory Einblicke steuert.

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
