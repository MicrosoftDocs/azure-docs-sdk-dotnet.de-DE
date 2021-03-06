---
title: Azure Data Lake Analytics-Bibliotheken für .NET
description: Referenz für Azure Data Lake Analytics-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: data-lake-analytics
ms.openlocfilehash: 829f9245ae06c64c4ad9a175fd25c742533a284e
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47189793"
---
# <a name="azure-data-lake-analytics-libraries-for-net"></a>Azure Data Lake Analytics-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Data Lake Analytics ist ein bedarfsgesteuerter Dienst für Analyseaufträge zum Vereinfachen von Big Data-Analysen.

Weitere Informationen finden Sie in der [Übersicht über Microsoft Azure Data Lake Analytics](/azure/data-lake-analytics/data-lake-analytics-overview).

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek zum Herstellen einer Verbindung mit dem Dienst und Verwalten von Analytics-Aufträgen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Analytics) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Analytics
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Analytics
```

### <a name="code-example"></a>Codebeispiel

In diesem Beispiel werden die Clients zum Herstellen einer Verbindung mit einem Analytics-Konto und zu dessen Verwaltung erstellt.

```csharp
/*
using AdlClient 
*/

// Setup authentication for this demo
Authentication auth = new Authentication("microsoft.onmicrosoft.com"); // change this to YOUR tenant
auth.Authenticate();

// Identify the accounts
AnalyticsAccountRef adla_account = new AnalyticsAccountRef(subscriptionId, resourceGroup, userName);

// Create the clients
AzureClient az = new AzureClient(auth);
AnalyticsClient adla = new AnalyticsClient(auth, adla_account);
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/datalakeanalytics/management)

## <a name="samples"></a>Beispiele
* [Azure Data Lake-.NET-Client-Beispiel](https://azure.microsoft.com/resources/samples/data-lake-dotnet-client/)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
