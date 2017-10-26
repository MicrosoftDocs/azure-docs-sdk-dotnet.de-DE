---
title: "Azure Billing-Bibliotheken für .NET"
description: "Referenz für Azure Billing-Bibliotheken für .NET"
keywords: Azure, .NET, SDK, API, Billing
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
ms.openlocfilehash: 8df15d55a80991f29b694f4af06a20514bf20b32
ms.sourcegitcommit: 2c08a778353ed743b9e437ed85f2e1dfb21b9427
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/26/2017
---
# <a name="azure-billing-libraries-for-net"></a><span data-ttu-id="16c93-104">Azure Billing-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="16c93-104">Azure Billing libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="16c93-105">Übersicht</span><span class="sxs-lookup"><span data-stu-id="16c93-105">Overview</span></span>

<span data-ttu-id="16c93-106">Die Azure Billing-API (Vorschau) bietet programmgesteuerten Zugriff auf Ihre Azure-Abrechnungsinformationen und -Rechnungen.</span><span class="sxs-lookup"><span data-stu-id="16c93-106">Azure Billing API (preview) provides programmatic access to your Azure billing information and invoices.</span></span>

## <a name="management-library"></a><span data-ttu-id="16c93-107">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="16c93-107">Management library</span></span>

<span data-ttu-id="16c93-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="16c93-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="16c93-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="16c93-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a><span data-ttu-id="16c93-110">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="16c93-110">Code Example</span></span>

<span data-ttu-id="16c93-111">Stellen Sie eine Verbindung mit Azure her, und rufen Sie eine Liste von Rechnungen ab.</span><span class="sxs-lookup"><span data-stu-id="16c93-111">Connect to Azure and get a list of invoices.</span></span>

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
> [<span data-ttu-id="16c93-112">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="16c93-112">Explore the management APIs</span></span>](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a><span data-ttu-id="16c93-113">Beispiele</span><span class="sxs-lookup"><span data-stu-id="16c93-113">Samples</span></span>

* [<span data-ttu-id="16c93-114">Nutzungs-API</span><span class="sxs-lookup"><span data-stu-id="16c93-114">Usage API</span></span>](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [<span data-ttu-id="16c93-115">RateCard-API</span><span class="sxs-lookup"><span data-stu-id="16c93-115">RateCard API</span></span>](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [<span data-ttu-id="16c93-116">Mehrinstanzenfähige Webanwendung</span><span class="sxs-lookup"><span data-stu-id="16c93-116">Multi-Tenant Web Application</span></span>](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
