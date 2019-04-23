---
title: Azure HDInsight SDK für .NET
description: Referenz zum Azure HDInsight SDK für .NET
ms.date: 04/10/2019
ms.topic: reference
ms.service: hdinsight
ms.openlocfilehash: 2282a302b269a52c71ed88c26e021344cdca4382
ms.sourcegitcommit: 4328168172ac1b1a448e16988f75199262bc5c2d
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/17/2019
ms.locfileid: "59700258"
---
# <a name="azure-hdinsight-sdk-for-net"></a><span data-ttu-id="fe2c3-103">Azure HDInsight SDK für .NET</span><span class="sxs-lookup"><span data-stu-id="fe2c3-103">Azure HDInsight SDK for .NET</span></span>

<span data-ttu-id="fe2c3-104">Azure HDInsight bietet Verwaltungs- und Auftrags-SDKs für .NET mit Klassen zum Verwalten Ihres HDInsight-Clusters sowie zum Übermitteln und Überwachen von Hadoop-Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-104">Azure HDInsight offers management and job SDKs for .NET that provide classes for managing your HDInsight cluster and submitting and monitoring Hadoop jobs.</span></span>

## <a name="management"></a><span data-ttu-id="fe2c3-105">Verwaltung</span><span class="sxs-lookup"><span data-stu-id="fe2c3-105">Management</span></span>

<span data-ttu-id="fe2c3-106">Das HDInsight-Verwaltungs-SDK für .NET bietet Klassen und Methoden, mit denen Sie Ihre HDInsight-Cluster verwalten können.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-106">The HDInsight management SDK for .NET provides classes and methods that allow you to manage your HDInsight clusters.</span></span> <span data-ttu-id="fe2c3-107">Es enthält Vorgänge zum Erstellen, Löschen, Aktualisieren, Auflisten, Ändern der Größe, Ausführen von Skriptaktionen, Überwachen, Abrufen der Eigenschaften von HDInsight-Clustern und mehr.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-107">It includes operations to create, delete, update, list, resize, execute script actions, monitor, get properties of HDInsight clusters, and more.</span></span>

## <a name="prerequisites"></a><span data-ttu-id="fe2c3-108">Voraussetzungen</span><span class="sxs-lookup"><span data-stu-id="fe2c3-108">Prerequisites</span></span>

* <span data-ttu-id="fe2c3-109">Ein Azure-Konto.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-109">An Azure account.</span></span> <span data-ttu-id="fe2c3-110">Falls Sie noch kein Konto haben, können Sie eine [kostenlose Testversion](https://azure.microsoft.com/free/) verwenden.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-110">If you don't have one, [get a free trial](https://azure.microsoft.com/free/).</span></span>
* [<span data-ttu-id="fe2c3-111">Visual Studio</span><span class="sxs-lookup"><span data-stu-id="fe2c3-111">Visual Studio</span></span>](https://visualstudio.microsoft.com/downloads/)

## <a name="sdk-installation"></a><span data-ttu-id="fe2c3-112">SDK-Installation</span><span class="sxs-lookup"><span data-stu-id="fe2c3-112">SDK Installation</span></span>

<span data-ttu-id="fe2c3-113">Öffnen Sie über Ihr Visual Studio-Projekt die Paket-Manager-Konsole, indem Sie auf **Extras** > **NuGet-Paket-Manager** und dann auf **Paket-Manager-Konsole** klicken.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-113">From your Visual Studio project, open the Package Manager Console by clicking **Tools**, **NuGet Package Manager**, and then click **Package Manager Console**.</span></span>

<span data-ttu-id="fe2c3-114">Führen Sie in der Paket-Manager-Konsole die folgenden Befehle aus:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-114">In the Package Manager Console, execute the following commands:</span></span>

```
  Install-Package Microsoft.Azure.Management.HDInsight
  Install-Package Microsoft.Azure.Management.Fluent
  Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

## <a name="authentication"></a><span data-ttu-id="fe2c3-115">Authentication</span><span class="sxs-lookup"><span data-stu-id="fe2c3-115">Authentication</span></span>

<span data-ttu-id="fe2c3-116">Das SDK muss zunächst für Ihr Azure-Abonnement authentifiziert werden.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-116">The SDK first needs to be authenticated with your Azure subscription.</span></span>  <span data-ttu-id="fe2c3-117">Erstellen Sie anhand des Beispiels unten einen Dienstprinzipal, und verwenden Sie ihn für die Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-117">Follow the example below to create a service principal and use it to authenticate.</span></span> <span data-ttu-id="fe2c3-118">Nachdem dies erfolgt ist, verfügen Sie über eine Instanz von `HDInsightManagementClient` mit vielen Methoden (in den Abschnitten unten beschrieben), die zum Durchführen von Verwaltungsvorgängen verwendet werden können.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-118">After this is done, you will have an instance of an `HDInsightManagementClient`, which contains many methods (outlined in below sections) that can be used to perform management operations.</span></span>

> [!NOTE]
> <span data-ttu-id="fe2c3-119">Neben dem Beispiel unten gibt es noch andere Möglichkeiten der Authentifizierung, die für Ihre Anforderungen unter Umständen besser geeignet sind.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-119">There are other ways to authenticate besides the below example that could potentially be better suited for your needs.</span></span> <span data-ttu-id="fe2c3-120">Hier werden alle Methoden beschrieben: [Authentifizieren bei den Azure-Bibliotheken für .NET](https://docs.microsoft.com/en-us/dotnet/azure/dotnet-sdk-azure-authenticate?view=azure-dotnet)</span><span class="sxs-lookup"><span data-stu-id="fe2c3-120">All methods are outlined here: [Authenticate with the Azure Libraries for .NET](https://docs.microsoft.com/en-us/dotnet/azure/dotnet-sdk-azure-authenticate?view=azure-dotnet)</span></span>

### <a name="authentication-example-using-a-service-principal"></a><span data-ttu-id="fe2c3-121">Beispiel für die Authentifizierung mit einem Dienstprinzipal</span><span class="sxs-lookup"><span data-stu-id="fe2c3-121">Authentication Example Using a Service Principal</span></span>

<span data-ttu-id="fe2c3-122">Melden Sie sich zuerst bei [Azure Cloud Shell](https://shell.azure.com/bash) an.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-122">First, login to [Azure Cloud Shell](https://shell.azure.com/bash).</span></span> <span data-ttu-id="fe2c3-123">Vergewissern Sie sich, dass Sie derzeit das Abonnement verwenden, in dem der Dienstprinzipal erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-123">Verify you are currently using the subscription in which you want the service principal created.</span></span> 

```azurecli-interactive
az account show
```

<span data-ttu-id="fe2c3-124">Die Informationen zu Ihrem Abonnement werden im JSON-Format angezeigt.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-124">Your subscription information is displayed as JSON.</span></span>

```json
{
  "environmentName": "AzureCloud",
  "id": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "isDefault": true,
  "name": "XXXXXXX",
  "state": "Enabled",
  "tenantId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "user": {
    "cloudShellID": true,
    "name": "XXX@XXX.XXX",
    "type": "user"
  }
}
```

<span data-ttu-id="fe2c3-125">Wenn Sie nicht am richtigen Abonnement angemeldet sind, können Sie das richtige auswählen, indem Sie Folgendes ausführen:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-125">If you're not logged into the correct subscription, select the correct one by running:</span></span> 
```azurecli-interactive
az account set -s <name or ID of subscription>
```

> [!IMPORTANT]
> <span data-ttu-id="fe2c3-126">Falls Sie den HDInsight-Ressourcenanbieter nicht bereits mit einer anderen Methode registriert haben (z.B. durch das Erstellen eines HDInsight-Clusters über das Azure-Portal), müssen Sie dies vor dem Authentifizieren durchführen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-126">If you have not already registered the HDInsight Resource Provider by another method (such as by creating an HDInsight Cluster through the Azure Portal), you need to do this once before you can authenticate.</span></span> <span data-ttu-id="fe2c3-127">Dies ist über [Azure Cloud Shell](https://shell.azure.com/bash) möglich, indem Sie den folgenden Befehl ausführen:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-127">This can be done from the [Azure Cloud Shell](https://shell.azure.com/bash) by running the following command:</span></span>
>```azurecli-interactive
>az provider register --namespace Microsoft.HDInsight
>```

<span data-ttu-id="fe2c3-128">Wählen Sie als Nächstes einen Namen für Ihren Dienstprinzipal aus, und erstellen Sie ihn mit dem folgenden Befehl:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-128">Next, choose a name for your service principal and create it with the following command:</span></span>

```azurecli-interactive
az ad sp create-for-rbac --name <Service Principal Name> --sdk-auth
```

<span data-ttu-id="fe2c3-129">Die Dienstprinzipalinformationen werden im JSON-Format angezeigt.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-129">The service principal information is displayed as JSON.</span></span>

```json
{
  "clientId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "clientSecret": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "subscriptionId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "tenantId": "XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX",
  "activeDirectoryEndpointUrl": "https://login.microsoftonline.com",
  "resourceManagerEndpointUrl": "https://management.azure.com/",
  "activeDirectoryGraphResourceId": "https://graph.windows.net/",
  "sqlManagementEndpointUrl": "https://management.core.windows.net:8443/",
  "galleryEndpointUrl": "https://gallery.azure.com/",
  "managementEndpointUrl": "https://management.core.windows.net/"
}
```
<span data-ttu-id="fe2c3-130">Kopieren Sie den unten angegebenen Codeausschnitt, und geben Sie für `TENANT_ID`, `CLIENT_ID`, `CLIENT_SECRET` und `SUBSCRIPTION_ID` die Zeichenfolgen aus dem JSON-Code ein, der nach dem Ausführen des Befehls zurückgegeben wurde, um den Dienstprinzipal zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-130">Copy the below snippet and fill in `TENANT_ID`, `CLIENT_ID`, `CLIENT_SECRET`, and `SUBSCRIPTION_ID` with the strings from the JSON that was returned after running the command to create the service principal.</span></span>

```csharp
using Microsoft.Azure.Management.HDInsight;
using Microsoft.Azure.Management.HDInsight.Models;
using Microsoft.Azure.Management.ResourceManager.Fluent;

namespace HDI_SDK_Test
{
    class Program
    {
        static void Main(string[] args)
        {
            // Tenant ID for your Azure Subscription
            var TENANT_ID = "";
            // Your Service Principal App Client ID
            var CLIENT_ID = "";
            // Your Service Principal Client Secret
            var CLIENT_SECRET = "";
            // Azure Subscription ID
            var SUBSCRIPTION_ID = "";

            var credentials = SdkContext.AzureCredentialsFactory
                .FromServicePrincipal(
                CLIENT_ID,
                CLIENT_SECRET,
                TENANT_ID,
                AzureEnvironment.AzureGlobalCloud);

            var client = new HDInsightManagementClient(credentials);
            client.SubscriptionId = SUBSCRIPTION_ID;
        }
    }
}
```

## <a name="cluster-management"></a><span data-ttu-id="fe2c3-131">Clusterverwaltung</span><span class="sxs-lookup"><span data-stu-id="fe2c3-131">Cluster Management</span></span>

> [!NOTE]
> <span data-ttu-id="fe2c3-132">In diesem Abschnitt wird davon ausgegangen, dass Sie bereits eine `HDInsightManagementClient`-Instanz authentifiziert und in einer Variablen mit dem Namen `client` gespeichert haben.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-132">This section assumes you have already authenticated and constructed an `HDInsightManagementClient` instance and store it in a variable called `client`.</span></span> <span data-ttu-id="fe2c3-133">Eine Anleitung zum Authentifizieren und Abrufen eines `HDInsightManagementClient`-Elements finden Sie oben im Abschnitt „Authentifizierung“.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-133">Instructions for authenticating and obtaining an `HDInsightManagementClient` can be found in the Authentication section above.</span></span>

### <a name="create-a-cluster"></a><span data-ttu-id="fe2c3-134">Erstellen eines Clusters</span><span class="sxs-lookup"><span data-stu-id="fe2c3-134">Create a Cluster</span></span>

<span data-ttu-id="fe2c3-135">Sie können einen neuen Cluster erstellen, indem Sie `client.Clusters.Create()` aufrufen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-135">A new cluster can be created by calling `client.Clusters.Create()`.</span></span>

#### <a name="samples"></a><span data-ttu-id="fe2c3-136">Beispiele</span><span class="sxs-lookup"><span data-stu-id="fe2c3-136">Samples</span></span>

<span data-ttu-id="fe2c3-137">Codebeispiele zum Erstellen verschiedener allgemeiner HDInsight-Clustertypen stehen zur Verfügung: [HDInsight-.NET-Beispiele](https://github.com/Azure-Samples/hdinsight-dotnet-sdk-samples).</span><span class="sxs-lookup"><span data-stu-id="fe2c3-137">Code samples for creating several common types of HDInsight clusters are available: [HDInsight .NET Samples](https://github.com/Azure-Samples/hdinsight-dotnet-sdk-samples).</span></span>

#### <a name="example"></a><span data-ttu-id="fe2c3-138">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-138">Example</span></span>

<span data-ttu-id="fe2c3-139">In diesem Beispiel wird gezeigt, wie Sie einen Spark-Cluster mit zwei Hauptknoten und einem Workerknoten erstellen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-139">This example demonstrates how to create a Spark cluster with 2 head nodes and 1 worker node.</span></span>

> [!NOTE]
> <span data-ttu-id="fe2c3-140">Sie müssen zuerst wie unten beschrieben eine Ressourcengruppe und ein Speicherkonto erstellen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-140">You first need to create a Resource Group and Storage Account, as explained below.</span></span> <span data-ttu-id="fe2c3-141">Wenn Sie diese Komponenten bereits erstellt haben, können Sie diese Schritte überspringen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-141">If you have already created these, you can skip these steps.</span></span>

##### <a name="creating-a-resource-group"></a><span data-ttu-id="fe2c3-142">Erstellen einer Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="fe2c3-142">Creating a Resource Group</span></span>

<span data-ttu-id="fe2c3-143">Sie können eine Ressourcengruppe erstellen, indem Sie mit [Azure Cloud Shell](https://shell.azure.com/bash) Folgendes ausführen:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-143">You can create a resource group using the [Azure Cloud Shell](https://shell.azure.com/bash) by running</span></span>
```azurecli-interactive
az group create -l <Region Name (i.e. eastus)> --n <Resource Group Name>
```
##### <a name="creating-a-storage-account"></a><span data-ttu-id="fe2c3-144">Erstellen eines Speicherkontos</span><span class="sxs-lookup"><span data-stu-id="fe2c3-144">Creating a Storage Account</span></span>

<span data-ttu-id="fe2c3-145">Sie können ein Speicherkonto erstellen, indem Sie mit [Azure Cloud Shell](https://shell.azure.com/bash) Folgendes ausführen:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-145">You can create a storage account using the [Azure Cloud Shell](https://shell.azure.com/bash) by running:</span></span>
```azurecli-interactive
az storage account create -n <Storage Account Name> -g <Existing Resource Group Name> -l <Region Name (i.e. eastus)> --sku <SKU i.e. Standard_LRS>
```
<span data-ttu-id="fe2c3-146">Führen Sie jetzt den folgenden Befehl aus, um den Schlüssel für Ihr Speicherkonto abzurufen (Sie benötigen ihn, um einen Cluster zu erstellen):</span><span class="sxs-lookup"><span data-stu-id="fe2c3-146">Now run the following command to get the key for your storage account (you will need this to create a cluster):</span></span>
```azurecli-interactive
az storage account keys list -n <Storage Account Name>
```
---
<span data-ttu-id="fe2c3-147">Mit dem unten angegebenen .NET-Codeausschnitt wird ein Spark-Cluster mit zwei Hauptknoten und einem Workerknoten erstellt.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-147">The below .NET snippet creates a Spark cluster with 2 head nodes and 1 worker node.</span></span> <span data-ttu-id="fe2c3-148">Geben Sie gemäß den Anweisungen in den Kommentaren Werte in die leeren Variablen ein, und ändern Sie ggf. auch andere Parameter, um diese an Ihre Anforderungen anzupassen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-148">Fill in the blank variables as explained in the comments and feel free to change other parameters to suit your specific needs.</span></span>

```csharp
// The name for the cluster you are creating
var clusterName = "";
// The name of your existing Resource Group
var resourceGroupName = "";
// Choose a username
var username = "";
// Choose a password
var password = "";
// Replace <> with the name of your storage account
var storageAccount = "<>.blob.core.windows.net";
// Storage account key you obtained above
var storageAccountKey = "";
// Choose a region
var location = "";
var container = "default";

var parameters = new ClusterCreateParametersExtended
{
    Location = location,
    Tags = new Dictionary<string, string>(),
    Properties = new ClusterCreateProperties
    {
        ClusterVersion = "3.6",
        OsType = OSType.Linux,
        ClusterDefinition = new ClusterDefinition
        {
            Kind = "Hadoop",            
            Configurations = new Dictionary<string, Dictionary<string, string>>()
            {                
                { "gateway", new Dictionary<string, string>
                    {
                        { "restAuthCredential.isEnabled", "true" },
                        { "restAuthCredential.username", username},
                        { "restAuthCredential.password", password}
                    }
                }
            }
        },
        Tier = Tier.Standard,
        ComputeProfile = new ComputeProfile
        {
            Roles = new List<Role>{
                new Role
                {
                    Name = "headnode",
                    TargetInstanceCount = 2,
                    HardwareProfile = new HardwareProfile
                    {
                        VmSize = "Large"
                    },
                    OsProfile = new OsProfile
                    {
                        LinuxOperatingSystemProfile = new LinuxOperatingSystemProfile
                        {
                            Username = username,
                            Password = password
                        }
                    }
                },
                new Role
                {
                    Name = "workernode",
                    TargetInstanceCount = 1,
                    HardwareProfile = new HardwareProfile
                    {
                        VmSize = "Large"
                    },
                    OsProfile = new OsProfile
                    {
                        LinuxOperatingSystemProfile = new LinuxOperatingSystemProfile
                        {
                            Username = username,
                            Password = password
                        }
                    }
                },
            }
        },
        StorageProfile = new StorageProfile
        {
            Storageaccounts = new[]
            {
                new StorageAccount
                {
                    Name = storageAccount,
                    Key = storageAccountKey,
                    Container = container,
                    IsDefault = true
                }
            }
        }
    }
};
client.Clusters.Create(
    resourceGroupName,
    clusterName,
    parameters
);
```

### <a name="get-cluster-details"></a><span data-ttu-id="fe2c3-149">Abrufen von Clusterdetails</span><span class="sxs-lookup"><span data-stu-id="fe2c3-149">Get Cluster Details</span></span>

<span data-ttu-id="fe2c3-150">Rufen Sie die Eigenschaften für einen Cluster wie folgt ab:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-150">To get properties for a given cluster:</span></span>

```csharp
client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a><span data-ttu-id="fe2c3-151">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-151">Example</span></span>

<span data-ttu-id="fe2c3-152">Sie können `get` verwenden, um zu bestätigen, dass die Erstellung des Clusters erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-152">You can use `get` to confirm that you have successfully created your cluster.</span></span>

```csharp
var myCluster = client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
Debug.WriteLine(myCluster.Name); //Prints the name of the cluster
Debug.WriteLine(myCluster.Id) //Prints the resource Id of the cluster
```

<span data-ttu-id="fe2c3-153">Die Ausgabe sollte wie folgt aussehen:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-153">The output should look like:</span></span>

```
<Cluster Name>
/subscriptions/XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX/resourceGroups/<Resource Group Name>/providers/Microsoft.HDInsight/clusters/<Cluster Name>
```
> [!NOTE]
> <span data-ttu-id="fe2c3-154">Der Rückgabewert von `get`, der in der Variablen `myCluster` gespeichert ist, hat den Typ `Microsoft.Azure.Management.HDInsight.ModelsCluster`.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-154">The return value of `get`, stored in variable `myCluster`, is of type `Microsoft.Azure.Management.HDInsight.ModelsCluster`.</span></span> <span data-ttu-id="fe2c3-155">Eine vollständige Liste mit den Eigenschaften dieses Objekts finden Sie [hier](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.management.hdinsight.models.cluster?view=azure-dotnet-preview).</span><span class="sxs-lookup"><span data-stu-id="fe2c3-155">A full list of this object's properties can be found [here](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.management.hdinsight.models.cluster?view=azure-dotnet-preview).</span></span>


### <a name="list-clusters"></a><span data-ttu-id="fe2c3-156">Auflisten von Clustern</span><span class="sxs-lookup"><span data-stu-id="fe2c3-156">List Clusters</span></span>

#### <a name="list-clusters-under-the-subscription"></a><span data-ttu-id="fe2c3-157">Auflisten von Clustern unter dem Abonnement</span><span class="sxs-lookup"><span data-stu-id="fe2c3-157">List Clusters Under The Subscription</span></span>

```csharp
client.Clusters.List();
```
#### <a name="list-clusters-by-resource-group"></a><span data-ttu-id="fe2c3-158">Auflisten von Clustern nach Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="fe2c3-158">List Clusters By Resource Group</span></span>

```csharp
client.Clusters.ListByResourceGroup("<Resource Group Name>");
```
> [!NOTE]
> <span data-ttu-id="fe2c3-159">Sowohl für `List()` als auch für `ListByResourceGroup()` wird ein `IPage<Cluster>`-Objekt zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-159">Both `List()` and `ListByResourceGroup()` return an `IPage<Cluster>` object.</span></span> <span data-ttu-id="fe2c3-160">Sie können `client.Clusters.ListNext("Next Page Link")` aufrufen, um die nächste Seite zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-160">To get the next page, you can call `client.Clusters.ListNext("Next Page Link")`.</span></span> <span data-ttu-id="fe2c3-161">Dies kann wiederholt werden, bis `NextPageLink` den Wert `null` hat (wie im Beispiel unten zu sehen).</span><span class="sxs-lookup"><span data-stu-id="fe2c3-161">This can be repeated until `NextPageLink` is `null`, as shown in the example below.</span></span>

#### <a name="example"></a><span data-ttu-id="fe2c3-162">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-162">Example</span></span>
<span data-ttu-id="fe2c3-163">Im folgenden Beispiel werden die Eigenschaften aller Cluster für das aktuelle Abonnement ausgegeben:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-163">The following example prints the properties of all clusters for the current subscription:</span></span>

```csharp
var clustersPaged = client.Clusters.List();
while (true)
{
  foreach (var cluster in clustersPaged)
  {
    Debug.WriteLine(cluster.Name);
  
}  if (clustersPaged.NextPageLink == null)
  {
    break;
  }
  clustersPaged = client.Clusters.ListNext(clustersPaged.NextPageLink);
}
```

### <a name="delete-a-cluster"></a><span data-ttu-id="fe2c3-164">Löschen eines Clusters</span><span class="sxs-lookup"><span data-stu-id="fe2c3-164">Delete a Cluster</span></span>

<span data-ttu-id="fe2c3-165">Löschen Sie einen Cluster wie folgt:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-165">To delete a cluster:</span></span>

```csharp
client.Clusters.Delete("<Resource Group Name>", "<Cluster Name>");
```

### <a name="update-cluster-tags"></a><span data-ttu-id="fe2c3-166">Aktualisieren von Clustermarkierungen</span><span class="sxs-lookup"><span data-stu-id="fe2c3-166">Update Cluster Tags</span></span>

<span data-ttu-id="fe2c3-167">Sie können die Markierungen eines Clusters wie folgt aktualisieren:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-167">You can update the tags of a given cluster like so:</span></span>

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(<Dictionary of Tags>));
```
#### <a name="example"></a><span data-ttu-id="fe2c3-168">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-168">Example</span></span>

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(new Dictionary<string, string> { { "tag1Name", "tag1Value" }, { "tag2Name", "tag2Value" } }));
```

### <a name="resize-cluster"></a><span data-ttu-id="fe2c3-169">Ändern der Clustergröße</span><span class="sxs-lookup"><span data-stu-id="fe2c3-169">Resize Cluster</span></span>

<span data-ttu-id="fe2c3-170">Sie können die Anzahl von Workerknoten für einen Cluster ändern, indem Sie wie folgt eine neue Größe angeben:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-170">You can resize a given cluster's number of worker nodes by specifying a new size like so:</span></span>

```csharp
client.Clusters.Resize("<Resource Group Name>", "<Cluster Name>", <Num of Worker Nodes (int)>)
```

## <a name="cluster-monitoring"></a><span data-ttu-id="fe2c3-171">Clusterüberwachung</span><span class="sxs-lookup"><span data-stu-id="fe2c3-171">Cluster Monitoring</span></span>

<span data-ttu-id="fe2c3-172">Das HDInsight Management SDK kann auch verwendet werden, um die Überwachung Ihrer Cluster per Operations Management Suite (OMS) zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-172">The HDInsight Management SDK can also be used to manage monitoring on your clusters via the Operations Management Suite (OMS).</span></span>

### <a name="enable-oms-monitoring"></a><span data-ttu-id="fe2c3-173">Aktivieren der OMS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="fe2c3-173">Enable OMS Monitoring</span></span>

> [!NOTE]
> <span data-ttu-id="fe2c3-174">Sie müssen über einen vorhandenen Log Analytics-Arbeitsbereich verfügen, um die OMS-Überwachung zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-174">To enable OMS Monitoring, you must have an existing Log Analytics workspace.</span></span> <span data-ttu-id="fe2c3-175">Wenn Sie noch keinen erstellt haben, erfahren Sie an dieser Stelle, wie Sie dazu vorgehen: [Erstellen eines Log Analytics-Arbeitsbereichs im Azure-Portal](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace)</span><span class="sxs-lookup"><span data-stu-id="fe2c3-175">If you have not already created one, you can learn how to do that here: [Create a Log Analytics workspace in the Azure portal](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace).</span></span>

<span data-ttu-id="fe2c3-176">Aktivieren Sie die OMS-Überwachung in Ihrem Cluster wie folgt:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-176">To enable OMS Monitoring on your cluster:</span></span>

```csharp
client.Extension.EnableMonitoring("<Resource Group Name", "Cluster Name", new ClusterMonitoringRequest(workspaceId: "<Workspace Id>"));
```

### <a name="view-status-of-oms-monitoring"></a><span data-ttu-id="fe2c3-177">Anzeigen des Status der OMS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="fe2c3-177">View Status Of OMS Monitoring</span></span>

<span data-ttu-id="fe2c3-178">Rufen Sie den Status von OMS in Ihrem Cluster wie folgt ab:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-178">To get the status of OMS on your cluster:</span></span>

```csharp
client.Extension.GetMonitoringStatus("<Resource Group Name", "Cluster Name");
```

### <a name="disable-oms-monitoring"></a><span data-ttu-id="fe2c3-179">Deaktivieren der OMS-Überwachung</span><span class="sxs-lookup"><span data-stu-id="fe2c3-179">Disable OMS Monitoring</span></span>

<span data-ttu-id="fe2c3-180">Deaktivieren Sie OMS in Ihrem Cluster wie folgt:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-180">To disable OMS on your cluster:</span></span>

```csharp
client.Extension.DisableMonitoring("<Resource Group Name>", "<Cluster Name>");
```

## <a name="script-actions"></a><span data-ttu-id="fe2c3-181">Skriptaktionen</span><span class="sxs-lookup"><span data-stu-id="fe2c3-181">Script Actions</span></span>

<span data-ttu-id="fe2c3-182">HDInsight verfügt über eine Konfigurationsmethode mit der Bezeichnung „Skriptaktionen“, mit der benutzerdefinierte Skripts zum Anpassen des Clusters aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-182">HDInsight provides a configuration method called script actions that invokes custom scripts to customize the cluster.</span></span>
> [!NOTE]
> <span data-ttu-id="fe2c3-183">Weitere Informationen zum Verwenden von Skriptaktionen finden Sie hier: [Anpassen Linux-basierter HDInsight-Cluster mithilfe von Skriptaktionen](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux)</span><span class="sxs-lookup"><span data-stu-id="fe2c3-183">More information on how to use script actions can be found here: [Customize Linux-based HDInsight clusters using script actions](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux)</span></span>

### <a name="execute-script-actions"></a><span data-ttu-id="fe2c3-184">Ausführen von Skriptaktionen</span><span class="sxs-lookup"><span data-stu-id="fe2c3-184">Execute Script Actions</span></span>

<span data-ttu-id="fe2c3-185">Sie können Skriptaktionen für einen Cluster wie folgt ausführen:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-185">You can execute script actions on a given cluster like so:</span></span>

```csharp
var scriptAction1 = new RuntimeScriptAction("<Script Name>", "<URL To Script>", <List<string> of roles>); //valid roles are "headnode", "workernode", "zookeepernode", and "edgenode"

client.Clusters.ExecuteScriptActions("<Resource Group Name>", "<Cluster Name>", new List<RuntimeScriptAction> { scriptAction1 }, <persistOnSuccess (bool)>); //add more RuntimeScriptActions to the list to execute multiple scripts
```

### <a name="delete-script-action"></a><span data-ttu-id="fe2c3-186">Löschen der Skriptaktion</span><span class="sxs-lookup"><span data-stu-id="fe2c3-186">Delete Script Action</span></span>

<span data-ttu-id="fe2c3-187">Löschen Sie eine angegebene permanente Skriptaktion für einen Cluster wie folgt:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-187">To delete a specified persisted script action on a given cluster:</span></span>

```csharp
client.ScriptActions.Delete("<Resource Group Name>", "<Cluster Name>", "<Script Name>");
```

### <a name="list-persisted-script-actions"></a><span data-ttu-id="fe2c3-188">Auflisten von permanenten Skriptaktionen</span><span class="sxs-lookup"><span data-stu-id="fe2c3-188">List Persisted Script Actions</span></span>

> [!NOTE]
> <span data-ttu-id="fe2c3-189">Für `ListPersistedScripts()` und `List()` wird ein `IPage<RuntimeScriptActionDetail>`-Objekt zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-189">`ListPersistedScripts()` and `List()` return an `IPage<RuntimeScriptActionDetail>` object.</span></span> <span data-ttu-id="fe2c3-190">Sie können `client.ScriptActions.ListPersistedScriptsNext("Next Page Link")` oder `client.ScriptExecutionHistory.ListNext("Next Page Link")` aufrufen, um die nächste Seite zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-190">To get the next page, you can call `client.ScriptActions.ListPersistedScriptsNext("Next Page Link")` or `client.ScriptExecutionHistory.ListNext("Next Page Link")`.</span></span> <span data-ttu-id="fe2c3-191">Dies kann wiederholt werden, bis `NextPageLink` den Wert `null` hat (wie in den Beispielen unten zu sehen).</span><span class="sxs-lookup"><span data-stu-id="fe2c3-191">This can be repeated until `NextPageLink` is `null`, as shown in the examples below.</span></span>

<span data-ttu-id="fe2c3-192">Listen Sie alle permanenten Skriptaktionen für den angegebenen Cluster wie folgt auf:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-192">To list all persisted script actions for the specified cluster:</span></span>
```csharp
client.ScriptActions.ListPersistedScripts("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a><span data-ttu-id="fe2c3-193">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-193">Example</span></span>

```csharp
var scriptsPaged = client.ScriptActions.ListPersistedScripts("<Resource Group Name>", "<Cluster Name>");
while (true)
{
    foreach (var script in scriptsPaged)
    {
        Debug.WriteLine(script.Name); //There are other properties of RuntimeScriptActionDetail besides Name, such as Status, Operation, StartTime, EndTime, etc. See reference documentation.
    }
    if (scriptsPaged.NextPageLink == null)
    {
        break;
    }
    scriptsPaged = client.ScriptActions.ListPersistedScriptsNext(scriptsPaged.NextPageLink);
}
```

### <a name="list-all-scripts-execution-history"></a><span data-ttu-id="fe2c3-194">Auflisten des Ausführungsverlaufs aller Skripts</span><span class="sxs-lookup"><span data-stu-id="fe2c3-194">List All Scripts' Execution History</span></span>

<span data-ttu-id="fe2c3-195">Listen Sie den Ausführungsverlauf aller Skripts für den angegebenen Cluster wie folgt auf:</span><span class="sxs-lookup"><span data-stu-id="fe2c3-195">To list all scripts' execution history for the specified cluster:</span></span>

```csharp
client.script_execution_history.list("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a><span data-ttu-id="fe2c3-196">Beispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-196">Example</span></span>

<span data-ttu-id="fe2c3-197">In diesem Beispiel werden alle Details zu allen erfolgten Skriptausführungen ausgegeben.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-197">This example prints all the details for all past script executions.</span></span>

```csharp
var scriptExecutionsPaged = client.ScriptExecutionHistory.List("<Resource Group Name>", "<Cluster Name>");
while (true)
{
    foreach (var script in scriptExecutionsPaged)
    {
        Debug.WriteLine(script.Name); //There are other properties of RuntimeScriptActionDetail besides Name, such as Status, Operation, StartTime, EndTime, etc. See reference documentation.

    }
    if (scriptExecutionsPaged.NextPageLink == null)
    {
        break;
    }
    scriptExecutionsPaged = client.ScriptExecutionHistory.ListNext(scriptExecutionsPaged.NextPageLink);
}
```

## <a name="jobs"></a><span data-ttu-id="fe2c3-198">Aufträge</span><span class="sxs-lookup"><span data-stu-id="fe2c3-198">Jobs</span></span>

<span data-ttu-id="fe2c3-199">Verwenden Sie das Azure HDInsight-Auftrags-SDK zum Erstellen, Verwalten und Überwachen von Aufträgen in einem Hadoop-Cluster.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-199">Use the Azure HDInsight job SDK for .NET to create, manage, and monitor jobs on a Hadoop cluster.</span></span>

### <a name="sdk-installation"></a><span data-ttu-id="fe2c3-200">SDK-Installation</span><span class="sxs-lookup"><span data-stu-id="fe2c3-200">SDK Installation</span></span>

<span data-ttu-id="fe2c3-201">Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].</span><span class="sxs-lookup"><span data-stu-id="fe2c3-201">Install the [NuGet package](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) directly from the Visual Studio [Package Manager console][PackageManager] or with the [.NET Core CLI][DotNetCLI].</span></span>

#### <a name="visual-studio-package-manager"></a><span data-ttu-id="fe2c3-202">Visual Studio-Paket-Manager</span><span class="sxs-lookup"><span data-stu-id="fe2c3-202">Visual Studio Package Manager</span></span>

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

### <a name="code-example"></a><span data-ttu-id="fe2c3-203">Codebeispiel</span><span class="sxs-lookup"><span data-stu-id="fe2c3-203">Code Example</span></span>

<span data-ttu-id="fe2c3-204">In diesem Beispiel wird ein Hive-Auftrag in einem Hadoop-Cluster ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="fe2c3-204">This example runs a Hive job in a Hadoop cluster.</span></span>

```csharp
HDInsightJobManagementClient managementClient = new HDInsightJobManagementClient(clusterUri, credentials);

Dictionary<string, string> defines = new Dictionary<string, string> {
    { "hive.execution.engine", "tez" },
    { "hive.exec.reducers.max", "1" }
};
List<string> arguments = new List<string> { { "argA" }, { "argB" } };
HiveJobSubmissionParameters parameters = new HiveJobSubmissionParameters
{
    Query = "SHOW TABLES",
    Defines = defines,
    Arguments = arguments
};

JobSubmissionResponse jobResponse = managementClient.JobManagement.SubmitHiveJob(parameters);
```

### <a name="samples"></a><span data-ttu-id="fe2c3-205">Beispiele</span><span class="sxs-lookup"><span data-stu-id="fe2c3-205">Samples</span></span>

- [<span data-ttu-id="fe2c3-206">Ausführen von Hive-Abfragen per HDInsight .NET-SDK</span><span class="sxs-lookup"><span data-stu-id="fe2c3-206">Run Hive jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [<span data-ttu-id="fe2c3-207">Ausführen von Pig-Aufträgen mithilfe des .NET-SDK für Hadoop in HDInsight</span><span class="sxs-lookup"><span data-stu-id="fe2c3-207">Run Pig jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [<span data-ttu-id="fe2c3-208">Übermitteln von Hadoop-Aufträgen in HDInsight</span><span class="sxs-lookup"><span data-stu-id="fe2c3-208">More jobs</span></span>](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)
