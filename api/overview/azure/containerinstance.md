---
title: Azure Container Instances-Bibliotheken für .NET
description: Referenz für Azure Container Instances-Bibliotheken für .NET
ms.date: 06/11/2018
ms.topic: reference
ms.service: container-instances
ms.openlocfilehash: 8642fc654546edde81aeaa520f52b2aff9720e55
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348102"
---
# <a name="azure-container-instances-libraries-for-net"></a>Azure Container Instances-Bibliotheken für .NET

Verwenden Sie die Azure Container Instances-Bibliotheken für .NET zum Erstellen und Verwalten von Azure-Containerinstanzen. In der [Übersicht über Azure Container Instances](/azure/container-instances/container-instances-overview) erfahren Sie mehr.

## <a name="management-library"></a>Verwaltungsbibliothek

Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Verwalten von Azure-Containerinstanzen in Azure.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.ContainerInstance.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ContainerInstance.Fluent
```

## <a name="example-source"></a>Beispielquelle

Wenn Sie die folgenden Codebeispiele im Kontext sehen möchten, finden Sie sie im folgenden GitHub-Repository:

[Azure-Samples/aci-docs-sample-dotnet](https://github.com/Azure-Samples/aci-docs-sample-dotnet)

## <a name="authentication"></a>Authentifizierung

Eine der einfachsten Möglichkeiten zum Authentifizieren von SDK-Clients ist die Verwendung der [dateibasierten Authentifizierung][sdk-auth]. Bei der dateibasierten Authentifizierung wird beim Instanziieren des Clientobjekts [IAzure][iazure] eine Anmeldeinformationendatei analysiert. Diese Anmeldeinformationen werden anschließend für die Authentifizierung über Azure verwendet. So verwenden Sie die dateibasierte Authentifizierung

1. Erstellen Sie mit der [Azure CLI](/cli/azure) oder mit [Cloud Shell](https://shell.azure.com/) eine Datei mit Anmeldeinformationen:

   `az ad sp create-for-rbac --sdk-auth > my.azureauth`

   Wenn Sie [Cloud Shell](https://shell.azure.com/) zum Erstellen der Datei mit Anmeldeinformationen verwenden, kopieren Sie ihren Inhalt in eine lokale Datei, auf die die .NET-Anwendung zugreifen kann.

2. Legen Sie die Umgebungsvariable `AZURE_AUTH_LOCATION` auf den vollständigen Pfad der erstellten Datei mit Anmeldeinformationen fest. Beispiel (in der Bash-Shell):

   ```bash
   export AZURE_AUTH_LOCATION=/home/yourusername/my.azureauth
   ```

Nachdem Sie die Anmeldeinformationendatei erstellt und die Umgebungsvariable `AZURE_AUTH_LOCATION` aufgefüllt haben, initialisieren Sie das Clientobjekt [IAzure][iazure] mithilfe der Methode [Azure.Authenticate][iazure-authenticate]. Das Beispielprojekt ruft zuerst den Wert `AZURE_AUTH_LOCATION` ab und ruft dann eine Methode auf, die ein initialisiertes `IAzure`-Clientobjekt zurückgibt:

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#L29-L35 "Get environment variable")]

Diese Methode aus der Beispielanwendung gibt die initialisierte [IAzure][iazure]-Instanz zurück, die dann als erster Parameter an alle anderen Methoden im Beispiel übergeben wird:

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#azure_auth "Authenticate IAzure client object")]

Weitere Informationen zu den verfügbaren Authentifizierungsmethoden in den .NET-Verwaltungsbibliotheken für Azure finden Sie unter [Authentication in Azure Management Libraries for .NET][sdk-auth] (Authentifizieren in den Azure-Verwaltungsbibliotheken für .NET).

## <a name="create-container-group---single-container"></a>Erstellen einer Containergruppe – einzelner Container

In diesem Beispiel wird eine Containergruppe mit einem einzelnen Container erstellt.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

## <a name="create-container-group---multiple-containers"></a>Erstellen einer Containergruppe – mehrere Container

In diesem Beispiel wird eine Containergruppe mit zwei Containern erstellt: einem Anwendungscontainer und einem Sidecar-Container.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

## <a name="asynchronous-container-create-with-polling"></a>Asynchrone Containererstellung mit Abruf

In diesem Beispiel wird mithilfe der asynchronen Erstellungsmethode eine Containergruppe mit einem einzelnen Container erstellt. Anschließend wird die Containergruppe von Azure abgerufen ihr Status ausgegeben, bis er „Wird ausgeführt“ lautet.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

## <a name="create-task-based-container-group"></a>Erstellen einer aufgabenbasierten Containergruppe

In diesem Beispiel wird eine Containergruppe mit einem einzelnen aufgabenbasierten Container erstellt. Der Container wird mit der [Neustartrichtlinie](/azure/container-instances/container-instances-restart-policy) „Nie“ und einer [benutzerdefinierten Befehlszeile](/azure/container-instances/container-instances-restart-policy#command-line-override) konfiguriert.

Wenn Sie einen einzelnen Befehl mit mehreren Befehlszeilenargumenten ausführen möchten, z.B. `echo FOO BAR`, müssen Sie sie als ein Zeichenfolgenarray für die `WithStartingCommandLines`-Methode angeben. Beispiel: 

`WithStartingCommandLines("echo", "FOO", "BAR")`

Wenn Sie jedoch mehrere Befehle mit (potenziell) mehreren Argumente ausführen möchten, müssen Sie eine Shell ausführen und die verketteten Befehle als Argument übergeben. Hiermit wird beispielsweise ein `echo`- sowie ein `tail`-Befehl ausgeführt:

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

## <a name="list-container-groups"></a>Auflisten von Containergruppen

In diesem Beispiel sind die Containergruppen in einer Ressourcengruppe aufgeführt.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

## <a name="get-an-existing-container-group"></a>Abrufen einer vorhandenen Containergruppe

In diesem Beispiel wird eine bestimmte Containergruppe abgerufen, die sich in einer Ressourcengruppe befindet. Dann werden einige ihrer Eigenschaften und deren Werte ausgegeben.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

## <a name="delete-a-container-group"></a>Löschen einer Containergruppe

In diesem Beispiel wird eine Containergruppe aus einer Ressourcengruppe gelöscht.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet --> [!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]

## <a name="api-reference"></a>API-Referenz

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a>Beispiele

* Der Quellcode für die vorhergehenden Beispiele ist auf GitHub zu finden:

  [Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]

* Weitere Azure Container Instances-Codebeispiele:

  [Azure-Codebeispiele][samples]

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

<!-- LINKS - External -->
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[sdk-auth]: https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md

<!-- LINKS - Internal -->
[DotNetCLI]: /dotnet/core/tools/dotnet-add-package
[PackageManager]: /nuget/tools/package-manager-console
[iazure]: /dotnet/api/microsoft.azure.management.fluent.azure
[iazure-authenticate]: /dotnet/api/microsoft.azure.management.fluent.azure.authenticate
