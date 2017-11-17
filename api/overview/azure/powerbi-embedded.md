---
title: "Power BI Embedded-Bibliotheken für .NET"
description: "Referenz für Power BI Embedded-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Power BI Embedded
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: f61c931d930fce75d038af8b8f1355f1de9cde7c
ms.sourcegitcommit: fe3e1475208ba47d4630788bac88b952cc3fe61f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/23/2017
---
# <a name="power-bi-embedded-libraries-for-net"></a><span data-ttu-id="3a416-104">Power BI Embedded-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="3a416-104">Power BI Embedded libraries for .NET</span></span>

<span data-ttu-id="3a416-105">[Power BI](https://powerbi.microsoft.com/) ist ein cloudbasierter Business Analytics-Dienst, der Ihnen eine einzelne Ansicht Ihrer äußerst wichtigen Geschäftsdaten bietet.</span><span class="sxs-lookup"><span data-stu-id="3a416-105">[Power BI](https://powerbi.microsoft.com/) is a cloud-based business analytics service that gives you a single view of your most critical business data.</span></span>

<span data-ttu-id="3a416-106">Weitere Informationen zum Verwenden von Power BI mit .NET finden Sie unter [Einbetten mit Power BI](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/).</span><span class="sxs-lookup"><span data-stu-id="3a416-106">To learn more about using Power BI with .NET, see [Embedding with Power BI](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/).</span></span>

## <a name="client-library"></a><span data-ttu-id="3a416-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="3a416-107">Client library</span></span>

<span data-ttu-id="3a416-108">Verwenden Sie die Clientbibliothek zum Herstellen einer Verbindung mit Power BI-APIs, um auf Datasets und Berichte zuzugreifen und zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="3a416-108">Use the client library to connect with Power BI APIs to access and interact with data sets and reports.</span></span>

<span data-ttu-id="3a416-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.PowerBI.Api) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus.</span><span class="sxs-lookup"><span data-stu-id="3a416-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.PowerBI.Api) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="3a416-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="3a416-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.PowerBI.Api
```

### <a name="example"></a><span data-ttu-id="3a416-111">Beispiel</span><span class="sxs-lookup"><span data-stu-id="3a416-111">Example</span></span>

<span data-ttu-id="3a416-112">Im folgenden Beispiel wird eine Liste von Datasets und Berichten abgerufen und angezeigt.</span><span class="sxs-lookup"><span data-stu-id="3a416-112">The following example retrieves and displays a list of datasets and reports.</span></span>

```csharp
/* Include these'using' directive:
using Microsoft.PowerBI.Api.V2;
using Microsoft.PowerBI.Api.V2.Models;
*/
using (PowerBIClient client = new PowerBIClient(new Uri(apiUrl), tokenCredentials))
{

    Console.WriteLine("\r*** DATASETS ***\r");

    // List of datasets in a group/app workspace
    ODataResponseListDataset datasetList = client.Datasets.GetDatasetsInGroup(groupId);

    foreach(Dataset ds in datasetList.Value)
    {
        Console.WriteLine(ds.Id + " | " + ds.Name);
    }

    Console.WriteLine("\r*** REPORTS ***\r");

    // List of reports in a group/app workspace
    ODataResponseListReport reportList = client.Reports.GetReportsInGroup(groupId);

    foreach (Report rpt in reportList.Value)
    {
        Console.WriteLine(rpt.Id + " | " + rpt.Name +  " | DatasetID = " + rpt.DatasetId);
    }
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="3a416-113">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="3a416-113">Explore the client APIs</span></span>](https://powerbi.microsoft.com/documentation/powerbi-developer-rest-api-reference/)

## <a name="samples"></a><span data-ttu-id="3a416-114">Beispiele</span><span class="sxs-lookup"><span data-stu-id="3a416-114">Samples</span></span>

* <span data-ttu-id="3a416-115">[Power BI Developer Samples](https://github.com/Microsoft/PowerBI-Developer-Samples) (Power BI-Entwicklerbeispiele)</span><span class="sxs-lookup"><span data-stu-id="3a416-115">[Power BI Developer Samples](https://github.com/Microsoft/PowerBI-Developer-Samples)</span></span>
* [<span data-ttu-id="3a416-116">Power BI-.NET-GitHub-Repository</span><span class="sxs-lookup"><span data-stu-id="3a416-116">Power BI .NET GitHub repo</span></span>](https://github.com/Microsoft/PowerBI-CSharp)

<span data-ttu-id="3a416-117">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="3a416-117">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
