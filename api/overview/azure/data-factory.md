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
# <a name="azure-data-factory-libraries-for-net"></a><span data-ttu-id="f36d5-104">Azure Data Factory-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="f36d5-104">Azure Data Factory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="f36d5-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="f36d5-105">Overview</span></span>

<span data-ttu-id="f36d5-106">Azure Data Factory ist ein cloudbasierter Datenintegrationsdienst.</span><span class="sxs-lookup"><span data-stu-id="f36d5-106">Azure Data Factory is a cloud-based data integration service.</span></span> <span data-ttu-id="f36d5-107">Er ermöglicht Ihnen das Erstellen datengesteuerter Workflows in der Cloud zum Orchestrieren und Automatisieren von Datenverschiebung und Datentransformation.</span><span class="sxs-lookup"><span data-stu-id="f36d5-107">It enables you to create data-driven workflows in the cloud to orchestrate and automate data movement and data transformation.</span></span>

<span data-ttu-id="f36d5-108">Weitere Informationen finden Sie unter [Einführung in Azure Data Factory](/azure/data-factory/data-factory-introduction).</span><span class="sxs-lookup"><span data-stu-id="f36d5-108">To learn more, read the [Introduction to Azure Data Factory](/azure/data-factory/data-factory-introduction).</span></span>

## <a name="management-library---data-factory-v2-preview"></a><span data-ttu-id="f36d5-109">Verwaltungsbibliothek: Data Factory V2 (Vorschauversion)</span><span class="sxs-lookup"><span data-stu-id="f36d5-109">Management library - Data Factory V2 (Preview)</span></span>

<span data-ttu-id="f36d5-110">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Planen datengesteuerter Workflows (Pipelines) in Data Factory V2 (Vorschauversion).</span><span class="sxs-lookup"><span data-stu-id="f36d5-110">Use the management library to create and schedule data-driven workflows (pipelines) in Data Factory V2 (Preview).</span></span>  <span data-ttu-id="f36d5-111">Weitere Informationen finden Sie unter [Create a data factory and pipeline using .NET SDK](/azure/data-factory/quickstart-create-data-factory-dot-net) (Erstellen einer Data Factory und Pipeline mit dem .NET SDK).</span><span class="sxs-lookup"><span data-stu-id="f36d5-111">For more information, see [Create a data factory and pipeline using .NET SDK](/azure/data-factory/quickstart-create-data-factory-dot-net).</span></span>

<span data-ttu-id="f36d5-112">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="f36d5-112">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactory) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f36d5-113">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="f36d5-113">Visual Studio Package Manager</span></span>

```powershell
# Get the most recent prerelease package
Install-Package Microsoft.Azure.Management.DataFactory -Prerelease
```

```bash
# Be sure to include the most recent version from the NuGet package page
dotnet add package Microsoft.Azure.Management.DataFactory --version 0.2.0-preview
```

### <a name="code-example"></a><span data-ttu-id="f36d5-114">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="f36d5-114">Code Example</span></span>

<span data-ttu-id="f36d5-115">Das folgende Beispiel verwendet die Verwaltungsbibliothek zum Erstellen einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="f36d5-115">The following example uses the management library to create a data factory.</span></span>

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
> [<span data-ttu-id="f36d5-116">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="f36d5-116">Explore the management APIs</span></span>](/dotnet/api/microsoft.azure.management.datafactory)

## <a name="management-library---data-factory-v1"></a><span data-ttu-id="f36d5-117">Verwaltungsbibliothek: Data Factory V1</span><span class="sxs-lookup"><span data-stu-id="f36d5-117">Management library - Data Factory V1</span></span>

<span data-ttu-id="f36d5-118">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Planen datengesteuerter Workflows (Pipelines) in Data Factory Version 1.</span><span class="sxs-lookup"><span data-stu-id="f36d5-118">Use the management library to create and schedule data-driven workflows (pipelines) in Data Factory Version 1.</span></span>  <span data-ttu-id="f36d5-119">Weitere Informationen finden Sie in der Dokumentation zu [Data Factory Version 1](/azure/data-factory/v1/data-factory-introduction).</span><span class="sxs-lookup"><span data-stu-id="f36d5-119">For more information, review the documentation for [Data Factory Version 1](/azure/data-factory/v1/data-factory-introduction).</span></span>

<span data-ttu-id="f36d5-120">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="f36d5-120">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f36d5-121">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="f36d5-121">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a><span data-ttu-id="f36d5-122">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="f36d5-122">Code Example</span></span>

<span data-ttu-id="f36d5-123">Das folgende Beispiel verwendet die Verwaltungsbibliothek zum Erstellen einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="f36d5-123">The following example uses the management library to create a data factory.</span></span>

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
> [<span data-ttu-id="f36d5-124">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="f36d5-124">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a><span data-ttu-id="f36d5-125">Beispiele</span><span class="sxs-lookup"><span data-stu-id="f36d5-125">Samples</span></span>

* <span data-ttu-id="f36d5-126">[MyDriving – eine Azure IOT- und Mobilbeispielanwendung](https://azure.microsoft.com/resources/samples/mydriving/), die mittels Data Factory Einblicke steuert.</span><span class="sxs-lookup"><span data-stu-id="f36d5-126">[MyDriving - An Azure IOT and Mobile Sample Application](https://azure.microsoft.com/resources/samples/mydriving/) that uses Data Factory to drive insights.</span></span>

<span data-ttu-id="f36d5-127">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="f36d5-127">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
