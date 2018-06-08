---
title: Azure Container Instances-Bibliotheken für .NET
description: Referenz für Azure Container Instances-Bibliotheken für .NET
keywords: Azure, .NET, SDK, API, Container Instances, ACI
author: mmacy
ms.author: marsma
manager: jeconnoc
ms.date: 05/25/2018
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: dcontainer-instances
ms.custom: devcenter, svc-overview
ms.openlocfilehash: 033f67a989b0ed6cfcb67a6212c0d5c46c485afa
ms.sourcegitcommit: 4ae9f77a9300a4fe54d0179055ae61191078f207
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/07/2018
ms.locfileid: "34567182"
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

## <a name="examples"></a>Beispiele

### <a name="create-container-group---single-container"></a>Containergruppe erstellen – einzelner Container

In diesem Beispiel wird eine Containergruppe mit einem einzelnen Container erstellt.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

### <a name="create-container-group---multiple-containers"></a>Containergruppe erstellen – mehrere Container

In diesem Beispiel wird eine Containergruppe mit zwei Containern erstellt: einem Anwendungscontainer und einem Sidecar-Container.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

### <a name="asynchronous-container-create-with-polling"></a>Asynchrone Containererstellung mit Abruf

In diesem Beispiel wird mithilfe der asynchronen Erstellungsmethode eine Containergruppe mit einem einzelnen Container erstellt. Anschließend wird die Containergruppe von Azure abgerufen ihr Status ausgegeben, bis er „Wird ausgeführt“ lautet.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

### <a name="create-task-based-container-group"></a>Aufgabenbasierte Containergruppe erstellen

In diesem Beispiel wird eine Containergruppe mit einem einzelnen aufgabenbasierten Container erstellt. Der Container wird mit der [Neustartrichtlinie](/azure/container-instances/container-instances-restart-policy) „Nie“ und einer [benutzerdefinierten Befehlszeile](/azure/container-instances/container-instances-restart-policy#command-line-override) konfiguriert.

Wenn Sie einen einzelnen Befehl mit mehreren Befehlszeilenargumenten ausführen möchten, z.B. `echo FOO BAR`, müssen Sie sie als ein Zeichenfolgenarray für die `WithStartingCommandLines`-Methode angeben. Beispiel: 

`WithStartingCommandLines("echo", "FOO", "BAR")`

Wenn Sie jedoch mehrere Befehle mit (potenziell) mehreren Argumente ausführen möchten, müssen Sie eine Shell ausführen und die verketteten Befehle als Argument übergeben. Hiermit wird beispielsweise ein `echo`- sowie ein `tail`-Befehl ausgeführt:

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

### <a name="list-container-groups"></a>Containergruppen auflisten

In diesem Beispiel sind die Containergruppen in einer Ressourcengruppe aufgeführt.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

### <a name="get-an-existing-container-group"></a>Vorhandene Containergruppe abrufen

In diesem Beispiel wird eine bestimmte Containergruppe abgerufen, die sich in einer Ressourcengruppe befindet. Dann werden einige ihrer Eigenschaften und deren Werte ausgegeben.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

### <a name="delete-a-container-group"></a>Containergruppe löschen

In diesem Beispiel wird eine Containergruppe aus einer Ressourcengruppe gelöscht.

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]

## <a name="api-reference"></a>API-Referenz

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a>Beispiele

* Der Quellcode für die vorhergehenden Beispiele ist auf GitHub zu finden:

  [Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]

* Weitere Azure Container Instances-Codebeispiele:

  [Azure-Codebeispiele][samples]

Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
