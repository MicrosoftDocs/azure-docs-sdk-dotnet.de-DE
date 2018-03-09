---
title: "Azure-Computebibliotheken für .NET"
description: "Referenz für Azure-Computebibliotheken für .NET"
keywords: Azure, .NET, SDK, API, VM, virtuelle Computer, compute
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: virtual-machines
ms.custom: devcenter, svc-overview
ms.openlocfilehash: cac6dde85a7b0db2c98d0888cb0ee5c60ee31836
ms.sourcegitcommit: dbec35008347b581dd238b882354300e427bec70
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/02/2018
---
# <a name="azure-virtual-machine-libraries-for-net"></a>Azure Virtual Machines-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Bedarfsgesteuerte, skalierbare Computeressourcen unter Linux oder Windows

Informationen zu den ersten Schritten mit virtuellen Azure-Computern finden Sie unter [Erstellen einer Linux-VM mit dem Azure-Portal](https://review.docs.microsoft.com/azure/virtual-machines/linux/quick-create-portal).

## <a name="management-apis"></a>Verwaltungs-APIs

Mit der Verwaltungs-API können Sie virtuelle Windows- und Linux-Computer in Azure über Ihren Code erstellen, konfigurieren und horizontal hochskalieren.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Compute.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Compute.Fluent
```

#### <a name="net-core-cli"></a>.NET Core CLI

```bash
dotnet add package Microsoft.Azure.Management.Compute.Fluent
```

### <a name="code-example"></a>Codebeispiel

Erstellen Sie eine Windows-VM.

```csharp
/* Include these "using" directives...
using Microsoft.Azure.Management.Compute.Fluent;
using Microsoft.Azure.Management.Compute.Fluent.Models;
using Microsoft.Azure.Management.ResourceManager.Fluent.Core;
*/

IVirtualMachine windowsVM = azure.VirtualMachines.Define("MyVirtualMachine")
    .WithRegion(Region.USEast)
    .WithNewResourceGroup("MyResourceGroup")
    .WithNewPrimaryNetwork("10.0.0.0/28")
    .WithPrimaryPrivateIPAddressDynamic()
    .WithNewPrimaryPublicIPAddress("MyIPAddressLabel")
    .WithPopularWindowsImage(KnownWindowsVirtualMachineImage.WindowsServer2012R2Datacenter)
    .WithAdminUsername("UserName")
    .WithAdminPassword("Password")
    .WithSize(VirtualMachineSizeTypes.StandardD3V2)
    .Create();
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](https://docs.microsoft.com/dotnet/api/overview/azure/virtualmachines/management?view=azure-dotnet)

### <a name="samples"></a>Beispiele

* [Erstellen und Verwalten von virtuellen Computern](/dotnet/azure/dotnet-sdk-azure-virtual-machine-samples)
* [Deploy an SSH Enabled VM with a Template with .NET (Bereitstellen eines SSH-fähigen virtuellen Computers mit einer Vorlage mit .NET)](https://azure.microsoft.com/resources/samples/resource-manager-dotnet-template-deployment/)

Zeigen Sie die [vollständige](https://azure.microsoft.com/resources/samples/?platform=dotnet&term=VM) Liste von VM-Beispielen an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
