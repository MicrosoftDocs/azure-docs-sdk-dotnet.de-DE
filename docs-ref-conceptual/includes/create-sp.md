---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 5c8cb328802cfb94e944e4241852fb9568e8507f
ms.sourcegitcommit: e534dad2d96b72ab6a9bc4b5567508962bd7e05c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/22/2019
ms.locfileid: "58343329"
---
Ihre .NET-Anwendung benötigt Berechtigungen zum Lesen und Erstellen von Ressourcen in Ihrem Azure-Abonnement, um die Azure-Verwaltungsbibliotheken für .NET zu verwenden. Erstellen Sie einen Dienstprinzipal, und konfigurieren Sie Ihre App so, dass sie mit dessen Anmeldeinformationen ausgeführt wird, um diesen Zugriff zu gewähren. Dienstprinzipale ermöglichen die Erstellung eines nicht interaktiven, Ihrer Identität zugeordneten Kontos, dem Sie nur die Berechtigungen erteilen, die zum Ausführen Ihrer App erforderlich sind.

Melden Sie sich zuerst bei [Azure Cloud Shell](https://shell.azure.com/bash) an. Vergewissern Sie sich, dass Sie derzeit das Abonnement verwenden, in dem der Dienstprinzipal erstellt werden soll. 

```azurecli-interactive
az account show
```

Die Informationen zu Ihrem Abonnement werden angezeigt.

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

Wenn Sie nicht beim richtigen Abonnement angemeldet sind, wählen Sie das richtige Abonnement durch Eingabe von `az account set -s <name or ID of subscription>` aus.

Erstellen Sie den Dienstprinzipal mit dem folgenden Befehl:

```azurecli-interactive
az ad sp create-for-rbac --sdk-auth
```

Die Dienstprinzipalinformationen werden im JSON-Format angezeigt.

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

Fügen Sie die kopierte JSON-Ausgabe zur späteren Verwendung in einen Text-Editor ein.
