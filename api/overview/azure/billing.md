---
title: Azure Billing-Bibliotheken für .NET
description: Referenz für Azure Billing-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: billing
ms.openlocfilehash: 196b9b4ed5f1f5f6794d86a43d26827355800d7b
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348082"
---
# <a name="azure-billing-libraries-for-net"></a><span data-ttu-id="f31b5-103">Azure Billing-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="f31b5-103">Azure Billing libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="f31b5-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="f31b5-104">Overview</span></span>

<span data-ttu-id="f31b5-105">Die Azure Billing-API (Vorschau) bietet programmgesteuerten Zugriff auf Ihre Azure-Abrechnungsinformationen und -Rechnungen.</span><span class="sxs-lookup"><span data-stu-id="f31b5-105">Azure Billing API (preview) provides programmatic access to your Azure billing information and invoices.</span></span>

## <a name="management-library"></a><span data-ttu-id="f31b5-106">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="f31b5-106">Management library</span></span>

<span data-ttu-id="f31b5-107">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="f31b5-107">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.Billing) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="f31b5-108">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="f31b5-108">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.Billing
```

```bash
dotnet add package Microsoft.Azure.Management.Billing
```

### <a name="code-example"></a><span data-ttu-id="f31b5-109">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="f31b5-109">Code Example</span></span>

<span data-ttu-id="f31b5-110">Stellen Sie eine Verbindung mit Azure her, und rufen Sie eine Liste von Rechnungen ab.</span><span class="sxs-lookup"><span data-stu-id="f31b5-110">Connect to Azure and get a list of invoices.</span></span>

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
> [<span data-ttu-id="f31b5-111">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="f31b5-111">Explore the management APIs</span></span>](/dotnet/api/overview/azure/billing/management)

## <a name="samples"></a><span data-ttu-id="f31b5-112">Beispiele</span><span class="sxs-lookup"><span data-stu-id="f31b5-112">Samples</span></span>

* [<span data-ttu-id="f31b5-113">Nutzungs-API</span><span class="sxs-lookup"><span data-stu-id="f31b5-113">Usage API</span></span>](https://github.com/Azure-Samples/billing-dotnet-usage-api)
* [<span data-ttu-id="f31b5-114">RateCard-API</span><span class="sxs-lookup"><span data-stu-id="f31b5-114">RateCard API</span></span>](https://github.com/Azure-Samples/billing-dotnet-ratecard-api)
* [<span data-ttu-id="f31b5-115">Mehrinstanzenfähige Webanwendung</span><span class="sxs-lookup"><span data-stu-id="f31b5-115">Multi-Tenant Web Application</span></span>](https://github.com/Azure-Samples/billing-dotnet-webapp-multitenant)

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
