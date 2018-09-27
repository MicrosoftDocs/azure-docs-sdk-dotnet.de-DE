---
title: Azure Key Vault-Bibliotheken für .NET
description: Referenz für Azure Key Vault-Bibliotheken für .NET
ms.date: 10/19/2017
ms.topic: reference
ms.service: key-vault
ms.openlocfilehash: a42eb9684bcfb8e8d2209235f61bbf6962cf5e9e
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190553"
---
# <a name="azure-key-vault-libraries-for-net"></a><span data-ttu-id="255f7-103">Azure Key Vault-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="255f7-103">Azure Key Vault libraries for .NET</span></span>

## <a name="overview"></a><span data-ttu-id="255f7-104">Übersicht</span><span class="sxs-lookup"><span data-stu-id="255f7-104">Overview</span></span>

<span data-ttu-id="255f7-105">Azure Key Vault unterstützt Sie dabei, kryptografische Schlüssel und Geheimnisse zu schützen, die von Cloudanwendungen und -diensten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="255f7-105">Azure Key Vault helps safeguard cryptographic keys and secrets used by cloud applications and services.</span></span>

<span data-ttu-id="255f7-106">Lesen Sie die gründliche Beantwortung der Frage [Was ist Key Vault?](/azure/key-vault/key-vault-whatis), gehen Sie dann [Erste Schritte mit dem Azure-Schlüsseltresor](/azure/key-vault/key-vault-get-started), oder lernen Sie das [Verwenden von Key Vault über eine Web-App](/azure/key-vault/key-vault-use-from-web-application).</span><span class="sxs-lookup"><span data-stu-id="255f7-106">Read more about [What is Key Vault?](/azure/key-vault/key-vault-whatis) then [Get started with Azure Key Vault](/azure/key-vault/key-vault-get-started) or learn how to [Use Key Vault from a web app](/azure/key-vault/key-vault-use-from-web-application).</span></span>

## <a name="client-library"></a><span data-ttu-id="255f7-107">Clientbibliothek</span><span class="sxs-lookup"><span data-stu-id="255f7-107">Client library</span></span>

<span data-ttu-id="255f7-108">Verwenden Sie die Clientbibliothek zum Verwalten von Schlüsseln und zugehörigen Objekte wie z.B. Zertifikaten und Geheimnissen.</span><span class="sxs-lookup"><span data-stu-id="255f7-108">Use the client library to manage keys and related assets such as certificates and secrets.</span></span>

<span data-ttu-id="255f7-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.KeyVault) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="255f7-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.KeyVault) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="255f7-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="255f7-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.KeyVault
```

```bash
dotnet add package Microsoft.Azure.KeyVault
```

### <a name="example"></a><span data-ttu-id="255f7-111">Beispiel</span><span class="sxs-lookup"><span data-stu-id="255f7-111">Example</span></span>

<span data-ttu-id="255f7-112">Das folgende Beispiel ruft das Geheimnis für einen bestimmten Schlüssel ab, der in den Anwendungseinstellungen identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="255f7-112">The following example retrieves the secret for a specific key that is identified in the application settings.</span></span>

```csharp
KeyVaultClient kv = new KeyVaultClient(new KeyVaultClient.AuthenticationCallback(securityToken));

SecretBundle sec = await kv.GetSecretAsync(WebConfigurationManager.AppSettings["SecretUri"]);

// sec.Value holds the secret
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="255f7-113">Informationen zu den Client-APIs</span><span class="sxs-lookup"><span data-stu-id="255f7-113">Explore the client APIs</span></span>](/dotnet/api/overview/azure/keyvault/client)

## <a name="management-library"></a><span data-ttu-id="255f7-114">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="255f7-114">Management library</span></span>

<span data-ttu-id="255f7-115">Verwenden Sie die Verwaltungsbibliothek zum Erstellen, Löschen und Abfragen von Schlüsseltresoren.</span><span class="sxs-lookup"><span data-stu-id="255f7-115">Use the management library to create, delete, and query key vaults.</span></span>

<span data-ttu-id="255f7-116">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="255f7-116">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="255f7-117">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="255f7-117">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.KeyVault.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.KeyVault.Fluent
```

### <a name="example"></a><span data-ttu-id="255f7-118">Beispiel</span><span class="sxs-lookup"><span data-stu-id="255f7-118">Example</span></span>

<span data-ttu-id="255f7-119">Das folgende Beispiel veranschaulicht das Erstellen eines neuen Schlüsseltresors für eine bestimmte Ressourcengruppe und einen Speicherort.</span><span class="sxs-lookup"><span data-stu-id="255f7-119">The following example demonstrates how to create a new key vault for a given resource group and location.</span></span>

```csharp
using (KeyVaultManagementClient client = new KeyVaultManagementClient(
    new TokenCloudCredentials(subscriptionId, accessToken)))
{
    client.Vaults.CreateOrUpdate(resourceGroupName, "myKeyVault", new VaultCreateOrUpdateParameters
    {
        Properties = new VaultProperties
        {
            EnabledForDeployment = true,
            EnabledForDiskEncryption = true,
            EnabledForTemplateDeployment = true,
            Location = resourceGroupLocation,
            // SKU level, access policies, tenants, etc.
        }
    });
}
```

> [!div class="nextstepaction"]
> [<span data-ttu-id="255f7-120">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="255f7-120">Explore the management APIs</span></span>](/dotnet/api/overview/azure/keyvault/management)

## <a name="samples"></a><span data-ttu-id="255f7-121">Beispiele</span><span class="sxs-lookup"><span data-stu-id="255f7-121">Samples</span></span>

* [<span data-ttu-id="255f7-122">Herunterladen der Azure Key Vault-Clientbeispiele</span><span class="sxs-lookup"><span data-stu-id="255f7-122">Download the Azure Key Vault client samples</span></span>](https://www.microsoft.com/download/details.aspx?id=45343)
* <span data-ttu-id="255f7-123">[Getting Started with Azure Client Side Encryption in .NET](https://azure.microsoft.com/resources/samples/storage-dotnet-client-side-encryption/) (Erste Schritte mit clientseitiger Azure-Verschlüsselung in .NET)</span><span class="sxs-lookup"><span data-stu-id="255f7-123">[Getting Started with Azure Client Side Encryption in .NET](https://azure.microsoft.com/resources/samples/storage-dotnet-client-side-encryption/)</span></span>


<span data-ttu-id="255f7-124">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="255f7-124">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
