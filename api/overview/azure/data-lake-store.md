---
title: "Azure Data Lake Store-Bibliotheken für .NET"
description: "Referenz für Azure Data Lake Store-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Data Lake Store
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: data-lake-store
ms.custom: devcenter, svc-overview
ms.openlocfilehash: e8380c4a9ebf86f03fe87fc800dffda10e48e60a
ms.sourcegitcommit: 3e904e6e4f04f1c92d729459434c85faff32e386
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/09/2017
---
# <a name="azure-data-lake-store-libraries-for-net"></a>Azure Data Lake Store-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Azure Data Lake-Speicher ist ein unternehmensweites riesiges Repository für Big Data-Analyseworkloads. Azure Data Lake bietet Ihnen die Möglichkeit, Daten von beliebiger Größe, Art und Erfassungsgeschwindigkeit zur Durchführung operativer und explorativer Analysen an einem einzigen Ort zu erfassen.

Weitere Informationen finden Sie in der [Übersicht über Azure Data Lake Store](/azure/data-lake-store/data-lake-store-overview).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Clientbibliothek zum Ausführen von Dateisystemvorgängen in Data Lake Store, etwa zum Erstellen von Ordnern in einem Data Lake Store-Konto und Hochladen bzw. Herunterladen von Dateien.  Ein vollständiges Tutorial zur Verwendung von Data Lake Store mit .NET finden Sie unter [Dateisystemvorgänge in Azure Data Lake Store per .NET SDK](/azure/data-lake-store/data-lake-store-data-operations-net-sdk).

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.DataLake.Store
```
### <a name="authentication"></a>Authentifizierung

* Informationen zur Authentifizierung von Endbenutzern für Ihre Anwendung finden Sie unter [End-user authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-end-user-authenticate-net-sdk) (Authentifizierung von Endbenutzern mit Data Lake Store per .NET SDK).
* Informationen zur Dienst-zu-Dienst-Authentifizierung für Ihre Anwendung finden Sie unter [Service-to-service authentication with Data Lake Store using .NET SDK](/azure/data-lake-store/data-lake-store-service-to-service-authenticate-net-sdk) (Dienst-zu-Dienst-Authentifizierung mit Data Lake Store per .NET SDK).

### <a name="code-example"></a>Codebeispiel

Mit dem folgenden Codeausschnitt wird das Data Lake Store-Dateisystem-Clientobjekt erstellt, das zum Ausführen von Anforderungen für den Dienst genutzt wird.

```csharp
// Create client objects
AdlsClient client = AdlsClient.CreateClient(_adlsAccountName, adlCreds);
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/datalakestore/client)


## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek, um die Verbindung mit Ihren Big Data-Repositorys herzustellen und sie zu verwalten.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.DataLake.Store) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.DataLake.Store
```

```bash
dotnet add package Microsoft.Azure.Management.DataLake.Store
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/datalakestore/management)


## <a name="samples"></a>Beispiele

* [Azure Data Lake-.NET-Client-Beispiel](https://azure.microsoft.com/en-us/resources/samples/data-lake-dotnet-client/)

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
