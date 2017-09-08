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
# <a name="azure-data-factory-libraries-for-net"></a><span data-ttu-id="4bb12-104">Azure Data Factory-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="4bb12-104">Azure Data Factory libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="4bb12-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="4bb12-105">Overview</span></span>

<span data-ttu-id="4bb12-106">Azure Data Factory ist ein cloudbasierter Datenintegrationsdienst.</span><span class="sxs-lookup"><span data-stu-id="4bb12-106">Azure Data Factory is a cloud-based data integration service.</span></span> <span data-ttu-id="4bb12-107">Er ermöglicht Ihnen das Erstellen datengesteuerter Workflows in der Cloud zum Orchestrieren und Automatisieren von Datenverschiebung und Datentransformation.</span><span class="sxs-lookup"><span data-stu-id="4bb12-107">It enables you to create data-driven workflows in the cloud to orchestrate and automate data movement and data transformation.</span></span>

<span data-ttu-id="4bb12-108">Weitere Informationen finden Sie unter [Einführung in Azure Data Factory](/azure/data-factory/data-factory-introduction).</span><span class="sxs-lookup"><span data-stu-id="4bb12-108">To learn more, read the [Introduction to Azure Data Factory](/azure/data-factory/data-factory-introduction).</span></span>

## <a name="management-library"></a><span data-ttu-id="4bb12-109">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="4bb12-109">Management library</span></span>

<span data-ttu-id="4bb12-110">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Planen datengesteuerter Workflows (Pipelines).</span><span class="sxs-lookup"><span data-stu-id="4bb12-110">Use the management library to create and schedule data-driven workflows (pipelines).</span></span>

<span data-ttu-id="4bb12-111">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="4bb12-111">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.DataFactories) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="4bb12-112">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="4bb12-112">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.DataFactories
```

```bash
dotnet add package Microsoft.Azure.Management.DataFactories
```

### <a name="code-example"></a><span data-ttu-id="4bb12-113">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="4bb12-113">Code Example</span></span>

<span data-ttu-id="4bb12-114">Das folgende Beispiel verwendet die Verwaltungsbibliothek zum Erstellen einer Data Factory.</span><span class="sxs-lookup"><span data-stu-id="4bb12-114">The following example uses the management library to create a data factory.</span></span>

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
> [<span data-ttu-id="4bb12-115">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="4bb12-115">Explore the management APIs</span></span>](/dotnet/api/overview/azure/datafactories/management)

## <a name="samples"></a><span data-ttu-id="4bb12-116">Beispiele</span><span class="sxs-lookup"><span data-stu-id="4bb12-116">Samples</span></span>

* <span data-ttu-id="4bb12-117">[MyDriving – eine Azure IOT- und Mobilbeispielanwendung](https://azure.microsoft.com/resources/samples/mydriving/), die mittels Data Factory Einblicke steuert.</span><span class="sxs-lookup"><span data-stu-id="4bb12-117">[MyDriving - An Azure IOT and Mobile Sample Application](https://azure.microsoft.com/resources/samples/mydriving/) that uses Data Factory to drive insights.</span></span>

<span data-ttu-id="4bb12-118">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="4bb12-118">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
