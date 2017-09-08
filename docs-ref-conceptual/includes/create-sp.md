<span data-ttu-id="8c682-101">Ihre .NET-Anwendung benötigt Berechtigungen zum Lesen und Erstellen von Ressourcen in Ihrem Azure-Abonnement, um die Azure-Verwaltungsbibliotheken für .NET zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="8c682-101">Your .NET application needs permissions to read and create resources in your Azure subscription in order to use the Azure Management Libraries for .NET.</span></span> <span data-ttu-id="8c682-102">Erstellen Sie einen Dienstprinzipal, und konfigurieren Sie Ihre App so, dass sie mit dessen Anmeldeinformationen ausgeführt wird, um diesen Zugriff zu gewähren.</span><span class="sxs-lookup"><span data-stu-id="8c682-102">Create a service principal and configure your app to run with its credentials to grant this access.</span></span> <span data-ttu-id="8c682-103">Dienstprinzipale ermöglichen die Erstellung eines nicht interaktiven, Ihrer Identität zugeordneten Kontos, dem Sie nur die Berechtigungen erteilen, die zum Ausführen Ihrer App erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="8c682-103">Service principals provide a way to create a non-interactive account associated with your identity to which you grant only the privileges your app needs to run.</span></span>

<span data-ttu-id="8c682-104">Melden Sie sich zuerst bei Azure PowerShell an:</span><span class="sxs-lookup"><span data-stu-id="8c682-104">First, login to Azure PowerShell:</span></span>

```powershell
Login-AzureRmAccount
```

<span data-ttu-id="8c682-105">Beachten Sie die angezeigten Informationen zu Ihrem Mandanten und Abonnement:</span><span class="sxs-lookup"><span data-stu-id="8c682-105">Note the information displayed about your tenant and subscription:</span></span>

```plaintext
Environment           : AzureCloud
Account               : jane@contoso.com
TenantId              : 43413cc1-5886-4711-9804-8cfea3d1c3ee
SubscriptionId        : 15dbcfa8-4b93-4c9a-881c-6189d39f04d4
SubscriptionName      : my-subscription
CurrentStorageAccount : 
```

<span data-ttu-id="8c682-106">[Erstellen Sie einen Dienstprinzipal mithilfe von PowerShell](/powershell/azure/create-azure-service-principal-azureps), wie hier:</span><span class="sxs-lookup"><span data-stu-id="8c682-106">[Create a service principal using PowerShell](/powershell/azure/create-azure-service-principal-azureps), like this:</span></span>

```powershell
# Create the service principal (use a strong password)
$sp = New-AzureRmADServicePrincipal -DisplayName "AzureDotNetTest" -Password "password"

# Give it the permissions it needs...
New-AzureRmRoleAssignment -ServicePrincipalName $sp.ApplicationId -RoleDefinitionName Contributor

# Display the Application ID, because we'll need it later.
$sp | Select DisplayName, ApplicationId
```

<span data-ttu-id="8c682-107">Notieren Sie sich unbedingt die ApplicationId:</span><span class="sxs-lookup"><span data-stu-id="8c682-107">Make sure to note the ApplicationId:</span></span>

```plaintext
DisplayName     ApplicationId
-----------     -------------
AzureDotNetTest a2ab11af-01aa-4759-8345-7803287dbd39
```
