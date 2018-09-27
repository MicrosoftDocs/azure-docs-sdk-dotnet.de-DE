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
# <a name="power-bi-embedded-libraries-for-net"></a>Power BI Embedded-Bibliotheken für .NET

[Power BI](https://powerbi.microsoft.com/) ist ein cloudbasierter Business Analytics-Dienst, der Ihnen eine einzelne Ansicht Ihrer äußerst wichtigen Geschäftsdaten bietet.

Weitere Informationen zum Verwenden von Power BI mit .NET finden Sie unter [Einbetten mit Power BI](https://powerbi.microsoft.com/en-us/documentation/powerbi-developer-embedding/).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Clientbibliothek zum Herstellen einer Verbindung mit Power BI-APIs, um auf Datasets und Berichte zuzugreifen und zu interagieren.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.PowerBI.Api) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus.

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.PowerBI.Api
```

### <a name="example"></a>Beispiel

Im folgenden Beispiel wird eine Liste von Datasets und Berichten abgerufen und angezeigt.

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
> [Informationen zu den Client-APIs](https://powerbi.microsoft.com/documentation/powerbi-developer-rest-api-reference/)

## <a name="samples"></a>Beispiele

* [Power BI Developer Samples](https://github.com/Microsoft/PowerBI-Developer-Samples) (Power BI-Entwicklerbeispiele)
* [Power BI-.NET-GitHub-Repository](https://github.com/Microsoft/PowerBI-CSharp)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
