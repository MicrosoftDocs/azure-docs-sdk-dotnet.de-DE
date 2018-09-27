---
title: Azure Billing-Bibliotheken für .NET
description: Referenz für Azure Billing-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: multiple
ms.openlocfilehash: 88b90c71d29eacf61e4da2099f8a054d74df4a83
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190253"
---
# <a name="azure-billing-libraries-for-net"></a>Azure Billing-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Die Azure Billing-API (Vorschau) bietet programmgesteuerten Zugriff auf Ihre Azure-Abrechnungsinformationen und -Rechnungen.

## <a name="management-library"></a>Verwaltungsbibliothek

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a>Codebeispiel

Stellen Sie eine Verbindung mit Azure her, und rufen Sie eine Liste von Rechnungen ab.

```csharp
/* Include these directives
using Microsoft.Rest.Azure.Authentication;
using Microsoft.Azure.Management.Billing;
using Microsoft.Azure.Management.Billing.Models;
*/

// Log into Azure
var serviceCreds = ApplicationTokenProvider.LoginSilentAsync(tenantId, clientId, secret);
var billingClient = new BillingClient(serviceCreds);
billingClient.SubscriptionId = subscriptionId;

// Get list of invoices
billingClient.Invoices.List();
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a>Beispiele

* [Nutzungs-API](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [RateCard-API](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [Mehrinstanzenfähige Webanwendung](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
