<span data-ttu-id="4b4de-101">Ihre .NET-Anwendung benötigt Berechtigungen zum Lesen und Erstellen von Ressourcen in Ihrem Azure-Abonnement, um die Azure-Verwaltungsbibliotheken für .NET zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="4b4de-101">Your .NET application needs permissions to read and create resources in your Azure subscription in order to use the Azure Management Libraries for .NET.</span></span> <span data-ttu-id="4b4de-102">Erstellen Sie einen Dienstprinzipal, und konfigurieren Sie Ihre App so, dass sie mit dessen Anmeldeinformationen ausgeführt wird, um diesen Zugriff zu gewähren.</span><span class="sxs-lookup"><span data-stu-id="4b4de-102">Create a service principal and configure your app to run with its credentials to grant this access.</span></span> <span data-ttu-id="4b4de-103">Dienstprinzipale ermöglichen die Erstellung eines nicht interaktiven, Ihrer Identität zugeordneten Kontos, dem Sie nur die Berechtigungen erteilen, die zum Ausführen Ihrer App erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="4b4de-103">Service principals provide a way to create a non-interactive account associated with your identity to which you grant only the privileges your app needs to run.</span></span>

<span data-ttu-id="4b4de-104">Melden Sie sich zuerst bei Azure PowerShell an:</span><span class="sxs-lookup"><span data-stu-id="4b4de-104">First, login to Azure PowerShell:</span></span>

```powershell
Login-AzureRmAccount
```

<span data-ttu-id="4b4de-105">Beachten Sie die angezeigten Informationen zu Ihrem Mandanten und Abonnement:</span><span class="sxs-lookup"><span data-stu-id="4b4de-105">Note the information displayed about your tenant and subscription:</span></span>

```plaintext
Environment           : AzureCloud
Account               : jane@contoso.com
TenantId              : 43413cc1-5886-4711-9804-8cfea3d1c3ee
SubscriptionId        : 15dbcfa8-4b93-4c9a-881c-6189d39f04d4
SubscriptionName      : my-subscription
CurrentStorageAccount : 
```

<span data-ttu-id="4b4de-106">[Erstellen Sie einen Dienstprinzipal mithilfe von PowerShell](/powershell/azure/create-azure-service-principal-azureps), wie hier gezeigt:</span><span class="sxs-lookup"><span data-stu-id="4b4de-106">[Create a service principal using PowerShell](/powershell/azure/create-azure-service-principal-azureps) as shown below.</span></span> 

> [!NOTE]
> <span data-ttu-id="4b4de-107">Wenn das Cmdlet `New-AzureRmADServicePrincipal` unten „Another object with the same value for property identifierUris already exists“ zurückgibt, enthält Ihr Mandant bereits einen Dienstprinzipal mit diesem Namen.</span><span class="sxs-lookup"><span data-stu-id="4b4de-107">If the `New-AzureRmADServicePrincipal` cmdlet below returns "Another object with the same value for property identifierUris already exists," there is already a service principal by that name in your tenant.</span></span> <span data-ttu-id="4b4de-108">Verwenden Sie einen anderen Wert für den Parameter **DisplayName**.</span><span class="sxs-lookup"><span data-stu-id="4b4de-108">Use a different value for the **DisplayName** parameter.</span></span> 

```powershell
# Create the service principal (use a strong password)
$cred = Get-Credential
$sp = New-AzureRmADServicePrincipal -DisplayName "AzureDotNetTest" -Password $cred.Password

# Give it the permissions it needs...
New-AzureRmRoleAssignment -ServicePrincipalName $sp.ApplicationId -RoleDefinitionName Contributor

# Display the Application ID, because we'll need it later.
$sp | Select DisplayName, ApplicationId
```

<span data-ttu-id="4b4de-109">Notieren Sie sich unbedingt die ApplicationId:</span><span class="sxs-lookup"><span data-stu-id="4b4de-109">Make sure to note the ApplicationId:</span></span>

```plaintext
DisplayName     ApplicationId
-----------     -------------
AzureDotNetTest a2ab11af-01aa-4759-8345-7803287dbd39
```
