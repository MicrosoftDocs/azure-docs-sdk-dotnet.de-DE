<span data-ttu-id="57491-101">Ihre .NET-Anwendung benötigt Berechtigungen zum Lesen und Erstellen von Ressourcen in Ihrem Azure-Abonnement, um die Azure-Verwaltungsbibliotheken für .NET zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="57491-101">Your .NET application needs permissions to read and create resources in your Azure subscription in order to use the Azure Management Libraries for .NET.</span></span> <span data-ttu-id="57491-102">Erstellen Sie einen Dienstprinzipal, und konfigurieren Sie Ihre App so, dass sie mit dessen Anmeldeinformationen ausgeführt wird, um diesen Zugriff zu gewähren.</span><span class="sxs-lookup"><span data-stu-id="57491-102">Create a service principal and configure your app to run with its credentials to grant this access.</span></span> <span data-ttu-id="57491-103">Dienstprinzipale ermöglichen die Erstellung eines nicht interaktiven, Ihrer Identität zugeordneten Kontos, dem Sie nur die Berechtigungen erteilen, die zum Ausführen Ihrer App erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="57491-103">Service principals provide a way to create a non-interactive account associated with your identity to which you grant only the privileges your app needs to run.</span></span>

<span data-ttu-id="57491-104">Melden Sie sich zuerst bei [Azure Cloud Shell](https://shell.azure.com/bash) an.</span><span class="sxs-lookup"><span data-stu-id="57491-104">First, login to [Azure Cloud Shell](https://shell.azure.com/bash).</span></span> <span data-ttu-id="57491-105">Vergewissern Sie sich, dass Sie derzeit das Abonnement verwenden, in dem der Dienstprinzipal erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="57491-105">Verify you are currently using the subscription in which you want the service principal created.</span></span> 

```azurecli-interactive
az account show
```

<span data-ttu-id="57491-106">Die Informationen zu Ihrem Abonnement werden angezeigt.</span><span class="sxs-lookup"><span data-stu-id="57491-106">Your subscription information is displayed.</span></span>

```json
{
  "environmentName": "AzureCloud",
  "id": "15dbcfa8-4b93-4c9a-881c-6189d39f04d4",
  "isDefault": true,
  "name": "my-subscription",
  "state": "Enabled",
  "tenantId": "43413cc1-5886-4711-9804-8cfea3d1c3ee",
  "user": {
    "cloudShellID": true,
    "name": "jane@contoso.com",
    "type": "user"
  }
}
```

<span data-ttu-id="57491-107">Wenn Sie nicht beim richtigen Abonnement angemeldet sind, wählen Sie das richtige Abonnement durch Eingabe von `az account set -s <name or ID of subscription>` aus.</span><span class="sxs-lookup"><span data-stu-id="57491-107">If you're not logged into the correct subscription, select the correct one by typing `az account set -s <name or ID of subscription>`.</span></span>

<span data-ttu-id="57491-108">Erstellen Sie den Dienstprinzipal mit dem folgenden Befehl:</span><span class="sxs-lookup"><span data-stu-id="57491-108">Create the service principal with the following command:</span></span>

```azurecli-interactive
az ad sp create-for-rbac --sdk-auth
```

<span data-ttu-id="57491-109">Die Dienstprinzipalinformationen werden im JSON-Format angezeigt.</span><span class="sxs-lookup"><span data-stu-id="57491-109">The service principal information is displayed as JSON.</span></span>

```json
{
  "clientId": "b52dd125-9272-4b21-9862-0be667bdf6dc",
  "clientSecret": "ebc6e170-72b2-4b6f-9de2-99410964d2d0",
  "subscriptionId": "ffa52f27-be12-4cad-b1ea-c2c241b6cceb",
  "tenantId": "72f988bf-86f1-41af-91ab-2d7cd011db47",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```

<span data-ttu-id="57491-110">Fügen Sie die kopierte JSON-Ausgabe zur späteren Verwendung in einen Text-Editor ein.</span><span class="sxs-lookup"><span data-stu-id="57491-110">Copy and paste the JSON output to a text editor for use later.</span></span>
