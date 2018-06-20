---
title: Azure Key Vault-Bibliotheken für .NET
description: Referenz für Azure Key Vault-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Key Vault
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: key-vault
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 3b8bcb9135794592f493db679e60fd40116d05e6
ms.sourcegitcommit: 4114b8821f20e02f4185fcea7549d716f29b9c90
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/24/2017
ms.locfileid: "23489184"
---
# <a name="azure-key-vault-libraries-for-net"></a>Azure Key Vault-Bibliotheken für .NET

## <a name="overview"></a>Übersicht

Der Azure-Schlüsseltresor unterstützt Sie dabei, kryptografische Schlüssel und geheime Schlüssel zu schützen, die von Cloudanwendungen und -diensten verwendet werden.

Lesen Sie die gründliche Beantwortung der Frage [Was ist Key Vault?](/azure/key-vault/key-vault-whatis), gehen Sie dann [Erste Schritte mit dem Azure-Schlüsseltresor](/azure/key-vault/key-vault-get-started), oder lernen Sie das [Verwenden von Key Vault über eine Web-App](/azure/key-vault/key-vault-use-from-web-application).

## <a name="client-library"></a>Clientbibliothek

Verwenden Sie die Clientbibliothek zum Verwalten von Schlüsseln und zugehörigen Objekte wie z.B. Zertifikaten und Geheimnissen.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.KeyVault) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.KeyVault
```

```bash
dotnet add package Microsoft.Azure.KeyVault
```

### <a name="example"></a>Beispiel

Das folgende Beispiel ruft das Geheimnis für einen bestimmten Schlüssel ab, der in den Anwendungseinstellungen identifiziert wird.

```csharp
KeyVaultClient kv = new KeyVaultClient(new KeyVaultClient.AuthenticationCallback(securityToken));

SecretBundle sec = await kv.GetSecretAsync(WebConfigurationManager.AppSettings["SecretUri"]);

// sec.Value holds the secret
```

> [!div class="nextstepaction"]
> [Informationen zu den Client-APIs](/dotnet/api/overview/azure/keyvault/client)

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek zum Erstellen, Löschen und Abfragen von Schlüsseltresoren.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.KeyVault.Fluent) direkt von der [Paket-Manager-Konsole][PackageManager] in Visual Studio aus oder mit der [.NET Core-CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.KeyVault.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.KeyVault.Fluent
```

### <a name="example"></a>Beispiel

Das folgende Beispiel veranschaulicht das Erstellen eines neuen Schlüsseltresors für eine bestimmte Ressourcengruppe und einen Speicherort.

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
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/keyvault/management)

## <a name="samples"></a>Beispiele

* [Herunterladen der Azure Key Vault-Clientbeispiele](https://www.microsoft.com/download/details.aspx?id=45343)
* [Getting Started with Azure Client Side Encryption in .NET](https://azure.microsoft.com/resources/samples/storage-dotnet-client-side-encryption/) (Erste Schritte mit clientseitiger Azure-Verschlüsselung in .NET)


Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
