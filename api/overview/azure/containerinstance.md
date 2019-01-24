---
title: Azure Container Instances-Bibliotheken für .NET
description: Referenz für Azure Container Instances-Bibliotheken für .NET
ms.date: 06/11/2018
ms.topic: reference
ms.service: container-instances
ms.openlocfilehash: 552746b316f1ba80adce5f55bb22412749fd93bc
ms.sourcegitcommit: 4f7bc5c5cd333e41446a3ebe5639a211d8ac9b90
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/24/2019
ms.locfileid: "54841277"
---
# <a name="azure-container-instances-libraries-for-net"></a><span data-ttu-id="2d4ae-103">Azure Container Instances-Bibliotheken für .NET</span><span class="sxs-lookup"><span data-stu-id="2d4ae-103">Azure Container Instances libraries for .NET</span></span>

<span data-ttu-id="2d4ae-104">Verwenden Sie die Azure Container Instances-Bibliotheken für .NET zum Erstellen und Verwalten von Azure-Containerinstanzen.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-104">Use the Microsoft Azure Container Instances libraries for .NET to create and manage Azure container instances.</span></span> <span data-ttu-id="2d4ae-105">In der [Übersicht über Azure Container Instances](/azure/container-instances/container-instances-overview) erfahren Sie mehr.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-105">Learn more by reading the [Azure Container Instances overview](/azure/container-instances/container-instances-overview).</span></span>

## <a name="management-library"></a><span data-ttu-id="2d4ae-106">Verwaltungsbibliothek</span><span class="sxs-lookup"><span data-stu-id="2d4ae-106">Management library</span></span>

<span data-ttu-id="2d4ae-107">Verwenden Sie die Verwaltungsbibliothek zum Erstellen und Verwalten von Azure-Containerinstanzen in Azure.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-107">Use the management library to create and manage Azure container instances in Azure.</span></span>

<span data-ttu-id="2d4ae-108">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="2d4ae-108">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.ContainerInstance.Fluent) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

### <a name="visual-studio-package-manager"></a><span data-ttu-id="2d4ae-109">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="2d4ae-109">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.ContainerInstance.Fluent
```

```bash
dotnet add package Microsoft.Azure.Management.ContainerInstance.Fluent
```

## <a name="example-source"></a><span data-ttu-id="2d4ae-110">Beispielquelle</span><span class="sxs-lookup"><span data-stu-id="2d4ae-110">Example source</span></span>

<span data-ttu-id="2d4ae-111">Wenn Sie die folgenden Codebeispiele im Kontext sehen möchten, finden Sie sie im folgenden GitHub-Repository:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-111">If you'd like to see the following code examples in context, you can find them in the following GitHub repository:</span></span>

[<span data-ttu-id="2d4ae-112">Azure-Samples/aci-docs-sample-dotnet</span><span class="sxs-lookup"><span data-stu-id="2d4ae-112">Azure-Samples/aci-docs-sample-dotnet</span></span>](https://github.com/Azure-Samples/aci-docs-sample-dotnet)

## <a name="authentication"></a><span data-ttu-id="2d4ae-113">Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="2d4ae-113">Authentication</span></span>

<span data-ttu-id="2d4ae-114">Eine der einfachsten Möglichkeiten zum Authentifizieren von SDK-Clients ist die Verwendung der [dateibasierten Authentifizierung][sdk-auth].</span><span class="sxs-lookup"><span data-stu-id="2d4ae-114">One of the easiest ways to authenticate SDK clients is with [file-based authentication][sdk-auth].</span></span> <span data-ttu-id="2d4ae-115">Bei der dateibasierten Authentifizierung wird beim Instanziieren des Clientobjekts [IAzure][iazure] eine Anmeldeinformationendatei analysiert. Diese Anmeldeinformationen werden anschließend für die Authentifizierung über Azure verwendet.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-115">File-based authentication parses a credentials file when instantiating the [IAzure][iazure] client object, which then uses those credentials when authenticating with Azure.</span></span> <span data-ttu-id="2d4ae-116">So verwenden Sie die dateibasierte Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="2d4ae-116">To use file-based authentication:</span></span>

1. <span data-ttu-id="2d4ae-117">Erstellen Sie mit der [Azure CLI](/cli/azure) oder mit [Cloud Shell](https://shell.azure.com/) eine Datei mit Anmeldeinformationen:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-117">Create a credentials file with the [Azure CLI](/cli/azure) or [Cloud Shell](https://shell.azure.com/):</span></span>

   `az ad sp create-for-rbac --sdk-auth > my.azureauth`

   <span data-ttu-id="2d4ae-118">Wenn Sie [Cloud Shell](https://shell.azure.com/) zum Erstellen der Datei mit Anmeldeinformationen verwenden, kopieren Sie ihren Inhalt in eine lokale Datei, auf die die .NET-Anwendung zugreifen kann.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-118">If you use the [Cloud Shell](https://shell.azure.com/) to generate the credentials file, copy its contents into a local file that your .NET application can access.</span></span>

2. <span data-ttu-id="2d4ae-119">Legen Sie die Umgebungsvariable `AZURE_AUTH_LOCATION` auf den vollständigen Pfad der erstellten Datei mit Anmeldeinformationen fest.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-119">Set the `AZURE_AUTH_LOCATION` environment variable to the full path of the generated credentials file.</span></span> <span data-ttu-id="2d4ae-120">Beispiel (in der Bash-Shell):</span><span class="sxs-lookup"><span data-stu-id="2d4ae-120">For example (in the Bash shell):</span></span>

   ```bash
   export AZURE_AUTH_LOCATION=/home/yourusername/my.azureauth
   ```

<span data-ttu-id="2d4ae-121">Nachdem Sie die Anmeldeinformationendatei erstellt und die Umgebungsvariable `AZURE_AUTH_LOCATION` aufgefüllt haben, initialisieren Sie das Clientobjekt [IAzure][iazure] mithilfe der Methode [Azure.Authenticate][iazure-authenticate].</span><span class="sxs-lookup"><span data-stu-id="2d4ae-121">Once you've created the credentials file and populated the `AZURE_AUTH_LOCATION` environment variable, use the [Azure.Authenticate][iazure-authenticate] method to initialize the [IAzure][iazure] client object.</span></span> <span data-ttu-id="2d4ae-122">Das Beispielprojekt ruft zuerst den Wert `AZURE_AUTH_LOCATION` ab und ruft dann eine Methode auf, die ein initialisiertes `IAzure`-Clientobjekt zurückgibt:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-122">The example project first obtains the `AZURE_AUTH_LOCATION` value, then calls a method that returns an initialized `IAzure` client object:</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#L29-L35 "Get environment variable")]

<span data-ttu-id="2d4ae-123">Diese Methode aus der Beispielanwendung gibt die initialisierte [IAzure][iazure]-Instanz zurück, die dann als erster Parameter an alle anderen Methoden im Beispiel übergeben wird:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-123">This method from the sample application returns the initialized [IAzure][iazure] instance, which is then passed as the first parameter to all other methods in the sample:</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[authenticate](~/aci-docs-sample-dotnet/Program.cs#azure_auth "Authenticate IAzure client object")]

<span data-ttu-id="2d4ae-124">Weitere Informationen zu den verfügbaren Authentifizierungsmethoden in den .NET-Verwaltungsbibliotheken für Azure finden Sie unter [Authentication in Azure Management Libraries for .NET][sdk-auth] (Authentifizieren in den Azure-Verwaltungsbibliotheken für .NET).</span><span class="sxs-lookup"><span data-stu-id="2d4ae-124">For more details about the available authentication methods in the .NET management libraries for Azure, see [Authentication in Azure Management Libraries for .NET][sdk-auth].</span></span>

## <a name="create-container-group---single-container"></a><span data-ttu-id="2d4ae-125">Erstellen einer Containergruppe – einzelner Container</span><span class="sxs-lookup"><span data-stu-id="2d4ae-125">Create container group - single container</span></span>

<span data-ttu-id="2d4ae-126">In diesem Beispiel wird eine Containergruppe mit einem einzelnen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-126">This example creates a container group with a single container.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group](~/aci-docs-sample-dotnet/Program.cs#create_container_group "Create single-container group")]

## <a name="create-container-group---multiple-containers"></a><span data-ttu-id="2d4ae-127">Containergruppe erstellen – mehrere Container</span><span class="sxs-lookup"><span data-stu-id="2d4ae-127">Create container group - multiple containers</span></span>

<span data-ttu-id="2d4ae-128">In diesem Beispiel wird eine Containergruppe mit zwei Containern erstellt: einem Anwendungscontainer und einem Sidecar-Container.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-128">This example creates a container group with two containers: an application container and a sidecar container.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group_multi](~/aci-docs-sample-dotnet/Program.cs#create_container_group_multi "Create multi-container group")]

## <a name="asynchronous-container-create-with-polling"></a><span data-ttu-id="2d4ae-129">Asynchrone Containererstellung mit Abruf</span><span class="sxs-lookup"><span data-stu-id="2d4ae-129">Asynchronous container create with polling</span></span>

<span data-ttu-id="2d4ae-130">In diesem Beispiel wird mithilfe der asynchronen Erstellungsmethode eine Containergruppe mit einem einzelnen Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-130">This example creates a container group with a single container using the async create method.</span></span> <span data-ttu-id="2d4ae-131">Anschließend wird die Containergruppe von Azure abgerufen ihr Status ausgegeben, bis er „Wird ausgeführt“ lautet.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-131">It then polls Azure for the container group, and outputs the container group's status until its state is "Running."</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group_polling](~/aci-docs-sample-dotnet/Program.cs#create_container_group_polling "Create single-container group with async and polling")]

## <a name="create-task-based-container-group"></a><span data-ttu-id="2d4ae-132">Aufgabenbasierte Containergruppe erstellen</span><span class="sxs-lookup"><span data-stu-id="2d4ae-132">Create task-based container group</span></span>

<span data-ttu-id="2d4ae-133">In diesem Beispiel wird eine Containergruppe mit einem einzelnen aufgabenbasierten Container erstellt.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-133">This example creates a container group with a single task-based container.</span></span> <span data-ttu-id="2d4ae-134">Der Container wird mit der [Neustartrichtlinie](/azure/container-instances/container-instances-restart-policy) „Nie“ und einer [benutzerdefinierten Befehlszeile](/azure/container-instances/container-instances-restart-policy#command-line-override) konfiguriert.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-134">The container is configured with a [restart policy](/azure/container-instances/container-instances-restart-policy) of "Never" and a [custom command line](/azure/container-instances/container-instances-restart-policy#command-line-override).</span></span>

<span data-ttu-id="2d4ae-135">Wenn Sie einen einzelnen Befehl mit mehreren Befehlszeilenargumenten ausführen möchten, z.B. `echo FOO BAR`, müssen Sie sie als ein Zeichenfolgenarray für die `WithStartingCommandLines`-Methode angeben.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-135">If you want to run a single command with several command-line arguments, for example `echo FOO BAR`, you must supply them as a string array to the `WithStartingCommandLines` method.</span></span> <span data-ttu-id="2d4ae-136">Beispiel: </span><span class="sxs-lookup"><span data-stu-id="2d4ae-136">For example:</span></span>

`WithStartingCommandLines("echo", "FOO", "BAR")`

<span data-ttu-id="2d4ae-137">Wenn Sie jedoch mehrere Befehle mit (potenziell) mehreren Argumente ausführen möchten, müssen Sie eine Shell ausführen und die verketteten Befehle als Argument übergeben.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-137">If, however, you want to run multiple commands with (potentially) multiple arguments, you must execute a shell and pass the chained commands as an argument.</span></span> <span data-ttu-id="2d4ae-138">Hiermit wird beispielsweise ein `echo`- sowie ein `tail`-Befehl ausgeführt:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-138">For example, this executes both an `echo` and a `tail` command:</span></span>

`WithStartingCommandLines("/bin/sh", "-c", "echo FOO BAR && tail -f /dev/null")`

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[create_container_group_task](~/aci-docs-sample-dotnet/Program.cs#create_container_group_task "Run a task-based container")]

## <a name="list-container-groups"></a><span data-ttu-id="2d4ae-139">Containergruppen auflisten</span><span class="sxs-lookup"><span data-stu-id="2d4ae-139">List container groups</span></span>

<span data-ttu-id="2d4ae-140">In diesem Beispiel sind die Containergruppen in einer Ressourcengruppe aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-140">This example lists the container groups in a resource group.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[list_container_groups](~/aci-docs-sample-dotnet/Program.cs#list_container_groups "List container groups")]

## <a name="get-an-existing-container-group"></a><span data-ttu-id="2d4ae-141">Vorhandene Containergruppe abrufen</span><span class="sxs-lookup"><span data-stu-id="2d4ae-141">Get an existing container group</span></span>

<span data-ttu-id="2d4ae-142">In diesem Beispiel wird eine bestimmte Containergruppe abgerufen, die sich in einer Ressourcengruppe befindet. Dann werden einige ihrer Eigenschaften und deren Werte ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-142">This example gets a specific container group residing in a resource group and then prints a few of its properties and their values.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[get_container_group](~/aci-docs-sample-dotnet/Program.cs#get_container_group "Get container group")]

## <a name="delete-a-container-group"></a><span data-ttu-id="2d4ae-143">Containergruppe löschen</span><span class="sxs-lookup"><span data-stu-id="2d4ae-143">Delete a container group</span></span>

<span data-ttu-id="2d4ae-144">In diesem Beispiel wird eine Containergruppe aus einer Ressourcengruppe gelöscht.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-144">This example deletes a container group from a resource group.</span></span>

<!-- SOURCE REPO: https://github.com/Azure-Samples/aci-docs-sample-dotnet -->  
[!code-csharp[delete_container_group](~/aci-docs-sample-dotnet/Program.cs#delete_container_group "Delete container group")]

## <a name="api-reference"></a><span data-ttu-id="2d4ae-145">API-Referenz</span><span class="sxs-lookup"><span data-stu-id="2d4ae-145">API reference</span></span>

> [!div class="nextstepaction"]
> [<span data-ttu-id="2d4ae-146">Informationen zu den Verwaltungs-APIs</span><span class="sxs-lookup"><span data-stu-id="2d4ae-146">Explore the management APIs</span></span>](/dotnet/api/overview/azure/containerinstances/management)

## <a name="samples"></a><span data-ttu-id="2d4ae-147">Beispiele</span><span class="sxs-lookup"><span data-stu-id="2d4ae-147">Samples</span></span>

* <span data-ttu-id="2d4ae-148">Der Quellcode für die vorhergehenden Beispiele ist auf GitHub zu finden:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-148">The source code for the preceding examples can be found on GitHub:</span></span>

  <span data-ttu-id="2d4ae-149">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span><span class="sxs-lookup"><span data-stu-id="2d4ae-149">[Azure-Samples/aci-docs-sample-dotnet][aci-docs-sample-dotnet]</span></span>

* <span data-ttu-id="2d4ae-150">Weitere Azure Container Instances-Codebeispiele:</span><span class="sxs-lookup"><span data-stu-id="2d4ae-150">More Azure Container Instances code samples:</span></span>

  <span data-ttu-id="2d4ae-151">[Azure-Codebeispiele][samples]</span><span class="sxs-lookup"><span data-stu-id="2d4ae-151">[Azure Code Samples][samples]</span></span>

<span data-ttu-id="2d4ae-152">Untersuchen Sie weiteren [.NET-Beispielcode](https://azure.microsoft.com/resources/samples/?platform=dotnet), den Sie in Ihren Apps verwenden können.</span><span class="sxs-lookup"><span data-stu-id="2d4ae-152">Explore more [sample .NET code](https://azure.microsoft.com/resources/samples/?platform=dotnet) you can use in your apps.</span></span>

<!-- LINKS - External -->
[aci-docs-sample-dotnet]: https://github.com/Azure-Samples/aci-docs-sample-dotnet
[samples]: https://azure.microsoft.com/resources/samples/?sort=0&term=ACI
[sdk-auth]: https://github.com/Azure/azure-libraries-for-net/blob/master/AUTH.md

<!-- LINKS - Internal -->
[DotNetCLI]: /dotnet/core/tools/dotnet-add-package
[PackageManager]: /nuget/tools/package-manager-console
[iazure]: /dotnet/api/microsoft.azure.management.fluent.azure
[iazure-authenticate]: /dotnet/api/microsoft.azure.management.fluent.azure.authenticate
