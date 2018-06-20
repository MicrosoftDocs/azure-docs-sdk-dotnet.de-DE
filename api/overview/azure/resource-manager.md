---
title: Azure Resource Manager-Bibliotheken für .NET
description: Referenz für Azure Resource Manager-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Resource Manager
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
ms.openlocfilehash: f9fe96fcdc94d3d27445f462c5220def9f2966da
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
ms.locfileid: "23566371"
---
# <a name="azure-resource-manager-libraries-for-net"></a>Azure Resource Manager-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Mit dem Azure-Ressourcen-Manager können Sie als Gruppe mit den Ressourcen in Ihrer Lösung arbeiten.  Weitere Informationen zu Resource Manager finden Sie unter [Übersicht über den Azure Resource Manager](https://docs.microsoft.com/azure/azure-resource-manager/resource-group-overview).

## <a name="management-library"></a>Verwaltungsbibliothek

Die Azure Resource Manager-Bibliothek für .NET ermöglicht Ihnen das Erstellen, Aktualisieren, Löschen und Auflisten von Ressourcen und Ressourcengruppen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ResourceManager.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ResourceManager.Fluent
```

### <a name="example"></a>Beispiel

Dieses Beispiel erstellt eine neue Ressourcengruppe.

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.ResourceManager.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IResourceGroup resourceGroup = azure.ResourceGroups
    .Define("ResourceGroupName")
    .WithRegion(Region.USWest)
    .Create();
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/resources/management)


## <a name="samples"></a>Beispiele

* [Verwalten von Ressourcengruppen](https://github.com/Azure-Samples/resources-dotnet-manage-resource-group)
* [Verwalten von Ressourcen](https://github.com/Azure-Samples/resources-dotnet-manage-resource)
* [Bereitstellen von Ressourcen mit ARM-Vorlagen](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template)
* [Bereitstellen von Ressourcen mit ARM-Vorlagen (Fortschritt)](https://github.com/Azure-Samples/resources-dotnet-deploy-using-arm-template-with-progress)


[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
