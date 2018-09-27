---
title: Power BI Embedded-Bibliotheken für .NET
description: Referenz für Power BI Embedded-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: multiple
ms.openlocfilehash: acb327b56e89522142e51016a6a9b279f995a674
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190373"
---
# <a name="power-bi-embedded-libraries-for-net"></a><span data-ttu-id="b0d1d-103">Power BI Embedded-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="b0d1d-103">Power BI Embedded libraries for .NET</span></span>

<span data-ttu-id="b0d1d-104">[Power BI](https://powerbi.microsoft.com/) ist ein cloudbasierter Business Analytics-Dienst, der Ihnen eine einzelne Ansicht Ihrer äußerst wichtigen Geschäftsdaten bietet.</span><span class="sxs-lookup"><span data-stu-id="b0d1d-104">[Power BI](https://powerbi.microsoft.com/) is a cloud-based business analytics service that gives you a single view of your most critical business data.</span></span>

<span data-ttu-id="b0d1d-105">Weitere Informationen zum Verwenden von Power BI mit .NET finden Sie unter [Einbetten mit Power BI](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/).</span><span class="sxs-lookup"><span data-stu-id="b0d1d-105">To learn more about using Power BI with .NET, see [Embedding with Power BI](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/).</span></span>

## <a name="client-library"></a><span data-ttu-id="b0d1d-106">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="b0d1d-106">Client library</span></span>

<span data-ttu-id="b0d1d-107">Verwenden Sie die Clientbibliothek zum Herstellen einer Verbindung mit Power BI-APIs, um auf Datasets und Berichte zuzugreifen und zu interagieren.</span><span class="sxs-lookup"><span data-stu-id="b0d1d-107">Use the client library to connect with Power BI APIs to access and interact with data sets and reports.</span></span>

<span data-ttu-id="b0d1d-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.PowerBI.Api) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus.</span><span class="sxs-lookup"><span data-stu-id="b0d1d-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.PowerBI.Api) directly from the Visual Studio [Package Manager console][PackageManager].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="b0d1d-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="b0d1d-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.PowerBI.Api
```

### <a name="example"></a><span data-ttu-id="b0d1d-110">Beispiel</span><span class="sxs-lookup"><span data-stu-id="b0d1d-110">Example</span></span>

<span data-ttu-id="b0d1d-111">Im folgenden Beispiel wird eine Liste von Datasets und Berichten abgerufen und angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b0d1d-111">The following example retrieves and displays a list of datasets and reports.</span></span>

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
> [<span data-ttu-id="b0d1d-112">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="b0d1d-112">Explore the client APIs</span></span>](https://powerbi.microsoft.com/documentation/powerbi-developer-rest-api-reference/)

## <a name="samples"></a><span data-ttu-id="b0d1d-113">Beispiele</span><span class="sxs-lookup"><span data-stu-id="b0d1d-113">Samples</span></span>

* <span data-ttu-id="b0d1d-114">[Power BI Developer Samples](https://github.com/Microsoft/PowerBI-Developer-Samples) (Power BI-Entwicklerbeispiele)</span><span class="sxs-lookup"><span data-stu-id="b0d1d-114">[Power BI Developer Samples](https://github.com/Microsoft/PowerBI-Developer-Samples)</span></span>
* [<span data-ttu-id="b0d1d-115">Power BI-.NET-GitHub-Repository</span><span class="sxs-lookup"><span data-stu-id="b0d1d-115">Power BI .NET GitHub repo</span></span>](https://github.com/Microsoft/PowerBI-CSharp)

<span data-ttu-id="b0d1d-116">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="b0d1d-116">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
