<Type Name="FabricClient+ClusterManagementClient" FullName="System.Fabric.FabricClient+ClusterManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ClusterManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ClusterManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ClusterManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ClusterManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ClusterManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="e2eff-101">Stellt die Cluster-Verwaltungsclient für Cluster Wartungsvorgänge ausführen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-101">Represents the cluster management client for performing cluster maintenance operations.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="e2eff-102">Die <see cref="T:System.Fabric.FabricClient.ClusterManagementClient" /> stellt APIs bereit, welche Hilfe ', um den Cluster als Ganzes verwalten.</span><span class="sxs-lookup"><span data-stu-id="e2eff-102">The <see cref="T:System.Fabric.FabricClient.ClusterManagementClient" /> provides APIs which help to manage the cluster as a whole.</span></span> <span data-ttu-id="e2eff-103">Hierbei handelt es sich um in der Regel Verwaltungsbefehlen wichtigen Clusterereignisse beispielsweise beim einem Ausfall von Knoten und die Notwendigkeit eines wichtigen wiederhergestellt betreffen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-103">These are typically administrative commands which relate to major cluster events such as the loss of nodes and the need to recover services in the case of major failures.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActivateNodeAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ActivateNodeAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ActivateNodeAsync (nodeName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ActivateNodeAsync : string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ActivateNodeAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2eff-104">Der Knoten aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-104">The Node to be Activated.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-105">Aktiviert einen Service Fabric-Clusterknoten, der momentan deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-105">Activates a Service Fabric cluster node which is currently deactivated.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-106">Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-106">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-107">Sobald aktiviert, der Knoten er wieder geeigneten Ziel zum Platzieren neuer Replikate zum wird und geschlossenen Replikate auf dem Knoten werden geöffnet.</span><span class="sxs-lookup"><span data-stu-id="e2eff-107">Once activated, the node will again become a viable target for placing new replicas, and any closed replicas remaining on the node will be opened.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-108">Nach Abschluss dieser API impliziert dies, dass die Absicht, aktivieren Sie vom System registriert wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-108">When this API completes it implies that the intent to activate has been registered by the system.</span></span> <span data-ttu-id="e2eff-109">Es bedeutet nicht, dass die Aktivierung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-109">It does not mean that the activation is complete.</span></span> <span data-ttu-id="e2eff-110">Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="e2eff-110">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-111">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-111">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-112">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-112">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-113">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-113">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ActivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ActivateNodeAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ActivateNodeAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ActivateNodeAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ActivateNodeAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2eff-114">Der Knoten aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-114">The Node to be Activated.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-115">Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-115">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-116">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-116">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-117">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-117">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-118">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-118">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-119">Aktiviert einen Service Fabric-Clusterknoten, der momentan deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-119">Activates a Service Fabric cluster node which is currently deactivated.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-120">Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-120">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-121">Sobald aktiviert, der Knoten er wieder geeigneten Ziel zum Platzieren neuer Replikate zum wird und geschlossenen Replikate auf dem Knoten werden geöffnet.</span><span class="sxs-lookup"><span data-stu-id="e2eff-121">Once activated, the node will again become a viable target for placing new replicas, and any closed replicas remaining on the node will be opened.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-122">Nach Abschluss dieser API impliziert dies, dass die Absicht, aktivieren Sie vom System registriert wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-122">When this API completes it implies that the intent to activate has been registered by the system.</span></span> <span data-ttu-id="e2eff-123">Es bedeutet nicht, dass die Aktivierung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-123">It does not mean that the activation is complete.</span></span> <span data-ttu-id="e2eff-124">Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="e2eff-124">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-125">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-125">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-126">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-126">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-127">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-127">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CopyClusterPackage">
      <MemberSignature Language="C#" Value="public void CopyClusterPackage (string imageStoreConnectionString, string clusterManifestPath, string clusterManifestPathInImageStore, string codePackagePath, string codePackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void CopyClusterPackage(string imageStoreConnectionString, string clusterManifestPath, string clusterManifestPathInImageStore, string codePackagePath, string codePackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub CopyClusterPackage (imageStoreConnectionString As String, clusterManifestPath As String, clusterManifestPathInImageStore As String, codePackagePath As String, codePackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.CopyClusterPackage : string * string * string * string * string -&gt; unit" Usage="clusterManagementClient.CopyClusterPackage (imageStoreConnectionString, clusterManifestPath, clusterManifestPathInImageStore, codePackagePath, codePackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="clusterManifestPath" Type="System.String" />
        <Parameter Name="clusterManifestPathInImageStore" Type="System.String" />
        <Parameter Name="codePackagePath" Type="System.String" />
        <Parameter Name="codePackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para><span data-ttu-id="e2eff-128">Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-128">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="e2eff-129">In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-129">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="e2eff-130">In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore".</span><span class="sxs-lookup"><span data-stu-id="e2eff-130">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="e2eff-131">Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-131">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="clusterManifestPath">
          <para><span data-ttu-id="e2eff-132">Der vollständige Pfad zu dem Cluster Manifestdatei kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-132">The full path to the cluster manifest file to be copied.</span></span></para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para><span data-ttu-id="e2eff-133">Der relative Pfad sowie der Dateiname des Ziels in den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-133">The relative path along with the file name of the destination in the image store.</span></span> <span data-ttu-id="e2eff-134">Dieser Parameter ist erforderlich, wenn ClusterManifestPath angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-134">This parameter is required when clusterManifestPath is specified.</span></span> <span data-ttu-id="e2eff-135">Dieser Pfad wird relativ zum Stammverzeichnis in den imagespeicher besitzen erstellt und als Ziel verwendet wird, für die Cluster-manifest-Kopie.</span><span class="sxs-lookup"><span data-stu-id="e2eff-135">This path is created relative to the root directory in the image store and used as the destination for the cluster manifest copy.</span></span></para>
        </param>
        <param name="codePackagePath">
          <para><span data-ttu-id="e2eff-136">Der vollständige Pfad zum Service Fabric-Code-Paket kopiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-136">The full path to the Service Fabric code package to be copied.</span></span></para>
        </param>
        <param name="codePackagePathInImageStore">
          <para><span data-ttu-id="e2eff-137">Der relative Pfad sowie der Dateiname des Ziels in den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-137">The relative path along with the file name of the destination in the image store.</span></span> <span data-ttu-id="e2eff-138">Dieser Parameter ist erforderlich, wenn CodePackagePathInImageStore angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-138">This parameter is required when codePackagePathInImageStore is specified.</span></span> <span data-ttu-id="e2eff-139">Dieser Pfad ist relativ zum Stammverzeichnis in der Image Store erstellt und als Ziel verwendet wird, für die Kopie der Code-Paket.</span><span class="sxs-lookup"><span data-stu-id="e2eff-139">This path is created relative to the root directory in the image store and used as the destination for the code package copy.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-140">Kopiert die clustermanifestdatei und/oder Service Fabric-Codepaket in den imagespeicher besitzen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-140">Copies the cluster manifest file and/or Service Fabric code package to the image store.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e2eff-141">Manifest Quellpfad für Cluster und Code Quellpfad darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="e2eff-141">Both source cluster manifest path and source code path cannot be null.</span></span></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="e2eff-142">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-142">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para><span data-ttu-id="e2eff-143">Auf der Image Store ist eine erforderliche Datei nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-143">A required file was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para><span data-ttu-id="e2eff-144">Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-144">A required directory was not found on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para><span data-ttu-id="e2eff-145">Ein Pfad zu einem Image Store/Dateiverzeichnis war zu lang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-145">A path to an image store file/directory was too long.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="e2eff-146"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-146"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="e2eff-147">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="e2eff-147">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeactivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeactivateNodeAsync (string nodeName, System.Fabric.NodeDeactivationIntent deactivationIntent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeactivateNodeAsync(string nodeName, valuetype System.Fabric.NodeDeactivationIntent deactivationIntent) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeactivateNodeAsync (nodeName As String, deactivationIntent As NodeDeactivationIntent) As Task" />
      <MemberSignature Language="F#" Value="member this.DeactivateNodeAsync : string * System.Fabric.NodeDeactivationIntent -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.DeactivateNodeAsync (nodeName, deactivationIntent)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="deactivationIntent" Type="System.Fabric.NodeDeactivationIntent" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2eff-148">Der Name des Knotens zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="e2eff-148">The name of the node to deactivate.</span></span></para>
        </param>
        <param name="deactivationIntent">
          <para><span data-ttu-id="e2eff-149">Die <see cref="T:System.Fabric.NodeDeactivationIntent" /> zur Deaktivierung des Knotens.</span><span class="sxs-lookup"><span data-stu-id="e2eff-149">The <see cref="T:System.Fabric.NodeDeactivationIntent" /> for deactivating the node.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-150">Deaktiviert einen bestimmten Knoten mit dem angegebenen <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-150">Deactivates a particular node with the specified <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-151">Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-151">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-152">Nach Abschluss dieser API impliziert dies, dass die Absicht, deaktivieren Sie vom System registriert wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-152">When this API completes it implies that the intent to deactivate has been registered by the system.</span></span> <span data-ttu-id="e2eff-153">Es bedeutet nicht, dass die Deaktivierung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-153">It does not mean that the deactivation is complete.</span></span> <span data-ttu-id="e2eff-154">Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="e2eff-154">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
          <para>
                <span data-ttu-id="e2eff-155">Sobald die Deaktivierung ausgeführt wird, die Datei deaktivierungsabsicht kann werden "erhöht" aber nicht verringert (z. B. ein Knoten deaktiviert wurde, mit der <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> Absicht kann weiter mit deaktiviert <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, aber nicht umgekehrt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-155">Once the deactivation is in progress, the deactivation intent can be “increased” but not decreased (for example, a node which is was deactivated with the <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> intent can be deactivated further with <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, but not the other way around.</span></span> <span data-ttu-id="e2eff-156">Knoten können erneut aktiviert werden, über <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> jedes Mal, wenn nach der Deaktivierung werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-156">Nodes may be reactivated via <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> any time after they are deactivated.</span></span> <span data-ttu-id="e2eff-157">Wenn die Deaktivierung nicht abgeschlossen ist. wird dies die Deaktivierung dadurch abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-157">If the deactivation is not complete this will cancel the deactivation.</span></span> <span data-ttu-id="e2eff-158">Ein Knoten, der ausfällt und wieder hochgefahren während der Deaktivierung müssen immer noch reaktiviert werden, bevor Dienste auf diesem Knoten platziert werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-158">A node which goes down and comes back up while deactivated will still need to be reactivated before services will be placed on that node.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-159">Service Fabric stellt sicher, dass diese Deaktivierung einer "sicheren" Prozess ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-159">Service Fabric ensures that deactivation is a 'safe' process.</span></span> <span data-ttu-id="e2eff-160">Er führt mehrere sicherheitsüberprüfungen (finden Sie unter <see cref="T:System.Fabric.SafetyCheckKind" />), stellen Sie sicher, dass kein Verlust der Verfügbarkeit oder Daten vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="e2eff-160">It performs several safety checks (see <see cref="T:System.Fabric.SafetyCheckKind" />) to ensure that there is no loss of availability or data</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-161">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-161">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-162">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-162">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-163">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-163">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeactivateNodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeactivateNodeAsync (string nodeName, System.Fabric.NodeDeactivationIntent deactivationIntent, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeactivateNodeAsync(string nodeName, valuetype System.Fabric.NodeDeactivationIntent deactivationIntent, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.DeactivateNodeAsync(System.String,System.Fabric.NodeDeactivationIntent,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeactivateNodeAsync : string * System.Fabric.NodeDeactivationIntent * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.DeactivateNodeAsync (nodeName, deactivationIntent, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="deactivationIntent" Type="System.Fabric.NodeDeactivationIntent" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2eff-164">Der Name des Knotens zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="e2eff-164">The name of the node to deactivate.</span></span></para>
        </param>
        <param name="deactivationIntent">
          <para><span data-ttu-id="e2eff-165">Die <see cref="T:System.Fabric.NodeDeactivationIntent" /> zur Deaktivierung des Knotens.</span><span class="sxs-lookup"><span data-stu-id="e2eff-165">The <see cref="T:System.Fabric.NodeDeactivationIntent" /> for deactivating the node.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-166">Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-166">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-167">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-167">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-168">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-168">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-169">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-169">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-170">Deaktiviert einen bestimmten Knoten mit dem angegebenen <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-170">Deactivates a particular node with the specified <see cref="T:System.Fabric.NodeDeactivationIntent" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-171">Eine Aufgabe, die asynchrone Bestätigung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-171">A Task that represents the asynchronous acknowledgment of the request.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-172">Nach Abschluss dieser API impliziert dies, dass die Absicht, deaktivieren Sie vom System registriert wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-172">When this API completes it implies that the intent to deactivate has been registered by the system.</span></span> <span data-ttu-id="e2eff-173">Es bedeutet nicht, dass die Deaktivierung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-173">It does not mean that the deactivation is complete.</span></span> <span data-ttu-id="e2eff-174">Der Status des Vorgangs kann bestimmt werden, mithilfe der <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span><span class="sxs-lookup"><span data-stu-id="e2eff-174">The progress of the operation can be determined by using the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> API</span></span> </para>
          <para>
                <span data-ttu-id="e2eff-175">Sobald die Deaktivierung ausgeführt wird, die Datei deaktivierungsabsicht kann werden "erhöht" aber nicht verringert (z. B. ein Knoten deaktiviert wurde, mit der <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> Absicht kann weiter mit deaktiviert <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, aber nicht umgekehrt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-175">Once the deactivation is in progress, the deactivation intent can be “increased” but not decreased (for example, a node which is was deactivated with the <see cref="F:System.Fabric.NodeDeactivationIntent.Pause" /> intent can be deactivated further with <see cref="F:System.Fabric.NodeDeactivationIntent.Restart" />, but not the other way around.</span></span> <span data-ttu-id="e2eff-176">Knoten können erneut aktiviert werden, über <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> jedes Mal, wenn nach der Deaktivierung werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-176">Nodes may be reactivated via <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.ActivateNodeAsync(System.String)" /> any time after they are deactivated.</span></span> <span data-ttu-id="e2eff-177">Wenn die Deaktivierung nicht abgeschlossen ist. wird dies die Deaktivierung dadurch abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-177">If the deactivation is not complete this will cancel the deactivation.</span></span> <span data-ttu-id="e2eff-178">Ein Knoten, der ausfällt und wieder hochgefahren während der Deaktivierung müssen immer noch reaktiviert werden, bevor Dienste auf diesem Knoten platziert werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-178">A node which goes down and comes back up while deactivated will still need to be reactivated before services will be placed on that node.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-179">Service Fabric stellt sicher, dass diese Deaktivierung einer "sicheren" Prozess ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-179">Service Fabric ensures that deactivation is a 'safe' process.</span></span> <span data-ttu-id="e2eff-180">Er führt mehrere sicherheitsüberprüfungen (finden Sie unter <see cref="T:System.Fabric.SafetyCheckKind" />), stellen Sie sicher, dass kein Verlust der Verfügbarkeit oder Daten vorhanden ist</span><span class="sxs-lookup"><span data-stu-id="e2eff-180">It performs several safety checks (see <see cref="T:System.Fabric.SafetyCheckKind" />) to ensure that there is no loss of availability or data</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-181">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-181">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-182">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-182">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-183">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-183">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-184">Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-184">Gets the Service Fabric cluster configuration file as a string.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-185">Die Service Fabric-Cluster-Konfigurationsdatei als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="e2eff-185">The Service Fabric cluster configuration file as a string.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationAsync (apiVersion As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync apiVersion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="apiVersion"><span data-ttu-id="e2eff-186">API-Version.</span><span class="sxs-lookup"><span data-stu-id="e2eff-186">Api version.</span></span></param>
        <summary>
          <para><span data-ttu-id="e2eff-187">Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-187">Gets the Service Fabric cluster configuration file as a string.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-188">Die Service Fabric-Cluster-Konfigurationsdatei als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="e2eff-188">The Service Fabric cluster configuration file as a string.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-189">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-189">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-190">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-190">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-191">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-191">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-192">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-192">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-193">Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab, mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="e2eff-193">Gets the Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-194">Der Service Fabric-Cluster-Konfigurationsdatei als eine Zeichenfolge, mit dem angegebenen Timeout und Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2eff-194">The Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterConfigurationAsync (string apiVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterConfigurationAsync(string apiVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterConfigurationAsync (apiVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="apiVersion"><span data-ttu-id="e2eff-195">API-Version.</span><span class="sxs-lookup"><span data-stu-id="e2eff-195">Api verison.</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-196">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-196">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-197">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-197">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-198">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-198">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-199">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-199">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-200">Die Konfigurationsdatei des Service Fabric-Cluster als Zeichenfolge ab, mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="e2eff-200">Gets the Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-201">Der Service Fabric-Cluster-Konfigurationsdatei als eine Zeichenfolge, mit dem angegebenen Timeout und Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2eff-201">The Service Fabric cluster configuration file as a string, by using the specified timeout and cancellation token.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationUpgradeStatusAsync () As Task(Of FabricOrchestrationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e2eff-202">Ruft den Status einer Aktualisierung läuft ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-202">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-203">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="e2eff-203">FabricOrchestrationUpgradeProgress</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="e2eff-204">Ruft den Status einer Aktualisierung läuft ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-204">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-205">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="e2eff-205">FabricOrchestrationUpgradeProgress</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterConfigurationUpgradeStatusAsync (timeout As TimeSpan) As Task(Of FabricOrchestrationUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync timeout" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-206">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-206">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="e2eff-207">Ruft den Status einer Aktualisierung läuft ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-207">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-208">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="e2eff-208">FabricOrchestrationUpgradeProgress</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterConfigurationUpgradeStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricOrchestrationUpgradeProgress&gt; GetClusterConfigurationUpgradeStatusAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterConfigurationUpgradeStatusAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterConfigurationUpgradeStatusAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;" Usage="clusterManagementClient.GetClusterConfigurationUpgradeStatusAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricOrchestrationUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-209">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-209">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-210">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-210">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-211">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-211">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-212">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-212">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="e2eff-213">Ruft den Status einer Aktualisierung läuft ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-213">Obtains the status of an upgrade in progress.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-214">FabricOrchestrationUpgradeProgress</span><span class="sxs-lookup"><span data-stu-id="e2eff-214">FabricOrchestrationUpgradeProgress</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetClusterManifestAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-215">Ruft den XML-Inhalt des aktuellen ausgeführten clustermanifest ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-215">Gets the XML contents of the current running cluster manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-216">Der Cluster-manifest-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-216">The cluster manifest contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-217">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-217">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-218">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-218">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-219">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-219">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-220">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-220">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-221">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-221">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-222">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-222">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-223">Ruft den XML-Inhalt des aktuellen ausgeführten clustermanifest ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-223">Gets the XML contents of the current running cluster manifest.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-224">Der Cluster-manifest-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-224">The cluster manifest contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-225">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-225">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-226">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-226">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetClusterManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetClusterManifestAsync (System.Fabric.Description.ClusterManifestQueryDescription queryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetClusterManifestAsync(class System.Fabric.Description.ClusterManifestQueryDescription queryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync(System.Fabric.Description.ClusterManifestQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetClusterManifestAsync : System.Fabric.Description.ClusterManifestQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetClusterManifestAsync (queryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queryDescription" Type="System.Fabric.Description.ClusterManifestQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="queryDescription">
          <para><span data-ttu-id="e2eff-227">Gibt zusätzliche Parameter, um zu bestimmen, welche clustermanifest abgerufen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-227">Specifies additional parameters to determine which cluster manifest to retrieve.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-228">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-228">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-229">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-229">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-230">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-230">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-231">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-231">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-232">Ruft den XML-Inhalt eines Clusters entsprechend den Angaben von Manifest <paramref name="queryDescription" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-232">Gets the XML contents of a cluster manifest as specified by <paramref name="queryDescription" />.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-233">Der Cluster-manifest-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-233">The cluster manifest contents.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-234">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-234">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-235">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-235">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetFabricUpgradeProgressAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetFabricUpgradeProgressAsync () As Task(Of FabricUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.GetFabricUpgradeProgressAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;" Usage="clusterManagementClient.GetFabricUpgradeProgressAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-236">Gibt den Status eines Service Fabric-Upgrade-Prozesses zurück.</span><span class="sxs-lookup"><span data-stu-id="e2eff-236">Returns the progress of a Service Fabric upgrade process.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-237">Der Fortschritt einer Service Fabric-Aktualisierungsprozess.</span><span class="sxs-lookup"><span data-stu-id="e2eff-237">The progress of a Service Fabric upgrade process.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-238">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-238">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-239">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-239">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetFabricUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeProgress&gt; GetFabricUpgradeProgressAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetFabricUpgradeProgressAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetFabricUpgradeProgressAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;" Usage="clusterManagementClient.GetFabricUpgradeProgressAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-240">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-240">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-241">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-241">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-242">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-242">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-243">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-243">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-244">Gibt den Status eines Service Fabric-Upgrade-Prozesses zurück.</span><span class="sxs-lookup"><span data-stu-id="e2eff-244">Returns the progress of a Service Fabric upgrade process.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-245">Der Fortschritt einer Service Fabric-Aktualisierungsprozess.</span><span class="sxs-lookup"><span data-stu-id="e2eff-245">The progress of a Service Fabric upgrade process.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-246">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-246">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-247">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-247">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetUpgradeOrchestrationServiceStateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUpgradeOrchestrationServiceStateAsync () As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetUpgradeOrchestrationServiceStateAsync : unit -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetUpgradeOrchestrationServiceStateAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-248">Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge ab.</span><span class="sxs-lookup"><span data-stu-id="e2eff-248">Gets the Service Fabric Upgrade Orchestration Service state as a string.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-249">Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="e2eff-249">The Service Fabric Upgrade Orchestration Service state as a string.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetUpgradeOrchestrationServiceStateAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.GetUpgradeOrchestrationServiceStateAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetUpgradeOrchestrationServiceStateAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="clusterManagementClient.GetUpgradeOrchestrationServiceStateAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-250">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-250">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-251">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-251">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-252">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-252">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-253">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-253">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-254">Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge ab, mit dem angegebenen Timeout und Abbruch token.</span><span class="sxs-lookup"><span data-stu-id="e2eff-254">Gets the Service Fabric Upgrade Orchestration Service state as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-255">Der Dienst zum Service Fabric Upgrade Orchestrierung Status als Zeichenfolge, mit dem angegebenen Timeout und Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2eff-255">The Service Fabric Upgrade Orchestration Service state as a string, by using the specified timeout and cancellation token.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveNextFabricUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync (System.Fabric.FabricUpgradeProgress upgradeProgress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync(class System.Fabric.FabricUpgradeProgress upgradeProgress) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress)" />
      <MemberSignature Language="VB.NET" Value="Public Function MoveNextFabricUpgradeDomainAsync (upgradeProgress As FabricUpgradeProgress) As Task" />
      <MemberSignature Language="F#" Value="member this.MoveNextFabricUpgradeDomainAsync : System.Fabric.FabricUpgradeProgress -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.MoveNextFabricUpgradeDomainAsync upgradeProgress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.FabricUpgradeProgress" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para><span data-ttu-id="e2eff-256">Das Fabric aktualisieren Prozessobjekt verwendet.</span><span class="sxs-lookup"><span data-stu-id="e2eff-256">The fabric upgrade process object to use.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-257">Weist die Dienst-Fabric die nächste upgradedomäne im Cluster zu aktualisieren, wenn die aktuelle upgradedomäne abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-257">Instructs the Service Fabric to upgrade the next upgrade domain in the cluster if the current upgrade domain has been completed.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-258">Der upgradedomäne im Cluster.</span><span class="sxs-lookup"><span data-stu-id="e2eff-258">The upgraded domain in the cluster.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-259">Ähnlich wie <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-259">Similar to <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-260">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-260">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-261">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-261">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="MoveNextFabricUpgradeDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync (System.Fabric.FabricUpgradeProgress upgradeProgress, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task MoveNextFabricUpgradeDomainAsync(class System.Fabric.FabricUpgradeProgress upgradeProgress, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.MoveNextFabricUpgradeDomainAsync(System.Fabric.FabricUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.MoveNextFabricUpgradeDomainAsync : System.Fabric.FabricUpgradeProgress * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.MoveNextFabricUpgradeDomainAsync (upgradeProgress, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeProgress" Type="System.Fabric.FabricUpgradeProgress" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeProgress">
          <para><span data-ttu-id="e2eff-262">Das Fabric aktualisieren Prozessobjekt verwendet.</span><span class="sxs-lookup"><span data-stu-id="e2eff-262">The fabric upgrade process object to use.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-263">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-263">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-264">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-264">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-265">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-265">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-266">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-266">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-267">Weist Service Fabric aktualisieren Sie die nächste upgradedomäne im Cluster aus, wenn die aktuelle upgradedomäne abgeschlossen wurde, mithilfe des angegebenen Timeout und ein Abbruchtoken, das an.</span><span class="sxs-lookup"><span data-stu-id="e2eff-267">Instructs Service Fabric to upgrade the next upgrade domain in the cluster if the current upgrade domain has been completed, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-268">Der upgradedomäne im Cluster.</span><span class="sxs-lookup"><span data-stu-id="e2eff-268">The upgraded domain in the cluster.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-269">Ähnlich wie <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-269">Similar to <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress,System.TimeSpan,System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-270">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-270">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-271">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-271">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionFabricAsync (string patchFilePath, string clusterManifestFilePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionFabricAsync(string patchFilePath, string clusterManifestFilePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ProvisionFabricAsync (patchFilePath As String, clusterManifestFilePath As String) As Task" />
      <MemberSignature Language="F#" Value="member this.ProvisionFabricAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ProvisionFabricAsync (patchFilePath, clusterManifestFilePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patchFilePath" Type="System.String" />
        <Parameter Name="clusterManifestFilePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="patchFilePath">
          <para><span data-ttu-id="e2eff-272">Der Pfad zu den Update-Patch-Datei.</span><span class="sxs-lookup"><span data-stu-id="e2eff-272">The path to the update patch file.</span></span></para>
        </param>
        <param name="clusterManifestFilePath">
          <para><span data-ttu-id="e2eff-273">Der Pfad zum clustermanifest.</span><span class="sxs-lookup"><span data-stu-id="e2eff-273">The path to the cluster manifest.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-274">Stellt die Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-274">Provisions the Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-275">Die bereitgestellte Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-275">The provisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-276">Ein <languageKeyword>null</languageKeyword> Wert ist zulässig, entweder die <paramref name="patchFilePath" /> Parameter oder die <paramref name="clusterManifestFilePath" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="e2eff-276">A <languageKeyword>null</languageKeyword> value is permitted for either the <paramref name="patchFilePath" /> parameter or the <paramref name="clusterManifestFilePath" /> parameter.</span></span> <span data-ttu-id="e2eff-277">Ein <languageKeyword>null</languageKeyword> Wert kann nicht für beide Parameter verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-277">A <languageKeyword>null</languageKeyword> value cannot be used for both parameters.</span></span></para>
          <para><span data-ttu-id="e2eff-278">Dies wird die Patch-Datei und/oder clustermanifestdatei den Speicherort des Image hochladen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-278">This will upload the patch file and/or cluster manifest file to the image store location.</span></span> <span data-ttu-id="e2eff-279">Der Speicherort des Bilds wird als eine Konfigurationseinstellung im clustermanifest angegeben, die bei der Erstellung des Clusters bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-279">The image store location is specified as a configuration setting in the cluster manifest that was provided when the cluster was created.</span></span></para>
          <para><span data-ttu-id="e2eff-280">Clustermanifestprüfung erfolgt im Kontext dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="e2eff-280">Cluster manifest validation will occur within the context of this call.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-281">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-281">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-282">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-282">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ProvisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ProvisionFabricAsync (string patchFilePath, string clusterManifestFilePath, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ProvisionFabricAsync(string patchFilePath, string clusterManifestFilePath, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ProvisionFabricAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ProvisionFabricAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ProvisionFabricAsync (patchFilePath, clusterManifestFilePath, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="patchFilePath" Type="System.String" />
        <Parameter Name="clusterManifestFilePath" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="patchFilePath">
          <para><span data-ttu-id="e2eff-283">Der Pfad zu den Update-Patch-Datei.</span><span class="sxs-lookup"><span data-stu-id="e2eff-283">The path to the update patch file.</span></span></para>
        </param>
        <param name="clusterManifestFilePath">
          <para><span data-ttu-id="e2eff-284">Der Pfad zum clustermanifest.</span><span class="sxs-lookup"><span data-stu-id="e2eff-284">The path to the cluster manifest.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-285">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-285">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-286">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-286">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-287">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-287">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-288">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-288">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-289">Wird für die Fabric-Dienst mithilfe des angegebenen Timeout und ein Abbruchtoken, das bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-289">Provisions the Service Fabric by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-290">Die bereitgestellte Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-290">The provisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-291">Ein <languageKeyword>null</languageKeyword> Wert ist zulässig, entweder die <paramref name="patchFilePath" /> Parameter oder die <paramref name="clusterManifestFilePath" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="e2eff-291">A <languageKeyword>null</languageKeyword> value is permitted for either the <paramref name="patchFilePath" /> parameter or the <paramref name="clusterManifestFilePath" /> parameter.</span></span> <span data-ttu-id="e2eff-292">Ein <languageKeyword>null</languageKeyword> Wert kann nicht für beide Parameter verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-292">A <languageKeyword>null</languageKeyword> value cannot be used for both parameters.</span></span></para>
          <para><span data-ttu-id="e2eff-293">Dies wird die Patch-Datei und/oder clustermanifestdatei den Speicherort des Image hochladen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-293">This will upload the patch file and/or cluster manifest file to the image store location.</span></span> <span data-ttu-id="e2eff-294">Der Speicherort des Bilds wird als eine Konfigurationseinstellung im clustermanifest angegeben, die bei der Erstellung des Clusters bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-294">The image store location is specified as a configuration setting in the cluster manifest that was provided when the cluster was created.</span></span></para>
          <para><span data-ttu-id="e2eff-295">Clustermanifestprüfung erfolgt im Kontext dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="e2eff-295">Cluster manifest validation will occur within the context of this call.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-296">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-296">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-297">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-297">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverPartitionAsync (partitionId As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="e2eff-298">Die Partitions-Id her</span><span class="sxs-lookup"><span data-stu-id="e2eff-298">The partition id to recover</span></span></param>
        <summary>
          <para><span data-ttu-id="e2eff-299">Zeigt die Service Fabric-Cluster an, dass eine bestimmte Partition Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-299">Indicates to the Service Fabric cluster that it should attempt to recover a specific partition which is currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-300">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-300">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-301">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-301">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-302">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-302">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-303">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-303">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-304">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-304">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-305">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-305">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="e2eff-306">Die Partitions-Id her</span><span class="sxs-lookup"><span data-stu-id="e2eff-306">The partition id to recover</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-307">Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-307">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-308">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-308">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-309">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-309">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-310">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-310">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-311">Zeigt die Service Fabric-Cluster an, dass eine bestimmte Partition Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-311">Indicates to the Service Fabric cluster that it should attempt to recover a specific partition which is currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-312">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-312">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-313">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-313">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-314">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-314">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-315">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-315">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-316">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-316">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-317">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-317">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverPartitionsAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionsAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-318">Zeigt die Service Fabric-Cluster an, dass alle Dienste (einschließlich Systemdienste) Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-318">Indicates to the Service Fabric cluster that it should attempt to recover any services (including system services) which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-319">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-319">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-320">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-320">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-321">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-321">Incorrect use of this API can cause potential data loss.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-322">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-322">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-323">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-323">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-324">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-324">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverPartitionsAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverPartitionsAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverPartitionsAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverPartitionsAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverPartitionsAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-325">Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-325">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-326">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-326">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-327">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-327">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-328">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-328">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-329">Zeigt die Service Fabric-Cluster an, dass alle Dienste (einschließlich Systemdienste) Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-329">Indicates to the Service Fabric cluster that it should attempt to recover any services (including system services) which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-330">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-330">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-331">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-331">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-332">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-332">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-333">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-333">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-334">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-334">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-335">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-335">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverServicePartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverServicePartitionsAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverServicePartitionsAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverServicePartitionsAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverServicePartitionsAsync (serviceName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverServicePartitionsAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverServicePartitionsAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="e2eff-336">Der Name des Diensts wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-336">The name of the service to recover.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-337">Service Fabric-Cluster zeigt, dass es sich bei den angegebenen Dienst Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-337">Indicates to the Service Fabric cluster that it should attempt to recover the specified service which is currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-338">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-338">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-339">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-339">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-340">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-340">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-341">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-341">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-342">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-342">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-343">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-343">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverServicePartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverServicePartitionsAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverServicePartitionsAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverServicePartitionsAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverServicePartitionsAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverServicePartitionsAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para><span data-ttu-id="e2eff-344">Der Name des Diensts wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-344">The name of the service to recover.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-345">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-345">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-346">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-346">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-347">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-347">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-348">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-348">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-349">Service Fabric-Cluster zeigt, dass es sich bei den angegebenen Dienst Wiederherstellung durchführen, der derzeit in quorumsverlust feststeckt, mithilfe des angegebenen Timeout und ein Abbruchtoken, das versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-349">Indicates to the Service Fabric cluster that it should attempt to recover the specified service which is currently stuck in quorum loss by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-350">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-350">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-351">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-351">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-352">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-352">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-353">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-353">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-354">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-354">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-355">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-355">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverSystemPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverSystemPartitionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverSystemPartitionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverSystemPartitionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RecoverSystemPartitionsAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RecoverSystemPartitionsAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverSystemPartitionsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-356">Zeigt die Service Fabric-Cluster an, dass Systemdienste Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-356">Indicates to the Service Fabric cluster that it should attempt to recover the system services which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-357">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-357">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-358">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-358">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-359">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-359">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-360">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-360">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-361">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-361">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-362">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-362">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RecoverSystemPartitionsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RecoverSystemPartitionsAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RecoverSystemPartitionsAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RecoverSystemPartitionsAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RecoverSystemPartitionsAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RecoverSystemPartitionsAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-363">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-363">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-364">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-364">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-365">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-365">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-366">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-366">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-367">Zeigt die Service Fabric-Cluster an, dass Systemdienste Wiederherstellung durchführen, der derzeit in quorumsverlust hängen versucht werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-367">Indicates to the Service Fabric cluster that it should attempt to recover the system services which are currently stuck in quorum loss.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-368">Eine Aufgabe, die Bestätigung der Absicht darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-368">A task representing acknowledgement of the intent.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-369">Dieser Vorgang sollte nur ausgeführt werden, wenn bekannt ist, dass die Replikate, die ausgefallen sind, nicht wiederhergestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="e2eff-369">This operation should only be performed if it is known that the replicas that are down cannot be recovered.</span></span> <span data-ttu-id="e2eff-370">Eine falsche Verwendung dieser API kann dazu führen, dass Daten verloren gehen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-370">Incorrect use of this API can cause potential data loss.</span></span> </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-371">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-371">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-372">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-372">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-373">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-373">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveClusterPackage">
      <MemberSignature Language="C#" Value="public void RemoveClusterPackage (string imageStoreConnectionString, string clusterManifestPathInImageStore, string codePackagePathInImageStore);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveClusterPackage(string imageStoreConnectionString, string clusterManifestPathInImageStore, string codePackagePathInImageStore) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveClusterPackage(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveClusterPackage (imageStoreConnectionString As String, clusterManifestPathInImageStore As String, codePackagePathInImageStore As String)" />
      <MemberSignature Language="F#" Value="member this.RemoveClusterPackage : string * string * string -&gt; unit" Usage="clusterManagementClient.RemoveClusterPackage (imageStoreConnectionString, clusterManifestPathInImageStore, codePackagePathInImageStore)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageStoreConnectionString" Type="System.String" />
        <Parameter Name="clusterManifestPathInImageStore" Type="System.String" />
        <Parameter Name="codePackagePathInImageStore" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageStoreConnectionString">
          <para><span data-ttu-id="e2eff-374">Die Verbindungszeichenfolge für den imagespeicher besitzen, der den Einstellungswert im clustermanifest des zielclusters gefunden "ImageStoreConnectionString" entsprechen soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-374">The connection string for the image store, which should match the "ImageStoreConnectionString" setting value found in the cluster manifest of the target cluster.</span></span> <span data-ttu-id="e2eff-375">In einem lokalen Cluster wird der Wert von der Clusterverwaltung während der anfänglichen Bereitstellung ausgewählt wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-375">In an on-premise cluster, the value is chosen during initial deployment by the cluster administrator.</span></span> <span data-ttu-id="e2eff-376">In einem Azure-Cluster über den Azure Resource Manager erstellt ist dieser Wert "Fabric: ImageStore".</span><span class="sxs-lookup"><span data-stu-id="e2eff-376">In an Azure cluster created through the Azure Resource Manager, this value is "fabric:ImageStore".</span></span> <span data-ttu-id="e2eff-377">Der Wert der Image Store Verbindungszeichenfolge kann durch einen Blick auf den Inhalt der Cluster-manifest zurückgegebenes überprüft werden <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-377">The image store connection string value can be checked by looking at the cluster manifest contents returned by <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.GetClusterManifestAsync" />.</span></span> 
            </para>
        </param>
        <param name="clusterManifestPathInImageStore">
          <para><span data-ttu-id="e2eff-378">Der relative Pfad der clustermanifestdatei in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-378">The relative path of cluster manifest file in the image store specified during <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</span></span></para>
        </param>
        <param name="codePackagePathInImageStore">
          <para><span data-ttu-id="e2eff-379">Der relative Pfad des Service Fabric-Codepaket in den imagespeicher besitzen, die während des angegebenen <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-379">The relative path of Service Fabric code package in the image store specified during <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.CopyClusterPackage(System.String,System.String,System.String,System.String,System.String)" />.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-380">Löscht die clustermanifestdatei und/oder Service Fabric-Codepaket aus den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-380">Deletes the cluster manifest file and/or Service Fabric code package from the image store.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="e2eff-381">ClusterManifestPathInImageStore oder CodePackagePathInImageStore-Parameter kann <languageKeyword>null</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="e2eff-381">Either clusterManifestPathInImageStore or codePackagePathInImageStore parameter can be <languageKeyword>null</languageKeyword>.</span></span> <span data-ttu-id="e2eff-382">Jedoch nicht beide Zertifikate werden <languageKeyword>null</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="e2eff-382">However, both of them cannot be <languageKeyword>null</languageKeyword>.</span></span></para>
        </remarks>
        <exception cref="T:System.UnauthorizedAccessException">
          <para><span data-ttu-id="e2eff-383">Fehler bei der Zugriff auf eine Datei auf den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-383">There was an error accessing a file on the image store.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <span data-ttu-id="e2eff-384"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den imagespeicher besitzen.</span><span class="sxs-lookup"><span data-stu-id="e2eff-384"><see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: There was an IO error communicating with the image store.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para><span data-ttu-id="e2eff-385">Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</span><span class="sxs-lookup"><span data-stu-id="e2eff-385">The request timed out but may have already been accepted for processing by the system.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveNodeStateAsync (string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveNodeStateAsync(string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveNodeStateAsync (nodeName As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveNodeStateAsync : string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RemoveNodeStateAsync nodeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2eff-386">Der Name des Knotens der dauerhaft verloren gegangen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-386">The name of the node which has been permanently lost.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-387">Gibt an, dass die persistenten Daten eines Knotens (z. B. aufgrund von Fehler auf dem Datenträger, oder reimaging usw.) verloren gegangen ist und diesem Service Fabric alle Dienste oder Statusangaben auf diesem Knoten als verloren und können nicht wiederhergestellt behandeln soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-387">Indicates that the persisted data of a node is lost (e.g., due to disk failure, or reimage, etc.), and that Service Fabric should treat any services or state on that node as lost and unrecoverable.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-388">Eine Aufgabe, die den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-388">A task representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-389">Nachdem ein Knoten ausfällt, Service Fabric wird nachverfolgen Replikate von permanenten Diensten auf diesem Knoten von da auf diesen Status auf diesem Knoten sind.</span><span class="sxs-lookup"><span data-stu-id="e2eff-389">After a node goes down, Service Fabric will keep track of replicas of persisted services on that node as they have state on that node.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-390">In Fällen, in dem der Administrator bekannt ist und, dass der persistente Zustand auf einem Knoten dauerhaft verloren gegangen ist, die <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> Methode aufgerufen werden... Service Fabric zu benachrichtigen, die der Zustand auf dem Knoten ist nicht mehr vorhanden (oder der Knoten mit dem Status er hatte nie zurückkehren kann).</span><span class="sxs-lookup"><span data-stu-id="e2eff-390">In cases where the administrator knows that the persisted state on a node has been permanently lost the <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> method should be called ... to notify Service Fabric that the state on the node is gone (or the node can never come back with the state it had).</span></span></para>
          <para>
                <span data-ttu-id="e2eff-391">Dies weist Service Fabric beim Warten auf diesem Knoten (und alle beibehaltenen Replikate auf diesem Knoten) wiederherstellen zu beenden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-391">This instructs Service Fabric to stop waiting for that node (and any persisted replicas on that node) to recover.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-392">Hinweis: Diese API muss aufgerufen werden, nachdem sie ermittelt haben, dass der Zustand auf diesem Knoten ausgefallen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-392">NOTE: This API must be called only after it has been determined that the state on that node has been lost.</span></span> </para>
          <para>
                <span data-ttu-id="e2eff-393">Wenn diese API aufgerufen wird, und klicken Sie dann der Knoten wieder mit seinen Status intakt ist es nicht definiertes Verhalten</span><span class="sxs-lookup"><span data-stu-id="e2eff-393">If this API is called and then the node comes back with its state intact it is Undefined Behavior</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-394">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-394">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-395">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-395">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-396">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-396">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveNodeStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveNodeStateAsync (string nodeName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveNodeStateAsync(string nodeName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveNodeStateAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RemoveNodeStateAsync (nodeName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para><span data-ttu-id="e2eff-397">Der Name des Knotens der dauerhaft verloren gegangen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-397">The name of the node which has been permanently lost.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-398">Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-398">The timespan that defines the maximum amount of time  will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-399">Das optionale Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-399">The optional cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-400">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-400">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-401">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-401">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-402">Gibt an, dass ein bestimmter Knoten (die ausgefallen ist) tatsächlich verloren hat, und dieser Service Fabric alle Dienste oder Statusangaben auf diesem Knoten als verloren und können nicht wiederhergestellt behandeln soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-402">Indicates that a particular node (which is down) has actually been lost, and that Service Fabric should treat any services or state on that node as lost and unrecoverable.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-403">Eine Aufgabe, die den Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-403">A task representing the operation.</span></span></para>
        </returns>
        <remarks>
          <para>
                <span data-ttu-id="e2eff-404">Nachdem ein Knoten ausfällt, Service Fabric wird nachverfolgen Replikate von permanenten Diensten auf diesem Knoten von da auf diesen Status auf diesem Knoten sind.</span><span class="sxs-lookup"><span data-stu-id="e2eff-404">After a node goes down, Service Fabric will keep track of replicas of persisted services on that node as they have state on that node.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-405">In Fällen, in dem der Administrator bekannt ist und, dass ein Knoten (und sein Status) dauerhaft verloren gegangen ist, die <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> Methode sollte aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-405">In cases where the administrator knows that a node (and its state) has been permanently lost the <see cref="M:System.Fabric.FabricClient.ClusterManagementClient.RemoveNodeStateAsync(System.String)" /> method should be called.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-406">Dies weist Service Fabric beim Warten auf diesem Knoten (und alle beibehaltenen Replikate auf diesem Knoten) wiederherstellen zu beenden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-406">This instructs Service Fabric to stop waiting for that node (and any persisted replicas on that node) to recover.</span></span></para>
          <para>
                <span data-ttu-id="e2eff-407">Hinweis: Diese API muss aufgerufen werden, nachdem sie ermittelt haben, dass der Zustand auf diesem Knoten ausgefallen ist.</span><span class="sxs-lookup"><span data-stu-id="e2eff-407">NOTE: This API must be called only after it has been determined that the state on that node has been lost.</span></span> </para>
          <para>
                <span data-ttu-id="e2eff-408">Wenn diese API aufgerufen wird, und klicken Sie dann der Knoten wieder mit seinen Status intakt ist es nicht definiertes Verhalten</span><span class="sxs-lookup"><span data-stu-id="e2eff-408">If this API is called and then the node comes back with its state intact it is Undefined Behavior</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                <span data-ttu-id="e2eff-409">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-409">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                <span data-ttu-id="e2eff-410">Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</span><span class="sxs-lookup"><span data-stu-id="e2eff-410">See <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                <span data-ttu-id="e2eff-411">Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-411">See also <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> for handling common FabricClient failures.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResetPartitionLoadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetPartitionLoadAsync (Guid partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResetPartitionLoadAsync(valuetype System.Guid partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ResetPartitionLoadAsync(System.Guid)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResetPartitionLoadAsync (partitionId As Guid) As Task" />
      <MemberSignature Language="F#" Value="member this.ResetPartitionLoadAsync : Guid -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ResetPartitionLoadAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="e2eff-412">Die Partition als Guid dargestellte Id</span><span class="sxs-lookup"><span data-stu-id="e2eff-412">The partition Id represented as a Guid</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="e2eff-413">Setzt eine bestimmte Partition laden</span><span class="sxs-lookup"><span data-stu-id="e2eff-413">Resets a given partition's load</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-414">Der Task, der diese asynchrone Methode zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-414">The task associated with this async method.</span></span> </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetPartitionLoadAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetPartitionLoadAsync (Guid partitionId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ResetPartitionLoadAsync(valuetype System.Guid partitionId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ResetPartitionLoadAsync(System.Guid,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResetPartitionLoadAsync : Guid * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ResetPartitionLoadAsync (partitionId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="partitionId">
          <para><span data-ttu-id="e2eff-415">Die Partition als Guid dargestellte Id</span><span class="sxs-lookup"><span data-stu-id="e2eff-415">The partition Id represented as a Guid</span></span> </para>
        </param>
        <param name="timeout">
          <para> <span data-ttu-id="e2eff-416">Die Zeitdauer, in dem die asynchrone Methode in der Reihenfolge für die aufzurufende Methode kein Timeout abgeschlossen werden muss.</span><span class="sxs-lookup"><span data-stu-id="e2eff-416">The length of time within which the async method must complete in order for the method to not time out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-417">Ein Abbruchtoken, das für diese Methode.</span><span class="sxs-lookup"><span data-stu-id="e2eff-417">A cancellation token for this method.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="e2eff-418">Setzt eine bestimmte Partition laden</span><span class="sxs-lookup"><span data-stu-id="e2eff-418">Resets a given partition's load</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-419">Der Task, der diese asynchrone Methode zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-419">The task associated with this async method.</span></span> </para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackFabricUpgradeAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackFabricUpgradeAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RollbackFabricUpgradeAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RollbackFabricUpgradeAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RollbackFabricUpgradeAsync : unit -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RollbackFabricUpgradeAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="e2eff-420">Rollback für die Service Fabric, um den Vorgang zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2eff-420">Rolls back the Service Fabric to upgrade the operation.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-421">Das Rollback Service Fabric so aktualisieren Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-421">The rollback Service Fabric to upgrade the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RollbackFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RollbackFabricUpgradeAsync (TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RollbackFabricUpgradeAsync(valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.RollbackFabricUpgradeAsync(System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RollbackFabricUpgradeAsync : TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.RollbackFabricUpgradeAsync (timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-422">Die Zeitspanne, die die maximale Zeitdauer, die Service Fabric diesen Vorgang definiert, um den Vorgang fortzusetzen, vor der Rückgabe einer Timeoutausnahme ausgelöst werden kann.</span><span class="sxs-lookup"><span data-stu-id="e2eff-422">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a timeout exception.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-423">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-423">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-424">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-424">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-425">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-425">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-426">Rollback für die Service Fabric, um den Vorgang zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="e2eff-426">Rolls back the Service Fabric to upgrade the operation.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-427">Das Rollback Service Fabric so aktualisieren Sie den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-427">The rollback Service Fabric to upgrade the operation.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync (string state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync(string state) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.SetUpgradeOrchestrationServiceStateAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SetUpgradeOrchestrationServiceStateAsync (state As String) As Task(Of FabricUpgradeOrchestrationServiceState)" />
      <MemberSignature Language="F#" Value="member this.SetUpgradeOrchestrationServiceStateAsync : string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;" Usage="clusterManagementClient.SetUpgradeOrchestrationServiceStateAsync state" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="e2eff-428">Status-Eingabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-428">state input</span></span></param>
        <summary>
          <para><span data-ttu-id="e2eff-429">Legt den Status der Dienst zum Service Fabric Upgrade Orchestrierung als Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="e2eff-429">Sets the Service Fabric Upgrade Orchestration Service state as a string.</span></span></para>
        </summary>
        <returns><span data-ttu-id="e2eff-430">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-430">Task</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetUpgradeOrchestrationServiceStateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync (string state, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.FabricUpgradeOrchestrationServiceState&gt; SetUpgradeOrchestrationServiceStateAsync(string state, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.SetUpgradeOrchestrationServiceStateAsync(System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SetUpgradeOrchestrationServiceStateAsync : string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;" Usage="clusterManagementClient.SetUpgradeOrchestrationServiceStateAsync (state, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.FabricUpgradeOrchestrationServiceState&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="e2eff-431">Status-Eingabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-431">state input</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-432">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-432">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-433">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-433">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-434">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-434">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-435">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-435">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-436">Legt den Status der Dienst zum Service Fabric Upgrade Orchestrierung als eine Zeichenfolge mithilfe des angegebenen Timeout und ein Abbruchtoken, das fest.</span><span class="sxs-lookup"><span data-stu-id="e2eff-436">Sets the Service Fabric Upgrade Orchestration Service state as a string, by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-437">Der Status der Dienst zum Service Fabric Upgrade Orchestrierung mithilfe des angegebenen Timeout und ein Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2eff-437">The Service Fabric Upgrade Orchestration Service state, by using the specified timeout and cancellation token.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToggleVerboseServicePlacementHealthReportingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToggleVerboseServicePlacementHealthReportingAsync (enabled As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.ToggleVerboseServicePlacementHealthReportingAsync : bool -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">
          <para><span data-ttu-id="e2eff-438">Ein boolescher Wert, der bei "true" bewirkt, dass reporting wird ein Replikat kann nicht platziert werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-438">A boolean value, which if true causes reporting when a replica is unabled to be placed.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="e2eff-439">Schaltet, ob der Cluster Resource Balancer eine Warnung der Integrität meldet, wenn sie ein Replikat platzieren kann.</span><span class="sxs-lookup"><span data-stu-id="e2eff-439">Toggles whether the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-440">Der Task, der diese asynchrone Methode zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-440">The task associated with this async method.</span></span> </para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-441">Diese Methode zweimal mit dem Wert "false" aufgerufen wird, löscht sie aus dem Arbeitsspeicher die Berichte, die potenziell ausgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-441">If this method is called twice with the value false, it clears from memory the reports that would potentially have been emitted.</span></span>
            <span data-ttu-id="e2eff-442">Wenn diese Methode mit dem Wert "true" aufgerufen wird, meldet der Cluster Resource Balancer Integrität Warnung, wenn sie ein Replikat platzieren kann.</span><span class="sxs-lookup"><span data-stu-id="e2eff-442">If this method is called with the value true, the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            <span data-ttu-id="e2eff-443">Wenn solche Health-Warnungen, integritätsprüfungen für eine überwachte Upgrades blockiert werden kann die Umschaltfläche deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="e2eff-443">If such health warnings are blocking a monitored upgrade's health checks the toggle can be switched off.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToggleVerboseServicePlacementHealthReportingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync (bool enabled, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task ToggleVerboseServicePlacementHealthReportingAsync(bool enabled, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync(System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ToggleVerboseServicePlacementHealthReportingAsync : bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.ToggleVerboseServicePlacementHealthReportingAsync (enabled, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="enabled">
          <para><span data-ttu-id="e2eff-444">Ein boolescher Wert, der bei "true" bewirkt, dass reporting wird ein Replikat kann nicht platziert werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-444">A boolean value, which if true causes reporting when a replica is unabled to be placed.</span></span> </para>
        </param>
        <param name="timeout">
          <para> <span data-ttu-id="e2eff-445">Die Zeitdauer, in dem die asynchrone Methode in der Reihenfolge für die aufzurufende Methode kein Timeout abgeschlossen werden muss.</span><span class="sxs-lookup"><span data-stu-id="e2eff-445">The length of time within which the async method must complete in order for the method to not time out.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-446">Ein Abbruchtoken, das für diese Methode.</span><span class="sxs-lookup"><span data-stu-id="e2eff-446">A cancellation token for this method.</span></span> </para>
        </param>
        <summary>
          <para> 
            <span data-ttu-id="e2eff-447">Schaltet, ob der Cluster Resource Balancer eine Warnung der Integrität meldet, wenn sie ein Replikat platzieren kann.</span><span class="sxs-lookup"><span data-stu-id="e2eff-447">Toggles whether the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            </para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-448">Der Task, der diese asynchrone Methode zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-448">The task associated with this async method.</span></span> </para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-449">Diese Methode zweimal mit dem Wert "false" aufgerufen wird, löscht sie aus dem Arbeitsspeicher die Berichte, die potenziell ausgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-449">If this method is called twice with the value false, it clears from memory the reports that would potentially have been emitted.</span></span>
            <span data-ttu-id="e2eff-450">Wenn diese Methode mit dem Wert "true" aufgerufen wird, meldet der Cluster Resource Balancer Integrität Warnung, wenn sie ein Replikat platzieren kann.</span><span class="sxs-lookup"><span data-stu-id="e2eff-450">If this method is called with the value true, the Cluster Resource Balancer will report a health warning when it's unable to place a replica.</span></span>
            <span data-ttu-id="e2eff-451">Wenn solche Health-Warnungen, integritätsprüfungen für eine überwachte Upgrades blockiert werden, kann die Umschaltfläche deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="e2eff-451">If such health warnings are blocking a monitored upgrade's health checks, the toggle can be switched off.</span></span> </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionFabricAsync (string codeVersion, string configVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionFabricAsync(string codeVersion, string configVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UnprovisionFabricAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnprovisionFabricAsync (codeVersion As String, configVersion As String) As Task" />
      <MemberSignature Language="F#" Value="member this.UnprovisionFabricAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UnprovisionFabricAsync (codeVersion, configVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="configVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="codeVersion">
          <para><span data-ttu-id="e2eff-452">Die Codeversion Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-452">The code version to unprovision.</span></span></para>
        </param>
        <param name="configVersion">
          <para><span data-ttu-id="e2eff-453">Die Konfigurationsversion Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-453">The configuration version to unprovision.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-454">Unprovisions des Dienst-Fabrics.</span><span class="sxs-lookup"><span data-stu-id="e2eff-454">Unprovisions the Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-455">Die nicht bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-455">The unprovisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>
          <para><span data-ttu-id="e2eff-456">Ein <languageKeyword>null</languageKeyword> Wert ist zulässig, entweder die <paramref name="codeVersion" /> Parameter oder die <paramref name="configVersion" /> Parameter.</span><span class="sxs-lookup"><span data-stu-id="e2eff-456">A <languageKeyword>null</languageKeyword> value is permitted for either the <paramref name="codeVersion" /> parameter or the <paramref name="configVersion" /> parameter.</span></span> <span data-ttu-id="e2eff-457">Ein <languageKeyword>null</languageKeyword> Wert kann nicht für beide Parameter verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="e2eff-457">A <languageKeyword>null</languageKeyword> value cannot be used for both parameters.</span></span></para>
          <para><span data-ttu-id="e2eff-458">Dadurch wird die Patch-Datei und/oder clustermanifestdatei aus der Image-Speicherort gelöscht.</span><span class="sxs-lookup"><span data-stu-id="e2eff-458">This will delete the patch file and/or cluster manifest file from the image store location.</span></span> <span data-ttu-id="e2eff-459">Der Speicherort des Bilds wird als eine Konfigurationseinstellung im clustermanifest angegeben, die bei der Erstellung des Clusters bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="e2eff-459">The image store location is specified as a configuration setting in the cluster manifest that was provided when the cluster was created.</span></span></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-460">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-460">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-461">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-461">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UnprovisionFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnprovisionFabricAsync (string codeVersion, string configVersion, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnprovisionFabricAsync(string codeVersion, string configVersion, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UnprovisionFabricAsync(System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnprovisionFabricAsync : string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UnprovisionFabricAsync (codeVersion, configVersion, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="codeVersion" Type="System.String" />
        <Parameter Name="configVersion" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="codeVersion">
          <para><span data-ttu-id="e2eff-462">Die Codeversion Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-462">The code version to unprovision.</span></span></para>
        </param>
        <param name="configVersion">
          <para><span data-ttu-id="e2eff-463">Die Konfigurationsversion Bereitstellung.</span><span class="sxs-lookup"><span data-stu-id="e2eff-463">The configuration version to unprovision.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-464">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-464">The maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-465">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-465">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-466">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-466">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-467">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-467">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-468">Unprovisions der Fabric-Dienst mithilfe des angegebenen Timeout und ein Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2eff-468">Unprovisions the Service Fabric by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-469">Die nicht bereitgestellten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-469">The unprovisioned Service Fabric.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-470">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-470">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-471">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-471">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateFabricUpgradeAsync (System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateFabricUpgradeAsync(class System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateFabricUpgradeAsync (updateDescription As FabricUpgradeUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateFabricUpgradeAsync : System.Fabric.Description.FabricUpgradeUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpdateFabricUpgradeAsync updateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.FabricUpgradeUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para><span data-ttu-id="e2eff-472">Beschreibung der neuen Upgrade Parameter angewendet.</span><span class="sxs-lookup"><span data-stu-id="e2eff-472">Description of the new upgrade parameters to apply.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-473">Ändert die Upgrade-Parameter, die das Verhalten des aktuellen clusterupgrade beschreiben.</span><span class="sxs-lookup"><span data-stu-id="e2eff-473">Modifies the upgrade parameters that describe the behavior of the current cluster upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-474">Das aktuelle clusterupgrade.</span><span class="sxs-lookup"><span data-stu-id="e2eff-474">The current cluster upgrade.</span></span></para>
        </returns>
        <remarks />
      </Docs>
    </Member>
    <Member MemberName="UpdateFabricUpgradeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateFabricUpgradeAsync (System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateFabricUpgradeAsync(class System.Fabric.Description.FabricUpgradeUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpdateFabricUpgradeAsync(System.Fabric.Description.FabricUpgradeUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateFabricUpgradeAsync : System.Fabric.Description.FabricUpgradeUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpdateFabricUpgradeAsync (updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="updateDescription" Type="System.Fabric.Description.FabricUpgradeUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="updateDescription">
          <para> <span data-ttu-id="e2eff-475">Die neuen Upgrade Parameter angewendet.</span><span class="sxs-lookup"><span data-stu-id="e2eff-475">The new upgrade parameters to apply.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-476">Die maximale Zeitdauer Service Fabric können diesen Vorgang fortzusetzen, vor dem Auslösen einer <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-476">The maximum amount of time Service Fabric will allow this operation to continue before throwing a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-477">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-477">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-478">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-478">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-479">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-479">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-480">Ändert die Upgrade-Parameter, die das Verhalten des aktuellen clusterupgrade beschreiben.</span><span class="sxs-lookup"><span data-stu-id="e2eff-480">Modifies the upgrade parameters that describe the behavior of the current cluster upgrade.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-481">Das aktuelle clusterupgrade.</span><span class="sxs-lookup"><span data-stu-id="e2eff-481">The current cluster upgrade.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeConfigurationAsync (description As ConfigurationUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="e2eff-482">Enthält: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="e2eff-482">Contains: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span>
            </param>
        <summary>
            <span data-ttu-id="e2eff-483">Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="e2eff-483">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-484">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-484">Task</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="e2eff-485">Enthält: ClusterConfigPath, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="e2eff-485">Contains: ClusterConfigPath, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span></param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-486">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-486">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-487">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-487">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-488">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-488">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="e2eff-489">Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="e2eff-489">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-490">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-490">Task</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeConfigurationAsync (description As ConfigurationUpgradeDescription, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="e2eff-491">Enthält: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="e2eff-491">Contains: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-492">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-492">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="e2eff-493">Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="e2eff-493">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-494">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-494">Task</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeConfigurationAsync (System.Fabric.Description.ConfigurationUpgradeDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeConfigurationAsync(class System.Fabric.Description.ConfigurationUpgradeDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeConfigurationAsync(System.Fabric.Description.ConfigurationUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeConfigurationAsync : System.Fabric.Description.ConfigurationUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeConfigurationAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ConfigurationUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="e2eff-495">Enthält: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span><span class="sxs-lookup"><span data-stu-id="e2eff-495">Contains: ClusterConfig, HealthCheckRetryTimeout, HealthCheckWaitDuration, HealthCheckStableDuration, UpgradeDomainTimeout, UpgradeTimeout, MaxPercentUnhealthyApplications, MaxPercentUnhealthyNodes, MaxPercentDeltaUnhealthyNodes, MaxPercentUpgradeDomainDeltaUnhealthyNodes</span></span></param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-496">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-496">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-497">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-497">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-498">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-498">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-499">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-499">Note that cancellation is advisory and that the operation may still be completed even if it is canceled.</span></span></para>
        </param>
        <summary>
            <span data-ttu-id="e2eff-500">Initiieren Sie ein Upgrade mithilfe einer Konfigurationsdatei für den Cluster.</span><span class="sxs-lookup"><span data-stu-id="e2eff-500">Initiate an Upgrade using a cluster configuration file.</span></span>
            </summary>
        <returns><span data-ttu-id="e2eff-501">Aufgabe</span><span class="sxs-lookup"><span data-stu-id="e2eff-501">Task</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeFabricAsync (System.Fabric.Description.FabricUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeFabricAsync(class System.Fabric.Description.FabricUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeFabricAsync(System.Fabric.Description.FabricUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpgradeFabricAsync (upgradeDescription As FabricUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpgradeFabricAsync : System.Fabric.Description.FabricUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeFabricAsync upgradeDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.FabricUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para><span data-ttu-id="e2eff-502">Die Beschreibung des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="e2eff-502">The description of the upgrade.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-503">Der Service Fabric-Upgrades.</span><span class="sxs-lookup"><span data-stu-id="e2eff-503">Upgrades the Service Fabric.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-504">Die aktualisierten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-504">The upgraded Service Fabric.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-505">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-505">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-506">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-506">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeFabricAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpgradeFabricAsync (System.Fabric.Description.FabricUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpgradeFabricAsync(class System.Fabric.Description.FabricUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ClusterManagementClient.UpgradeFabricAsync(System.Fabric.Description.FabricUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpgradeFabricAsync : System.Fabric.Description.FabricUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="clusterManagementClient.UpgradeFabricAsync (upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeDescription" Type="System.Fabric.Description.FabricUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="upgradeDescription">
          <para><span data-ttu-id="e2eff-507">Die Beschreibung des Upgrades.</span><span class="sxs-lookup"><span data-stu-id="e2eff-507">The description of the upgrade.</span></span></para>
        </param>
        <param name="timeout">
          <para><span data-ttu-id="e2eff-508">Die Zeitspanne, die die maximale Zeitdauer definiert Service Fabric können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</span><span class="sxs-lookup"><span data-stu-id="e2eff-508">The timespan that defines the maximum amount of time Service Fabric will allow this operation to continue before returning a <see cref="T:System.TimeoutException" />.</span></span></para>
        </param>
        <param name="cancellationToken">
          <para><span data-ttu-id="e2eff-509">Das Abbruchtoken, das beobachten von der Vorgang.</span><span class="sxs-lookup"><span data-stu-id="e2eff-509">The cancellation token that the operation is observing.</span></span> <span data-ttu-id="e2eff-510">Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="e2eff-510">It can be used to send a notification that the operation should be canceled.</span></span> <span data-ttu-id="e2eff-511">Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</span><span class="sxs-lookup"><span data-stu-id="e2eff-511">Note that cancellation is advisory and that the operation may still be completed even if it is cancelled.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="e2eff-512">Aktualisiert die Fabric-Dienst mithilfe des angegebenen Timeout und ein Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e2eff-512">Upgrades the Service Fabric by using the specified timeout and cancellation token.</span></span></para>
        </summary>
        <returns>
          <para><span data-ttu-id="e2eff-513">Die aktualisierten Service Fabric.</span><span class="sxs-lookup"><span data-stu-id="e2eff-513">The upgraded Service Fabric.</span></span></para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><span data-ttu-id="e2eff-514">Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".</span><span class="sxs-lookup"><span data-stu-id="e2eff-514">The <see cref="T:System.Fabric.FabricClient" /> object is in a closed state.</span></span> <span data-ttu-id="e2eff-515">Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="e2eff-515">Dispose of the <see cref="T:System.Fabric.FabricClient" /> object you are using and instantiate a new <see cref="T:System.Fabric.FabricClient" /> object.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>