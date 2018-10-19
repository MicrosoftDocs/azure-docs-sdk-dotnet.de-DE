---
title: Azure HDInsight .NET SDK
description: Referenz zum Azure HDInsight .NET SDK
ms.date: 9/19/2018
ms.topic: reference
ms.service: hdinsight
ms.openlocfilehash: 35e2c8c07fb2b86b2d0ae9be4f855e369c1aa86d
ms.sourcegitcommit: 1cf4550df8ed3236d838f561f6177d14d89b5e44
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 10/16/2018
ms.locfileid: "49348202"
---
# <a name="azure-hdinsight-net-sdk"></a>Azure HDInsight .NET SDK

## <a name="azure-hdinsight-libraries-for-net-2x"></a>Azure HD Insight-Bibliotheken für .NET 2.X

## <a name="overview"></a>Übersicht

Das HDInsight-Dienst-.NET-SDK bietet Klassen, die sich auf Erstellung, Konfiguration, Übermittlung und Überwachung von Hadoop-Aufträgen beziehen, die von einem Azure HDInsight-Dienst verwaltet werden. Darüber hinaus bietet sie Klassen zum Verwalten von Azure-Abonnements mithilfe des HDInsight-Diensts, und zum Konfigurieren der Cluster, Speicherkonten und sonstigen Ressourcen, die den HDInsight-Clustern zugeordnet sind, die von einem Azure-Abonnement verwaltet werden.

## <a name="management-libraries"></a>Verwaltungsbibliotheken

### <a name="jobs"></a>Aufträge

Verwenden Sie das Azure HDInsight-Client-SDK zum Erstellen, verwalten und Überwachen von Aufträgen in einem Hadoop-Cluster. 

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight.Job) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.HDInsight.Job
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight.Job
```

#### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird ein Hive-Auftrag in einem Hadoop-Cluster ausgeführt.

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

### <a name="hdinsight"></a>HDInsight

Verwenden Sie das Azure HDInsight-Verwaltungs-SDK zum Erstellen, Verwalten, Starten, Beenden und Skalieren von Hadoop-Clustern.

Installieren Sie das [NuGet-Paket](https://www.nuget.org/packages/Microsoft.Azure.Management.HDInsight) direkt über die [Paket-Manager-Konsole][PackageManager] in Visual Studio oder mit der [.NET Core CLI][DotNetCLI].

#### <a name="visual-studio-package-manager"></a>Visual Studio-Paket-Manager

```powershell
Install-Package Microsoft.Azure.Management.HDInsight
```

```bash
dotnet add package Microsoft.Azure.Management.HDInsight
```

#### <a name="code-example"></a>Codebeispiel

In diesem Beispiel wird ein HDInsight-Linux-Hadoop-Cluster mit zwei Knoten mit einem vorhandenen Azure Blob Storage erstellt.

```csharp
HDInsightManagementClient managementClient = new HDInsightManagementClient(authToken);
// Set parameters for the new cluster
ClusterCreateParameters parameters = new ClusterCreateParameters
{
    ClusterSizeInNodes = 2,
    UserName = "admin",
    Password = "<Enter HTTP User Password>",
    ClusterType = "Hadoop",
    OSType = OSType.Linux,
    Version = "3.5",
    // Use an Azure storage account as the default storage
    DefaultStorageInfo = new AzureStorageInfo("<StorageAccount>", "<StorageKey>", "<BlobContainerName>"),
    Location = "EAST US 2",
    SshUserName = "sshuser",
    SshPassword = "<Enter SSH User Password>",
};

// Create the cluster
managementClient.Clusters.Create("<ExistingResourceGroupName>", "<NewClusterName>", parameters);
```

> [!div class="nextstepaction"]
> [Informationen zu den Verwaltungs-APIs](/dotnet/api/overview/azure/hdinsights/management)


## <a name="samples"></a>Beispiele

- [Erstellen von Linux-basierten Clustern in HDInsight mit dem .NET-SDK](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-create-linux-clusters-dotnet-sdk)
- [Verwalten von Hadoop-Clustern in HDInsight mit .NET-SDK](https://docs.microsoft.com/azure/hdinsight/hdinsight-administer-use-dotnet-sdk)
- [Ausführen von Hive-Abfragen per HDInsight .NET-SDK](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-hive-dotnet-sdk)
- [Ausführen von Pig-Aufträgen mithilfe des .NET-SDK für Hadoop in HDInsight](https://docs.microsoft.com/azure/hdinsight/hdinsight-hadoop-use-pig-dotnet-sdk)
- [Übermitteln von Hadoop-Aufträgen in HDInsight](https://docs.microsoft.com/azure/hdinsight/hdinsight-submit-hadoop-jobs-programmatically)

Zeigen Sie die [vollständige Liste](https://azure.microsoft.com/resources/samples/?platform=dotnet&service=hdinsight) von Beispielen für Azure SQL-Datenbank an.

[PackageManager]: https://docs.microsoft.com/nuget/tools/package-manager-console
[DotNetCLI]: https://docs.microsoft.com/dotnet/core/tools/dotnet-add-package

## <a name="hdinsight-net-management-sdk-3x-preview"></a>HDInsight .NET Management SDK 3.X – Vorschauversion

## <a name="overview"></a>Übersicht

Mit dem HDInsight .NET SDK werden Klassen und Methoden bereitgestellt, mit denen Sie Ihre HDInsight-Cluster verwalten können. Es enthält Vorgänge zum Erstellen, Löschen, Aktualisieren, Auflisten, Ändern der Größe, Ausführen von Skriptaktionen, Überwachen, Abrufen der Eigenschaften von HDInsight-Clustern und mehr.

## <a name="prerequisites"></a>Voraussetzungen

* Ein Azure-Konto. Falls Sie noch kein Konto haben, können Sie eine [kostenlose Testversion](https://azure.microsoft.com/free/) verwenden.
* [Visual Studio](https://visualstudio.microsoft.com/downloads/)

## <a name="sdk-installation"></a>SDK-Installation

Öffnen Sie über Ihr Visual Studio-Projekt die Paket-Manager-Konsole, indem Sie auf **Extras** > **NuGet-Paket-Manager** und dann auf **Paket-Manager-Konsole** klicken.

Führen Sie in der Paket-Manager-Konsole die folgenden Befehle aus:

```
  Install-Package Microsoft.Azure.Management.HDInsight -Version 3.1.0-preview
  Install-Package Microsoft.Azure.Management.Fluent
  Install-Package Microsoft.Azure.Management.ResourceManager.Fluent
```

## <a name="authentication"></a>Authentifizierung

Das SDK muss zunächst für Ihr Azure-Abonnement authentifiziert werden.  Erstellen Sie anhand des Beispiels unten einen Dienstprinzipal, und verwenden Sie ihn für die Authentifizierung. Nachdem dies erfolgt ist, verfügen Sie über eine Instanz von `HDInsightManagementClient` mit vielen Methoden (in den Abschnitten unten beschrieben), die zum Durchführen von Verwaltungsvorgängen verwendet werden können.

> [!NOTE]
> Neben dem Beispiel unten gibt es noch andere Möglichkeiten der Authentifizierung, die für Ihre Anforderungen unter Umständen besser geeignet sind. Alle Methoden sind hier beschrieben: [Authentifizieren bei den Azure-Bibliotheken für .NET](https://docs.microsoft.com/en-us/dotnet/azure/dotnet-sdk-azure-authenticate?view=azure-dotnet).

### <a name="authentication-example-using-a-service-principal"></a>Beispiel für die Authentifizierung mit einem Dienstprinzipal

Melden Sie sich zuerst bei [Azure Cloud Shell](https://shell.azure.com/bash) an. Vergewissern Sie sich, dass Sie derzeit das Abonnement verwenden, in dem der Dienstprinzipal erstellt werden soll. 

```azurecli-interactive
az account show
```

Die Informationen zu Ihrem Abonnement werden im JSON-Format angezeigt.

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

Wenn Sie nicht am richtigen Abonnement angemeldet sind, können Sie das richtige auswählen, indem Sie Folgendes ausführen: 
```azurecli-interactive
az account set -s <name or ID of subscription>
```

> [!IMPORTANT]
> Falls Sie den HDInsight-Ressourcenanbieter nicht bereits mit einer anderen Methode registriert haben (z.B. durch das Erstellen eines HDInsight-Clusters über das Azure-Portal), müssen Sie dies vor dem Authentifizieren durchführen. Dies ist über [Azure Cloud Shell](https://shell.azure.com/bash) möglich, indem Sie den folgenden Befehl ausführen:
>```azurecli-interactive
>az provider register --namespace Microsoft.HDInsight
>```

Wählen Sie als Nächstes einen Namen für Ihren Dienstprinzipal aus, und erstellen Sie ihn mit dem folgenden Befehl:

```azurecli-interactive
az ad sp create-for-rbac --name <Service Principal Name> --sdk-auth
```

Die Dienstprinzipalinformationen werden im JSON-Format angezeigt.

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
Kopieren Sie den unten angegebenen Codeausschnitt, und geben Sie für `TENANT_ID`, `CLIENT_ID`, `CLIENT_SECRET` und `SUBSCRIPTION_ID` die Zeichenfolgen aus dem JSON-Code ein, der nach dem Ausführen des Befehls zurückgegeben wurde, um den Dienstprinzipal zu erstellen.

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


## <a name="cluster-management"></a>Clusterverwaltung

> [!NOTE]
> In diesem Abschnitt wird davon ausgegangen, dass Sie bereits eine `HDInsightManagementClient`-Instanz authentifiziert und in einer Variablen mit dem Namen `client` gespeichert haben. Eine Anleitung zum Authentifizieren und Abrufen eines `HDInsightManagementClient`-Elements finden Sie oben im Abschnitt „Authentifizierung“.

### <a name="create-a-cluster"></a>Erstellen eines Clusters

Sie können einen neuen Cluster erstellen, indem Sie `client.Clusters.Create()` aufrufen. 

#### <a name="example"></a>Beispiel

In diesem Beispiel wird gezeigt, wie Sie einen Spark-Cluster mit zwei Hauptknoten und einem Workerknoten erstellen.

> [!NOTE]
> Sie müssen zuerst wie unten beschrieben eine Ressourcengruppe und ein Speicherkonto erstellen. Wenn Sie diese Komponenten bereits erstellt haben, können Sie diese Schritte überspringen.

##### <a name="creating-a-resource-group"></a>Erstellen einer Ressourcengruppe

Sie können eine Ressourcengruppe erstellen, indem Sie mit [Azure Cloud Shell](https://shell.azure.com/bash) Folgendes ausführen:
```azurecli-interactive
az group create -l <Region Name (i.e. eastus)> --n <Resource Group Name>
```
##### <a name="creating-a-storage-account"></a>Erstellen eines Speicherkontos

Sie können ein Speicherkonto erstellen, indem Sie mit [Azure Cloud Shell](https://shell.azure.com/bash) Folgendes ausführen:
```azurecli-interactive
az storage account create -n <Storage Account Name> -g <Existing Resource Group Name> -l <Region Name (i.e. eastus)> --sku <SKU i.e. Standard_LRS>
```
Führen Sie jetzt den folgenden Befehl aus, um den Schlüssel für Ihr Speicherkonto abzurufen (Sie benötigen ihn, um einen Cluster zu erstellen):
```azurecli-interactive
az storage account keys list -n <Storage Account Name>
```
---
Mit dem unten angegebenen .NET-Codeausschnitt wird ein Spark-Cluster mit zwei Hauptknoten und einem Workerknoten erstellt. Geben Sie gemäß den Anweisungen in den Kommentaren Werte in die leeren Variablen ein, und ändern Sie ggf. auch andere Parameter, um diese an Ihre Anforderungen anzupassen.

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

### <a name="get-cluster-details"></a>Abrufen von Clusterdetails

Rufen Sie die Eigenschaften für einen Cluster wie folgt ab:

```csharp
client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a>Beispiel

Sie können `get` verwenden, um zu bestätigen, dass die Erstellung des Clusters erfolgreich war.

```csharp
var myCluster = client.Clusters.Get("<Resource Group Name>", "<Cluster Name>");
Debug.WriteLine(myCluster.Name); //Prints the name of the cluster
Debug.WriteLine(myCluster.Id) //Prints the resource Id of the cluster
```

Die Ausgabe sollte wie folgt aussehen:

```
<Cluster Name>
/subscriptions/XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX/resourceGroups/<Resource Group Name>/providers/Microsoft.HDInsight/clusters/<Cluster Name>
```
> [!NOTE]
> Der Rückgabewert von `get`, der in der Variablen `myCluster` gespeichert ist, hat den Typ `Microsoft.Azure.Management.HDInsight.ModelsCluster`. Eine vollständige Liste mit den Eigenschaften dieses Objekts finden Sie [hier](https://docs.microsoft.com/en-us/dotnet/api/microsoft.azure.management.hdinsight.models.cluster?view=azure-dotnet-preview).


### <a name="list-clusters"></a>Auflisten von Clustern

#### <a name="list-clusters-under-the-subscription"></a>Auflisten von Clustern unter dem Abonnement

```csharp
client.Clusters.List();
```
#### <a name="list-clusters-by-resource-group"></a>Auflisten von Clustern nach Ressourcengruppe

```csharp
client.Clusters.ListByResourceGroup("<Resource Group Name>");
```
> [!NOTE]
> Sowohl für `List()` als auch für `ListByResourceGroup()` wird ein `IPage<Cluster>`-Objekt zurückgegeben. Sie können `client.Clusters.ListNext("Next Page Link")` aufrufen, um die nächste Seite zu erhalten. Dies kann wiederholt werden, bis `NextPageLink` den Wert `null` hat (wie im Beispiel unten zu sehen).

#### <a name="example"></a>Beispiel
Im folgenden Beispiel werden die Eigenschaften aller Cluster für das aktuelle Abonnement ausgegeben:

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

### <a name="delete-a-cluster"></a>Löschen eines Clusters

Löschen Sie einen Cluster wie folgt:

```csharp
client.Clusters.Delete("<Resource Group Name>", "<Cluster Name>");
```

### <a name="update-cluster-tags"></a>Aktualisieren von Clustermarkierungen

Sie können die Markierungen eines Clusters wie folgt aktualisieren:

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(<Dictionary of Tags>));
```
#### <a name="example"></a>Beispiel

```csharp
client.Clusters.Update("<Resource Group Name>", "<Cluster Name>", new ClusterPatchParameters(new Dictionary<string, string> { { "tag1Name", "tag1Value" }, { "tag2Name", "tag2Value" } }));
```

### <a name="resize-cluster"></a>Ändern der Clustergröße

Sie können die Anzahl von Workerknoten für einen Cluster ändern, indem Sie wie folgt eine neue Größe angeben:

```csharp
client.Clusters.Resize("<Resource Group Name>", "<Cluster Name>", <Num of Worker Nodes (int)>)
```

## <a name="cluster-monitoring"></a>Clusterüberwachung

Das HDInsight Management SDK kann auch verwendet werden, um die Überwachung Ihrer Cluster per Operations Management Suite (OMS) zu verwalten.

### <a name="enable-oms-monitoring"></a>Aktivieren der OMS-Überwachung

> [!NOTE]
> Sie müssen über einen vorhandenen Log Analytics-Arbeitsbereich verfügen, um die OMS-Überwachung zu ermöglichen. Falls Sie diesen noch nicht erstellt haben, helfen Ihnen die Informationen im folgenden Artikel weiter: [Erstellen eines Log Analytics-Arbeitsbereichs im Azure-Portal](https://docs.microsoft.com/en-us/azure/log-analytics/log-analytics-quick-create-workspace).

Aktivieren Sie die OMS-Überwachung in Ihrem Cluster wie folgt:

```csharp
client.Extension.EnableMonitoring("<Resource Group Name", "Cluster Name", new ClusterMonitoringRequest(workspaceId: "<Workspace Id>"));
```

### <a name="view-status-of-oms-monitoring"></a>Anzeigen des Status der OMS-Überwachung

Rufen Sie den Status von OMS in Ihrem Cluster wie folgt ab:

```csharp
client.Extension.GetMonitoringStatus("<Resource Group Name", "Cluster Name");
```

### <a name="disable-oms-monitoring"></a>Deaktivieren der OMS-Überwachung

Deaktivieren Sie OMS in Ihrem Cluster wie folgt:

```csharp
client.Extension.DisableMonitoring("<Resource Group Name>", "<Cluster Name>");
```

## <a name="script-actions"></a>Skriptaktionen

HDInsight verfügt über eine Konfigurationsmethode mit der Bezeichnung „Skriptaktionen“, mit der benutzerdefinierte Skripts zum Anpassen des Clusters aufgerufen werden.
> [!NOTE]
> Weitere Informationen zur Verwendung von Skriptaktionen finden Sie unter [Anpassen Linux-basierter HDInsight-Cluster mithilfe von Skriptaktionen](https://docs.microsoft.com/en-us/azure/hdinsight/hdinsight-hadoop-customize-cluster-linux).

### <a name="execute-script-actions"></a>Ausführen von Skriptaktionen

Sie können Skriptaktionen für einen Cluster wie folgt ausführen:

```csharp
var scriptAction1 = new RuntimeScriptAction("<Script Name>", "<URL To Script>", <List<string> of roles>); //valid roles are "headnode", "workernode", "zookeepernode", and "edgenode"

client.Clusters.ExecuteScriptActions("<Resource Group Name>", "<Cluster Name>", new List<RuntimeScriptAction> { scriptAction1 }, <persistOnSuccess (bool)>); //add more RuntimeScriptActions to the list to execute multiple scripts
```

### <a name="delete-script-action"></a>Löschen der Skriptaktion

Löschen Sie eine angegebene permanente Skriptaktion für einen Cluster wie folgt:

```csharp
client.ScriptActions.Delete("<Resource Group Name>", "<Cluster Name>", "<Script Name>");
```

### <a name="list-persisted-script-actions"></a>Auflisten von permanenten Skriptaktionen

> [!NOTE]
> Für `ListPersistedScripts()` und `List()` wird ein `IPage<RuntimeScriptActionDetail>`-Objekt zurückgegeben. Sie können `client.ScriptActions.ListPersistedScriptsNext("Next Page Link")` oder `client.ScriptExecutionHistory.ListNext("Next Page Link")` aufrufen, um die nächste Seite zu erhalten. Dies kann wiederholt werden, bis `NextPageLink` den Wert `null` hat (wie in den Beispielen unten zu sehen).

Listen Sie alle permanenten Skriptaktionen für den angegebenen Cluster wie folgt auf:
```csharp
client.ScriptActions.ListPersistedScripts("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a>Beispiel

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

### <a name="list-all-scripts-execution-history"></a>Auflisten des Ausführungsverlaufs aller Skripts

Listen Sie den Ausführungsverlauf aller Skripts für den angegebenen Cluster wie folgt auf:

```csharp
client.script_execution_history.list("<Resource Group Name>", "<Cluster Name>");
```

#### <a name="example"></a>Beispiel

In diesem Beispiel werden alle Details zu allen erfolgten Skriptausführungen ausgegeben.

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
