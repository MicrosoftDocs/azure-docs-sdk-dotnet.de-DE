---
title: Azure Data Factory-Bibliotheken für .NET
description: Referenz für Azure Data Factory-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Data Factory
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: data-factory
ms.custom: devcenter, svc-overview
ms.openlocfilehash: b3c492fbfe4a4afa6f06f8c48a370c554a01719c
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065790"
---
# <a name="azure-data-factory-libraries-for-net"></a>Azure Data Factory-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Data Factory ist ein cloudbasierter Datenintegrationsdienst. Er ermöglicht Ihnen das Erstellen datengesteuerter Workflows in der Cloud zum Orchestrieren und Automatisieren von Datenverschiebung und Datentransformation.

Weitere Informationen finden Sie unter [Einführung in Azure Data Factory](/azure/data-factory/data-factory-introduction).

## <a name="management-library---data-factory-v2-preview"></a>Verwaltungsbibliothek: Data Factory V2 (Vorschauversion)

Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Planen datengesteuerter Workflows (Pipelines) in Data Factory V2 (Vorschauversion).  Weitere Informationen finden Sie unter [Create a data factory and pipeline using .NET SDK](/azure/data-factory/quickstart-create-data-factory-dot-net) (Erstellen einer Data Factory und Pipeline mit dem .NET SDK).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
# Get the most recent prerelease package
Install-Package Microsoft.Azure.Management.DataFactory -Prerelease
```

```bash
# Be sure to include the most recent version from the NuGet package page
dotnet add package Microsoft.Azure.Management.DataFactory --version 0.2.0-preview
```

### <a name="code-example"></a>Codebeispiel

Das folgende Beispiel verwendet die Verwaltungsbibliothek zum Erstellen einer Data Factory.

```csharp
/*
using Microsoft.Azure.Management.ResourceManager;
using Microsoft.Azure.Management.DataFactory;
using Microsoft.Azure.Management.DataFactory.Models;
*/

DataFactoryManagementClient client = new DataFactoryManagementClient(tokenCredentials) { SubscriptionId = subscriptionId };
Factory dataFactory = new Factory
{
    Location = region,
    Identity = new FactoryIdentity()
};
client.Factories.CreateOrUpdate(resourceGroup, dataFactoryName, dataFactory);
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/microsoft.azure.management.datafactory)

## <a name="management-library---data-factory-v1"></a>Verwaltungsbibliothek: Data Factory V1

Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Planen datengesteuerter Workflows (Pipelines) in Data Factory Version 1.  Weitere Informationen finden Sie in der Dokumentation zu [Data Factory Version 1](/azure/data-factory/v1/data-factory-introduction).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

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
