---
title: Azure Billing-Bibliotheken für .NET
description: Referenz für Azure Billing-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Billing
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 97a4c642e8be03db7e31e8c9bc71dcf9c3fc1447
ms.sourcegitcommit: bfa1898c97798991215d08ce89dea87efff44157
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/28/2018
ms.locfileid: "37065510"
---
# <a name="azure-billing-libraries-for-net"></a><span data-ttu-id="bffe4-104">Azure Billing-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="bffe4-104">Azure Billing libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="bffe4-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="bffe4-105">Overview</span></span>

<span data-ttu-id="bffe4-106">Die Azure Billing-API (Vorschau) bietet programmgesteuerten Zugriff auf Ihre Azure-Abrechnungsinformationen und -Rechnungen.</span><span class="sxs-lookup"><span data-stu-id="bffe4-106">Azure Billing API (preview) provides programmatic access to your Azure billing information and invoices.</span></span>

## <a name="management-library"></a><span data-ttu-id="bffe4-107">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="bffe4-107">Management library</span></span>

<span data-ttu-id="bffe4-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="bffe4-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="bffe4-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="bffe4-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a><span data-ttu-id="bffe4-110">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="bffe4-110">Code Example</span></span>

<span data-ttu-id="bffe4-111">Stellen Sie eine Verbindung mit Azure her, und rufen Sie eine Liste von Rechnungen ab.</span><span class="sxs-lookup"><span data-stu-id="bffe4-111">Connect to Azure and get a list of invoices.</span></span>

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
> [<span data-ttu-id="bffe4-112">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="bffe4-112">Explore the management APIs</span></span>](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a><span data-ttu-id="bffe4-113">Beispiele</span><span class="sxs-lookup"><span data-stu-id="bffe4-113">Samples</span></span>

* [<span data-ttu-id="bffe4-114">Nutzungs-API</span><span class="sxs-lookup"><span data-stu-id="bffe4-114">Usage API</span></span>](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [<span data-ttu-id="bffe4-115">RateCard-API</span><span class="sxs-lookup"><span data-stu-id="bffe4-115">RateCard API</span></span>](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [<span data-ttu-id="bffe4-116">Mehrinstanzenfähige Webanwendung</span><span class="sxs-lookup"><span data-stu-id="bffe4-116">Multi-Tenant Web Application</span></span>](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
