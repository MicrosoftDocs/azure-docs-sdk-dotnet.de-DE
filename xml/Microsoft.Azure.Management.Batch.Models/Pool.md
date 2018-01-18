<Type Name="Pool" FullName="Microsoft.Azure.Management.Batch.Models.Pool">
  <TypeSignature Language="C#" Value="public class Pool : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Pool extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Pool" />
  <TypeSignature Language="VB.NET" Value="Public Class Pool&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Pool = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f581a-101">Enthält Informationen zu einem Pool an.</span><span class="sxs-lookup"><span data-stu-id="f581a-101">Contains information about a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f581a-102">Initialisiert eine neue Instanz der Klasse Pool an.</span><span class="sxs-lookup"><span data-stu-id="f581a-102">Initializes a new instance of the Pool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool (string id = null, string name = null, string type = null, string etag = null, string displayName = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState = null, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, string vmSize = null, Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration = null, Nullable&lt;int&gt; currentDedicatedNodes = null, Nullable&lt;int&gt; currentLowPriorityNodes = null, Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication = null, Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Management.Batch.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string displayName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, string vmSize, class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration, valuetype System.Nullable`1&lt;int32&gt; currentDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; currentLowPriorityNodes, class Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication, class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Management.Batch.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolProvisioningState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.AllocationState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.ScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleRun,System.Nullable{Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState},Microsoft.Azure.Management.Batch.Models.NetworkConfiguration,System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.MetadataItem},Microsoft.Azure.Management.Batch.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Pool : string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.ScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleRun * Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; * Microsoft.Azure.Management.Batch.Models.NetworkConfiguration * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; * Microsoft.Azure.Management.Batch.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="new Microsoft.Azure.Management.Batch.Models.Pool (id, name, type, etag, displayName, lastModified, creationTime, provisioningState, provisioningStateTransitionTime, allocationState, allocationStateTransitionTime, vmSize, deploymentConfiguration, currentDedicatedNodes, currentLowPriorityNodes, scaleSettings, autoScaleRun, interNodeCommunication, networkConfiguration, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata, startTask, certificates, applicationPackages, applicationLicenses, resizeOperationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="deploymentConfiguration" Type="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" />
        <Parameter Name="currentDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
        <Parameter Name="autoScaleRun" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleRun" />
        <Parameter Name="interNodeCommunication" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Management.Batch.Models.StartTask" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resizeOperationStatus" Type="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f581a-103">Die ID der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f581a-103">The ID of the resource.</span></span></param>
        <param name="name"><span data-ttu-id="f581a-104">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f581a-104">The name of the resource.</span></span></param>
        <param name="type"><span data-ttu-id="f581a-105">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="f581a-105">The type of the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="f581a-106">Das ETag der Ressource, für Parallelität-Anweisungen verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f581a-106">The ETag of the resource, used for concurrency statements.</span></span></param>
        <param name="displayName"><span data-ttu-id="f581a-107">Der Anzeigename für den Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-107">The display name for the pool.</span></span></param>
        <param name="lastModified"><span data-ttu-id="f581a-108">Uhrzeit des Pools wird von der letzten Änderung.</span><span class="sxs-lookup"><span data-stu-id="f581a-108">The last modified time of the pool.</span></span></param>
        <param name="creationTime"><span data-ttu-id="f581a-109">Die Erstellungszeit des Pools.</span><span class="sxs-lookup"><span data-stu-id="f581a-109">The creation time of the pool.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f581a-110">Der aktuelle Status des Pools.</span><span class="sxs-lookup"><span data-stu-id="f581a-110">The current state of the pool.</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="f581a-111">Der Zeitpunkt, an dem der Pool seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="f581a-111">The time at which the pool entered its current state.</span></span></param>
        <param name="allocationState"><span data-ttu-id="f581a-112">Gibt an, ob der Pool Größe ist.</span><span class="sxs-lookup"><span data-stu-id="f581a-112">Whether the pool is resizing.</span></span></param>
        <param name="allocationStateTransitionTime"><span data-ttu-id="f581a-113">Der Zeitpunkt, an dem der Pool seinen aktuellen Zuordnungsstatus erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="f581a-113">The time at which the pool entered its current allocation state.</span></span></param>
        <param name="vmSize"><span data-ttu-id="f581a-114">Die Größe der virtuellen Maschinen in den Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-114">The size of virtual machines in the pool.</span></span> <span data-ttu-id="f581a-115">Alle virtuellen Computer in einem Pool haben die gleiche Größe.</span><span class="sxs-lookup"><span data-stu-id="f581a-115">All VMs in a pool are the same size.</span></span></param>
        <param name="deploymentConfiguration"><span data-ttu-id="f581a-116">Diese Eigenschaft beschreibt, wie die Pool-Knoten werden mit Cloud-Dienste oder virtuelle Computer - bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="f581a-116">This property describes how the pool nodes will be deployed - using Cloud Services or Virtual Machines.</span></span></param>
        <param name="currentDedicatedNodes"><span data-ttu-id="f581a-117">Die Anzahl der Serverknoten derzeit im Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-117">The number of compute nodes currently in the pool.</span></span></param>
        <param name="currentLowPriorityNodes"><span data-ttu-id="f581a-118">Die Anzahl der mit niedriger Priorität Serverknoten derzeit im Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-118">The number of low priority compute nodes currently in the pool.</span></span></param>
        <param name="scaleSettings"><span data-ttu-id="f581a-119">Einstellungen, die die Anzahl der Knoten im Pool zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="f581a-119">Settings which configure the number of nodes in the pool.</span></span></param>
        <param name="autoScaleRun"><span data-ttu-id="f581a-120">Die Ergebnisse und Fehler von der letzten Ausführung der Formel für automatische Skalierung.</span><span class="sxs-lookup"><span data-stu-id="f581a-120">The results and errors from the last execution of the autoscale formula.</span></span></param>
        <param name="interNodeCommunication"><span data-ttu-id="f581a-121">Gibt an, ob der Pool für direkte Kommunikation zwischen Knoten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="f581a-121">Whether the pool permits direct communication between nodes.</span></span></param>
        <param name="networkConfiguration"><span data-ttu-id="f581a-122">Die Netzwerkkonfiguration des Pools.</span><span class="sxs-lookup"><span data-stu-id="f581a-122">The network configuration for the pool.</span></span></param>
        <param name="maxTasksPerNode"><span data-ttu-id="f581a-123">Die maximale Anzahl von Tasks, die gleichzeitig auf einem einzelnen Computeknoten im Pool ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="f581a-123">The maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span></param>
        <param name="taskSchedulingPolicy"><span data-ttu-id="f581a-124">Wie Aufgaben auf Serverknoten in einem Pool verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-124">How tasks are distributed across compute nodes in a pool.</span></span></param>
        <param name="userAccounts"><span data-ttu-id="f581a-125">Die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-125">The list of user accounts to be created on each node in the pool.</span></span></param>
        <param name="metadata"><span data-ttu-id="f581a-126">Eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f581a-126">A list of name-value pairs associated with the pool as metadata.</span></span></param>
        <param name="startTask"><span data-ttu-id="f581a-127">Eine Aufgabe, die auf den einzelnen Computeknoten ausgeführt wird, wie den Pool hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="f581a-127">A task specified to run on each compute node as it joins the pool.</span></span></param>
        <param name="certificates"><span data-ttu-id="f581a-128">Die Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-128">The list of certificates to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationPackages"><span data-ttu-id="f581a-129">Die Liste der Anwendungspakete auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-129">The list of application packages to be installed on each compute node in the pool.</span></span></param>
        <param name="applicationLicenses"><span data-ttu-id="f581a-130">Die Liste der Anwendung Lizenz zur Nutzung der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-130">The list of application licenses the Batch service will make available on each compute node in the pool.</span></span></param>
        <param name="resizeOperationStatus"><span data-ttu-id="f581a-131">Enthält Details über die aktuellen oder letzten abgeschlossenen Größenänderung.</span><span class="sxs-lookup"><span data-stu-id="f581a-131">Contains details about the current or last completed resize operation.</span></span></param>
        <summary>
            <span data-ttu-id="f581a-132">Initialisiert eine neue Instanz der Klasse Pool an.</span><span class="sxs-lookup"><span data-stu-id="f581a-132">Initializes a new instance of the Pool class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="f581a-133">Ruft ab, ob die Größe der Pool ändert.</span><span class="sxs-lookup"><span data-stu-id="f581a-133">Gets whether the pool is resizing.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="f581a-134">Gültige Werte:</span><span class="sxs-lookup"><span data-stu-id="f581a-134">Values are:</span></span>
            
             <span data-ttu-id="f581a-135">Steady - ist der Pool nicht vergrößern/verkleinern.</span><span class="sxs-lookup"><span data-stu-id="f581a-135">Steady - The pool is not resizing.</span></span> <span data-ttu-id="f581a-136">Es sind keine Änderungen auf die Anzahl der Knoten im Pool ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f581a-136">There are no changes to the number of nodes in the pool in progress.</span></span> <span data-ttu-id="f581a-137">Ein Pool geht in diesen Zustand, bei der Erstellung und keine Vorgänge für den Pool so ändern Sie die Anzahl der dedizierten Knoten ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-137">A pool enters this state when it is created and when no operations are being performed on the pool to change the number of dedicated nodes.</span></span>
             <span data-ttu-id="f581a-138">Ändern der Größe - Pool ist Größenänderung; d. h. berechnen Knoten werden hinzugefügt oder aus dem Pool entfernt.</span><span class="sxs-lookup"><span data-stu-id="f581a-138">Resizing - The pool is resizing; that is, compute nodes are being added to or removed from the pool.</span></span>
             <span data-ttu-id="f581a-139">Beenden - Pool wurde ihre Größe ändern, aber der Benutzer hat angefordert, dass die Größenänderung beendet wird, aber die beendigungsanforderung wurde noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="f581a-139">Stopping - The pool was resizing, but the user has requested that the resize be stopped, but the stop request has not yet been completed.</span></span> <span data-ttu-id="f581a-140">Folgende Werte sind möglich: "Stetige", "Größe", "Beenden"</span><span class="sxs-lookup"><span data-stu-id="f581a-140">Possible values include: 'Steady', 'Resizing', 'Stopping'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-141">Ruft den Zeitpunkt, an dem der Pool seinen aktuellen Zuordnungsstatus erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="f581a-141">Gets the time at which the pool entered its current allocation state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-142">Ruft ab oder legt die Liste der Anwendungslizenzen der Batch-Dienst auf jeder Serverknoten im Pool verfügbar gemacht werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-142">Gets or sets the list of application licenses the Batch service will make available on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-143">Die Liste der Anwendungslizenzen muss es sich um eine Teilmenge der verfügbaren Batch Dienstlizenzen Anwendung sein.</span><span class="sxs-lookup"><span data-stu-id="f581a-143">The list of application licenses must be a subset of available Batch service application licenses.</span></span> <span data-ttu-id="f581a-144">Pool-Erstellung schlägt fehl, wenn eine Lizenz angefordert wird, die nicht unterstützt wird.</span><span class="sxs-lookup"><span data-stu-id="f581a-144">If a license is requested which is not supported, pool creation will fail.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackages As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationPackages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-145">Ruft ab oder legt die Liste der Anwendungspakete auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-145">Gets or sets the list of application packages to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-146">Änderungen an Anwendungspakete Auswirkungen auf alle neuen Serverknoten verknüpfen den Pool, aber wirken sich nicht auf die Serverknoten, die bereits im Pool befinden, bis er neu gestartet oder ein reimaging ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-146">Changes to application packages affect all new compute nodes joining the pool, but do not affect compute nodes that are already in the pool until they are rebooted or reimaged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Management.Batch.Models.AutoScaleRun" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoScaleRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-147">Ruft die Ergebnisse und Fehler aus der letzten Ausführung der Formel für automatische Skalierung ab.</span><span class="sxs-lookup"><span data-stu-id="f581a-147">Gets the results and errors from the last execution of the autoscale formula.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-148">Diese Eigenschaft wird festgelegt, nur wenn der Pool automatisch skaliert, d. h. AutoScaleSettings verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-148">This property is set only if the pool automatically scales, i.e. autoScaleSettings are used.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-149">Ruft ab oder legt die Liste der Zertifikate auf jeder Serverknoten im Pool installiert werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-149">Gets or sets the list of certificates to be installed on each compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-150">Für Serverknoten für Windows, installiert der Batch-Dienst die Zertifikate auf den angegebenen Zertifikatspeicher und den Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="f581a-150">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="f581a-151">Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="f581a-151">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="f581a-152">Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-152">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-153">Ruft die Erstellungszeit des Pools an.</span><span class="sxs-lookup"><span data-stu-id="f581a-153">Gets the creation time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-154">Ruft die Anzahl von Serverknoten, die derzeit im Pool ab.</span><span class="sxs-lookup"><span data-stu-id="f581a-154">Gets the number of compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-155">Ruft die Anzahl der mit niedriger Priorität Serverknoten derzeit im Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-155">Gets the number of low priority compute nodes currently in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentConfiguration As DeploymentConfiguration" />
      <MemberSignature Language="F#" Value="member this.DeploymentConfiguration : Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deploymentConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-156">Ruft ab oder legt diese Eigenschaft beschreibt, wie die Pool-Knoten bereitgestellt werden – mit Cloud-Dienste oder virtuelle Computer.</span><span class="sxs-lookup"><span data-stu-id="f581a-156">Gets or sets this property describes how the pool nodes will be deployed - using Cloud Services or Virtual Machines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-157">Mit CloudServiceConfiguration gibt an, dass die Knoten mithilfe einer Azure-Cloud-Dienste (PaaS), während VirtualMachineConfiguration Azure Virtual Machines (IaaS) verwendet erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="f581a-157">Using CloudServiceConfiguration specifies that the nodes should be creating using Azure Cloud Services (PaaS), while VirtualMachineConfiguration uses Azure Virtual Machines (IaaS).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-158">Ruft ab oder legt den Anzeigenamen für den Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-158">Gets or sets the display name for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-159">Der Anzeigename muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.</span><span class="sxs-lookup"><span data-stu-id="f581a-159">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="InterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property InterNodeCommunication As Nullable(Of InterNodeCommunicationState)" />
      <MemberSignature Language="F#" Value="member this.InterNodeCommunication : Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-160">Ruft ab oder legt fest, ob der Pool direkten Kommunikation zwischen Knoten ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="f581a-160">Gets or sets whether the pool permits direct communication between nodes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-161">Dies schränkt ein, auf dem Knoten, die dem Pool zugewiesen werden können.</span><span class="sxs-lookup"><span data-stu-id="f581a-161">This imposes restrictions on which nodes can be assigned to the pool.</span></span> <span data-ttu-id="f581a-162">Aktivieren diesen Wert reduzieren die Wahrscheinlichkeit für die angeforderte Anzahl von Knoten in den Pool zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f581a-162">Enabling this value can reduce the chance of the requested number of nodes to be allocated in the pool.</span></span> <span data-ttu-id="f581a-163">Wenn nicht angegeben, dieser Wert wird standardmäßig auf "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="f581a-163">If not specified, this value defaults to 'Disabled'.</span></span> <span data-ttu-id="f581a-164">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="f581a-164">Possible values include: 'Enabled', 'Disabled'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-165">Ruft den Zeitpunkt den letzten Änderung des Pools an.</span><span class="sxs-lookup"><span data-stu-id="f581a-165">Gets the last modified time of the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-166">Dies ist der letzten Ausführung bei der die Ebene Pool-Daten, z. B. die TargetDedicatedNodes oder AutoScaleSettings, geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="f581a-166">This is the last time at which the pool level data, such as the targetDedicatedNodes or autoScaleSettings, changed.</span></span> <span data-ttu-id="f581a-167">Es ist nicht auf Knotenebene Änderungen wie z. B. einem Serverknoten Ändern des Status berücksichtigen.</span><span class="sxs-lookup"><span data-stu-id="f581a-167">It does not factor in node-level changes such as a compute node changing state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-168">Ruft ab oder legt die maximale Anzahl von Aufgaben, die gleichzeitig auf einem einzelnen Serverknoten im Pool ausgeführt werden können.</span><span class="sxs-lookup"><span data-stu-id="f581a-168">Gets or sets the maximum number of tasks that can run concurrently on a single compute node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-169">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Pool als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f581a-169">Gets or sets a list of name-value pairs associated with the pool as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-170">Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.</span><span class="sxs-lookup"><span data-stu-id="f581a-170">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Management.Batch.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-171">Ruft ab oder legt die Netzwerkkonfiguration für den Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-171">Gets or sets the network configuration for the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of PoolProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="f581a-172">Ruft den aktuellen Status des Pools an.</span><span class="sxs-lookup"><span data-stu-id="f581a-172">Gets the current state of the pool.</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>
             <span data-ttu-id="f581a-173">Gültige Werte:</span><span class="sxs-lookup"><span data-stu-id="f581a-173">Values are:</span></span>
            
             <span data-ttu-id="f581a-174">Erfolgreich - ist Pool zum Ausführen von Aufgaben nach der Verfügbarkeit von Serverknoten verfügbar.</span><span class="sxs-lookup"><span data-stu-id="f581a-174">Succeeded - The pool is available to run tasks subject to the availability of compute nodes.</span></span>
             <span data-ttu-id="f581a-175">wird gelöscht – der Benutzer hat angefordert, dass der Pool gelöscht werden, aber der Delete-Vorgang wurde noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="f581a-175">Deleting - The user has requested that the pool be deleted, but the delete operation has not yet completed.</span></span> <span data-ttu-id="f581a-176">Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen"</span><span class="sxs-lookup"><span data-stu-id="f581a-176">Possible values include: 'Succeeded', 'Deleting'</span></span>
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-177">Ruft den Zeitpunkt, an dem der Pool seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="f581a-177">Gets the time at which the pool entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeOperationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResizeOperationStatus As ResizeOperationStatus" />
      <MemberSignature Language="F#" Value="member this.ResizeOperationStatus : Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resizeOperationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-178">Ruft enthält Details zu den aktuellen oder letzten abgeschlossenen Resize-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f581a-178">Gets contains details about the current or last completed resize operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.Batch.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-179">Abrufen oder Festlegen von Einstellungen, die die Anzahl der Knoten im Pool zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="f581a-179">Gets or sets settings which configure the number of nodes in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Management.Batch.Models.StartTask with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-180">Ermittelt oder definiert ein Task auf jeder Compute-Knoten ausgeführt wird, wie den Pool hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="f581a-180">Gets or sets a task specified to run on each compute node as it joins the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-181">In einem Patchvorgang (Update) kann diese Eigenschaft auf ein leeres Objekt festgelegt werden, die Startaufgabe aus dem Pool entfernen.</span><span class="sxs-lookup"><span data-stu-id="f581a-181">In an PATCH (update) operation, this property can be set to an empty object to remove the start task from the pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-182">Ruft ab oder legt sie fest, wie Aufgaben auf Serverknoten in einem Pool verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-182">Gets or sets how tasks are distributed across compute nodes in a pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-183">Ruft ab oder legt die Liste der Benutzerkonten auf jedem Knoten im Pool erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="f581a-183">Gets or sets the list of user accounts to be created on each node in the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f581a-184">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f581a-184">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f581a-185">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f581a-185">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f581a-186">Ruft ab oder legt die Größe der virtuellen Computer im Pool.</span><span class="sxs-lookup"><span data-stu-id="f581a-186">Gets or sets the size of virtual machines in the pool.</span></span> <span data-ttu-id="f581a-187">Alle virtuellen Computer in einem Pool haben die gleiche Größe.</span><span class="sxs-lookup"><span data-stu-id="f581a-187">All VMs in a pool are the same size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f581a-188">Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit CloudServiceConfiguration erstellt) finden Sie unter Größen für Cloud-Dienste (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span><span class="sxs-lookup"><span data-stu-id="f581a-188">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="f581a-189">Batch unterstützt alle Cloud-Dienste VM-Größen sind ExtraSmall mit Ausnahme von.</span><span class="sxs-lookup"><span data-stu-id="f581a-189">Batch supports all Cloud Services VM sizes except ExtraSmall.</span></span> <span data-ttu-id="f581a-190">Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images aus dem virtuellen Computer Marketplace (Pools mit VirtualMachineConfiguration erstellt) finden Sie unter Größen für virtuelle Maschinen (Linux) (https://azure.microsoft.com/documentation/articles/ virtuelle Maschinen-Linux-Größen /) oder Größen für virtuelle Computer (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span><span class="sxs-lookup"><span data-stu-id="f581a-190">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="f581a-191">Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</span><span class="sxs-lookup"><span data-stu-id="f581a-191">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>