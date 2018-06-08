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
# <a name="azure-container-instances-libraries-for-net"></a><span data-ttu-id="80d75-104">Azure Container Instances-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="80d75-104">Azure Container Instances libraries for .NET</span></span>

<span data-ttu-id="80d75-105">Verwenden Sie die Azure Container Instances-Bibliotheken für .NET zum Erstellen und Verwalten von Azure-Containerinstanzen.</span><span class="sxs-lookup"><span data-stu-id="80d75-105">Use the Microsoft Azure Container Instances libraries for .NET to create and manage Azure container instances.</span></span> <span data-ttu-id="80d75-106">In der [Übersicht über Azure Container Instances](/azure/container-instances/container-instances-overview) erfahren Sie mehr.</span><span class="sxs-lookup"><span data-stu-id="80d75-106">Learn more by reading the [Azure Container Instances overview](/azure/container-instances/container-instances-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="80d75-107">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="80d75-107">Management library</span></span>

<span data-ttu-id="80d75-108">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Verwalten von Azure-Containerinstanzen in Azure.</span><span class="sxs-lookup"><span data-stu-id="80d75-108">Use the management library to create and manage Azure container instances in Azure.</span></span>

<span data-ttu-id="80d75-109">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="80d75-109">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

### <a name="visual-studio-package-manager"></a><span data-ttu-id="80d75-110">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="80d75-110">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ContainerInstance.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ContainerInstance.Fluent
```

## <a name="examples"></a><span data-ttu-id="80d75-111">Beispiele</span><span class="sxs-lookup"><span data-stu-id="80d75-111">Examples</span></span>

### <a name="create-container-group---single-container"></a><span data-ttu-id="80d75-112">Containergruppe erstellen – einzelner Container</span><span class="sxs-lookup"><span data-stu-id="80d75-112">Create container group - single container</span></span>

<span data-ttu-id="80d75-113">In diesem Beispiel wird eine Containergruppe mit einem einzelnen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="80d75-113">This example creates a container group with a single container.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

### <a name="create-container-group---multiple-containers"></a><span data-ttu-id="80d75-114">Containergruppe erstellen – mehrere Container</span><span class="sxs-lookup"><span data-stu-id="80d75-114">Create container group - multiple containers</span></span>

<span data-ttu-id="80d75-115">In diesem Beispiel wird eine Containergruppe mit zwei Containern erstellt: einem Anwendungscontainer und einem Sidecar-Container.</span><span class="sxs-lookup"><span data-stu-id="80d75-115">This example creates a container group with two containers: an application container and a sidecar container.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

### <a name="asynchronous-container-create-with-polling"></a><span data-ttu-id="80d75-116">Asynchrone Containererstellung mit Abruf</span><span class="sxs-lookup"><span data-stu-id="80d75-116">Asynchronous container create with polling</span></span>

<span data-ttu-id="80d75-117">In diesem Beispiel wird mithilfe der asynchronen Erstellungsmethode eine Containergruppe mit einem einzelnen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="80d75-117">This example creates a container group with a single container using the async create method.</span></span> <span data-ttu-id="80d75-118">Anschließend wird die Containergruppe von Azure abgerufen ihr Status ausgegeben, bis er „Wird ausgeführt“ lautet.</span><span class="sxs-lookup"><span data-stu-id="80d75-118">It then polls Azure for the container group, and outputs the container group's status until its state is "Running."</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

### <a name="create-task-based-container-group"></a><span data-ttu-id="80d75-119">Aufgabenbasierte Containergruppe erstellen</span><span class="sxs-lookup"><span data-stu-id="80d75-119">Create task-based container group</span></span>

<span data-ttu-id="80d75-120">In diesem Beispiel wird eine Containergruppe mit einem einzelnen aufgabenbasierten Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="80d75-120">This example creates a container group with a single task-based container.</span></span> <span data-ttu-id="80d75-121">Der Container wird mit der [Neustartrichtlinie](/azure/container-instances/container-instances-restart-policy) „Nie“ und einer [benutzerdefinierten Befehlszeile](/azure/container-instances/container-instances-restart-policy#command-line-override) konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="80d75-121">The container is configured with a [restart policy](/azure/container-instances/container-instances-restart-policy) of "Never" and a [custom command line](/azure/container-instances/container-instances-restart-policy#command-line-override).</span></span>

<span data-ttu-id="80d75-122">Wenn Sie einen einzelnen Befehl mit mehreren Befehlszeilenargumenten ausführen möchten, z.B. `echo FOO BAR`, müssen Sie sie als ein Zeichenfolgenarray für die `WithStartingCommandLines`-Methode angeben.</span><span class="sxs-lookup"><span data-stu-id="80d75-122">If you want to run a single command with several command-line arguments, for example `echo FOO BAR`, you must supply them as a string array to the `WithStartingCommandLines` method.</span></span> <span data-ttu-id="80d75-123">Beispiel: </span><span class="sxs-lookup"><span data-stu-id="80d75-123">For example:</span></span>

`WithStartingCommandLines("echo", "FOO", "BAR")`

<span data-ttu-id="80d75-124">Wenn Sie jedoch mehrere Befehle mit (potenziell) mehreren Argumente ausführen möchten, müssen Sie eine Shell ausführen und die verketteten Befehle als Argument übergeben.</span><span class="sxs-lookup"><span data-stu-id="80d75-124">If, however, you want to run multiple commands with (potentially) multiple arguments, you must execute a shell and pass the chained commands as an argument.</span></span> <span data-ttu-id="80d75-125">Hiermit wird beispielsweise ein `echo`- sowie ein `tail`-Befehl ausgeführt:</span><span class="sxs-lookup"><span data-stu-id="80d75-125">For example, this executes both an `echo` and a `tail` command:</span></span>

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

### <a name="list-container-groups"></a><span data-ttu-id="80d75-126">Containergruppen auflisten</span><span class="sxs-lookup"><span data-stu-id="80d75-126">List container groups</span></span>

<span data-ttu-id="80d75-127">In diesem Beispiel sind die Containergruppen in einer Ressourcengruppe aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="80d75-127">This example lists the container groups in a resource group.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

### <a name="get-an-existing-container-group"></a><span data-ttu-id="80d75-128">Vorhandene Containergruppe abrufen</span><span class="sxs-lookup"><span data-stu-id="80d75-128">Get an existing container group</span></span>

<span data-ttu-id="80d75-129">In diesem Beispiel wird eine bestimmte Containergruppe abgerufen, die sich in einer Ressourcengruppe befindet. Dann werden einige ihrer Eigenschaften und deren Werte ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="80d75-129">This example gets a specific container group residing in a resource group and then prints a few of its properties and their values.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

### <a name="delete-a-container-group"></a><span data-ttu-id="80d75-130">Containergruppe löschen</span><span class="sxs-lookup"><span data-stu-id="80d75-130">Delete a container group</span></span>

<span data-ttu-id="80d75-131">In diesem Beispiel wird eine Containergruppe aus einer Ressourcengruppe gelöscht.</span><span class="sxs-lookup"><span data-stu-id="80d75-131">This example deletes a container group from a resource group.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->
[!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]

## <a name="api-reference"></a><span data-ttu-id="80d75-132">API-Referenz</span><span class="sxs-lookup"><span data-stu-id="80d75-132">API reference</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="80d75-133">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="80d75-133">Explore the management APIs</span></span>](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a><span data-ttu-id="80d75-134">Beispiele</span><span class="sxs-lookup"><span data-stu-id="80d75-134">Samples</span></span>

* <span data-ttu-id="80d75-135">Der Quellcode für die vorhergehenden Beispiele ist auf GitHub zu finden:</span><span class="sxs-lookup"><span data-stu-id="80d75-135">The source code for the preceding examples can be found on GitHub:</span></span>

  <span data-ttu-id="80d75-136">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span><span class="sxs-lookup"><span data-stu-id="80d75-136">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span></span>

* <span data-ttu-id="80d75-137">Weitere Azure Container Instances-Codebeispiele:</span><span class="sxs-lookup"><span data-stu-id="80d75-137">More Azure Container Instances code samples:</span></span>

  <span data-ttu-id="80d75-138">[Azure-Codebeispiele][samples]</span><span class="sxs-lookup"><span data-stu-id="80d75-138">[Azure Code Samples][samples]</span></span>

<span data-ttu-id="80d75-139">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="80d75-139">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
