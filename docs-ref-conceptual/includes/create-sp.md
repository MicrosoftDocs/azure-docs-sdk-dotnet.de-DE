Ihre .NET-Anwendung benötigt Berechtigungen zum Lesen und Erstellen von Ressourcen in Ihrem Azure-Abonnement, um die Azure-Verwaltungsbibliotheken für .NET zu verwenden. Erstellen Sie einen Dienstprinzipal, und konfigurieren Sie Ihre App so, dass sie mit dessen Anmeldeinformationen ausgeführt wird, um diesen Zugriff zu gewähren. Dienstprinzipale ermöglichen die Erstellung eines nicht interaktiven, Ihrer Identität zugeordneten Kontos, dem Sie nur die Berechtigungen erteilen, die zum Ausführen Ihrer App erforderlich sind.

Melden Sie sich zuerst bei Azure PowerShell an:

```powershell
Login-AzureRmAccount
```

Beachten Sie die angezeigten Informationen zu Ihrem Mandanten und Abonnement:

```plaintext
Environment           : AzureCloud
Account               : jane@contoso.com
TenantId              : 43413cc1-5886-4711-9804-8cfea3d1c3ee
SubscriptionId        : 15dbcfa8-4b93-4c9a-881c-6189d39f04d4
SubscriptionName      : my-subscription
CurrentStorageAccount : 
```

[Erstellen Sie einen Dienstprinzipal mithilfe von PowerShell](/powershell/azure/create-azure-service-principal-azureps), wie hier:

```powershell
# Create the service principal (use a strong password)
$sp = New-AzureRmADServicePrincipal -DisplayName "AzureDotNetTest" -Password "password"

# Give it the permissions it needs...
New-AzureRmRoleAssignment -ServicePrincipalName $sp.ApplicationId -RoleDefinitionName Contributor

# Display the Application ID, because we'll need it later.
$sp | Select DisplayName, ApplicationId
```

Notieren Sie sich unbedingt die ApplicationId:

```plaintext
DisplayName     ApplicationId
-----------     -------------
AzureDotNetTest a2ab11af-01aa-4759-8345-7803287dbd39
```
