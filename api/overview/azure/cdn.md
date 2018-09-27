---
title: Azure CDN-Bibliotheken für .NET
description: Referenz für Azure CDN-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: cdn
ms.openlocfilehash: 6475edbe4fa0d01739de5cff76038aa6e7fd2cf9
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190123"
---
# <a name="azure-cdn-libraries-for-net"></a>Azure CDN-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Das Azure Content Delivery Network (CDN) speichert statische Webinhalte an strategisch platzierten Standorten zwischen, um beim Bereitstellen von Inhalten für Benutzer einen maximalen Durchsatz zu ermöglichen. Das CDN bietet Entwicklern eine globale Lösung für die Übermittlung von Inhalten mit hoher Bandbreite durch Zwischenspeichern der Inhalte auf physischen Knoten auf der ganzen Welt.

Weitere Informationen zu Azure CDN finden Sie unter [Übersicht über Azure Content Delivery Network](https://docs.microsoft.com/azure/cdn/cdn-overview).


## <a name="management-library"></a>Verwaltungsbibliothek

Sie können die Azure CDN-Bibliothek für .NET verwenden, um die Erstellung und Verwaltung von CDN-Profilen und -Endpunkten zu automatisieren. 

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Cdn.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Cdn.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.Cdn.Fluent
```

### <a name="example"></a>Beispiel

In diesem Beispiel erstellen Sie ein neues CDN-Profil mit einem neuen Endpunkt, der auf `www.contoso.com` verweist.

```csharp
/* Include these "using" directives.
using Microsoft.Azure.Management.Cdn.Fluent;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

ICdnProfile profileDefinition = azure.CdnProfiles.Define("CdnProfileName")
    .WithRegion(Region.USCentral)
    .WithExistingResourceGroup("ResourceGroupName")
    .WithStandardVerizonSku()
    .WithNewEndpoint("www.contoso.com")
    .Create();

```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/cdn/management)


## <a name="samples"></a>Beispiele

* [Erste Schritte mit CDN (CDN-Verwaltung) in .NET](https://github.com/Azure-Samples/cdn-dotnet-manage-cdn)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
