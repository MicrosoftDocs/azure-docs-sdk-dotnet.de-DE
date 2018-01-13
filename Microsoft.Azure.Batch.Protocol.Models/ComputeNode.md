<Type Name="ComputeNode" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNode">
  <TypeSignature Language="C#" Value="public class ComputeNode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNode extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNode" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNode" />
  <TypeSignature Language="F#" Value="type ComputeNode = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c9b0-101">Compute-Knoten in der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-101">A compute node in the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-102">Initialisiert eine neue Instanz der ComputeNode-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-102">Initializes a new instance of the ComputeNode class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNode (string id = null, string url = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;DateTime&gt; lastBootTime = null, Nullable&lt;DateTime&gt; allocationTime = null, string ipAddress = null, string affinityId = null, string vmSize = null, Nullable&lt;int&gt; totalTasksRun = null, Nullable&lt;int&gt; runningTasksCount = null, Nullable&lt;int&gt; totalTasksSucceeded = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks = null, Microsoft.Azure.Batch.Protocol.Models.StartTask startTask = null, Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors = null, Nullable&lt;bool&gt; isDedicated = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string url, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; schedulingState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBootTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationTime, string ipAddress, string affinityId, string vmSize, valuetype System.Nullable`1&lt;int32&gt; totalTasksRun, valuetype System.Nullable`1&lt;int32&gt; runningTasksCount, valuetype System.Nullable`1&lt;int32&gt; totalTasksSucceeded, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; recentTasks, class Microsoft.Azure.Batch.Protocol.Models.StartTask startTask, class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation startTaskInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; certificateReferences, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; errors, valuetype System.Nullable`1&lt;bool&gt; isDedicated, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration endpointConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SchedulingState},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskInformation},Microsoft.Azure.Batch.Protocol.Models.StartTask,Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError},System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode : string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; * Microsoft.Azure.Batch.Protocol.Models.StartTask * Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNode" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNode (id, url, state, schedulingState, stateTransitionTime, lastBootTime, allocationTime, ipAddress, affinityId, vmSize, totalTasksRun, runningTasksCount, totalTasksSucceeded, recentTasks, startTask, startTaskInfo, certificateReferences, errors, isDedicated, endpointConfiguration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;" />
        <Parameter Name="schedulingState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastBootTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="affinityId" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="totalTasksRun" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="runningTasksCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="totalTasksSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="recentTasks" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Batch.Protocol.Models.StartTask" />
        <Parameter Name="startTaskInfo" Type="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" />
        <Parameter Name="certificateReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;" />
        <Parameter Name="isDedicated" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="endpointConfiguration" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="9c9b0-103">Die ID des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-103">The ID of the compute node.</span></span></param>
        <param name="url"><span data-ttu-id="9c9b0-104">Die URL des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-104">The URL of the compute node.</span></span></param>
        <param name="state"><span data-ttu-id="9c9b0-105">Der aktuelle Status des Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-105">The current state of the compute node.</span></span></param>
        <param name="schedulingState"><span data-ttu-id="9c9b0-106">Gibt an, ob der Computeknoten für die aufgabenplanung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-106">Whether the compute node is available for task scheduling.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="9c9b0-107">Der Zeitpunkt, zu dem die Serverknoten seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-107">The time at which the compute node entered its current state.</span></span></param>
        <param name="lastBootTime"><span data-ttu-id="9c9b0-108">Die Zeit, an der die Serverknoten gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-108">The time at which the compute node was started.</span></span></param>
        <param name="allocationTime"><span data-ttu-id="9c9b0-109">Der Zeitpunkt, zu dem dieser Serverknoten dem Pool zugewiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-109">The time at which this compute node was allocated to the pool.</span></span></param>
        <param name="ipAddress"><span data-ttu-id="9c9b0-110">Die IP-Adresse, die andere Serverknoten verwenden können, für die Kommunikation mit diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-110">The IP address that other compute nodes can use to communicate with this compute node.</span></span></param>
        <param name="affinityId"><span data-ttu-id="9c9b0-111">Ein Bezeichner, der für die Hinzufügen einer Aufgabe anfordern, die der Aufgabe geplant werden auf diesem Knoten übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-111">An identifier which can be passed when adding a task to request that the task be scheduled on this node.</span></span></param>
        <param name="vmSize"><span data-ttu-id="9c9b0-112">Die Größe des virtuellen Computers die Compute-Knoten gehostet.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-112">The size of the virtual machine hosting the compute node.</span></span></param>
        <param name="totalTasksRun"><span data-ttu-id="9c9b0-113">Die Gesamtanzahl der Auftragsaufgaben auf den Computeknoten abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-113">The total number of job tasks completed on the compute node.</span></span> <span data-ttu-id="9c9b0-114">Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-114">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span></param>
        <param name="runningTasksCount"><span data-ttu-id="9c9b0-115">Die Gesamtanzahl der aktuell ausgeführten Aufgaben auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-115">The total number of currently running job tasks on the compute node.</span></span> <span data-ttu-id="9c9b0-116">Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-116">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span></param>
        <param name="totalTasksSucceeded"><span data-ttu-id="9c9b0-117">Die Gesamtanzahl der Auftragsaufgaben die (mit ExitCode 0) wurde erfolgreich abgeschlossen auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-117">The total number of job tasks which completed successfully (with exitCode 0) on the compute node.</span></span>
            <span data-ttu-id="9c9b0-118">Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-118">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span></param>
        <param name="recentTasks"><span data-ttu-id="9c9b0-119">Eine Liste der Aufgaben, deren Status zuletzt geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-119">A list of tasks whose state has recently changed.</span></span></param>
        <param name="startTask"><span data-ttu-id="9c9b0-120">Der Task auf den Computeknoten ausgeführt wird, wie sie den Pool verknüpft.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-120">The task specified to run on the compute node as it joins the pool.</span></span></param>
        <param name="startTaskInfo"><span data-ttu-id="9c9b0-121">Common Language Runtime Informationen über die Ausführung des Tasks "Start" auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-121">Runtime information about the execution of the start task on the compute node.</span></span></param>
        <param name="certificateReferences"><span data-ttu-id="9c9b0-122">Die Liste der Zertifikate auf dem Computeknoten installiert.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-122">The list of certificates installed on the compute node.</span></span></param>
        <param name="errors"><span data-ttu-id="9c9b0-123">Die Liste der Fehler, die derzeit von der Computeknoten auftreten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-123">The list of errors that are currently being encountered by the compute node.</span></span></param>
        <param name="isDedicated"><span data-ttu-id="9c9b0-124">Gibt an, ob diese Computeknoten einen dedizierten Knoten ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-124">Whether this compute node is a dedicated node.</span></span> <span data-ttu-id="9c9b0-125">Wenn "false" ist der Knoten eines Knotens mit niedriger Priorität.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-125">If false, the node is a low-priority node.</span></span></param>
        <param name="endpointConfiguration"><span data-ttu-id="9c9b0-126">Die Endpunktkonfiguration für den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-126">The endpoint configuration for the compute node.</span></span></param>
        <summary>
            <span data-ttu-id="9c9b0-127">Initialisiert eine neue Instanz der ComputeNode-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-127">Initializes a new instance of the ComputeNode class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-128">Ruft ab oder legt einen Bezeichner die übergeben werden kann, wenn eine Aufgabe, um anzufordern, dass die Aufgabe geplant werden, auf diesem Knoten hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-128">Gets or sets an identifier which can be passed when adding a task to request that the task be scheduled on this node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-129">Beachten Sie, dass dies nur ein weicher Affinität ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-129">Note that this is just a soft affinity.</span></span> <span data-ttu-id="9c9b0-130">Wenn der Zielknoten ausgelastet ist oder nicht verfügbar, die zum Zeitpunkt der Task geplant ist, wird die Aufgabe an anderer Stelle geplant werden.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-130">If the target node is busy or unavailable at the time the task is scheduled, then the task will be scheduled elsewhere.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property AllocationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.AllocationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allocationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-131">Ruft ab oder legt die Zeit, zu der diese Compute-Knoten belegt wurde, an den Pool.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-131">Gets or sets the time at which this compute node was allocated to the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; CertificateReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property CertificateReferences As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.CertificateReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.CertificateReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="certificateReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-132">Ruft ab oder legt die Liste der Zertifikate auf dem Computeknoten installiert.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-132">Gets or sets the list of certificates installed on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-133">Für Serverknoten für Windows, installiert der Batch-Dienst die Zertifikate auf den angegebenen Zertifikatspeicher und den Speicherort an.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-133">For Windows compute nodes, the Batch service installs the certificates to the specified certificate store and location.</span></span> <span data-ttu-id="9c9b0-134">Für Linux-Serverknoten werden die Zertifikate gespeichert, in einem Verzeichnis in das Arbeitsverzeichnis für die Aufgabe und eine Umgebung aus, die Variable AZ_BATCH_CERTIFICATES_DIR für den Task zum Abfragen von diesem Speicherort angegeben wird.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-134">For Linux compute nodes, the certificates are stored in a directory inside the task working directory and an environment variable AZ_BATCH_CERTIFICATES_DIR is supplied to the task to query for this location.</span></span> <span data-ttu-id="9c9b0-135">Für Zertifikate mit der Sichtbarkeit der "RemoteUser" ein "Zertifikate"-Verzeichnis im Basisverzeichnis des Benutzers erstellt wird (z. B. /home/ {Benutzername} / Zertifikaten) und Zertifikate in diesem Verzeichnis abgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-135">For certificates with visibility of 'remoteUser', a 'certs' directory is created in the user's home directory (e.g., /home/{user-name}/certs) and certificates are placed in that directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndpointConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration EndpointConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property EndpointConfiguration As ComputeNodeEndpointConfiguration" />
      <MemberSignature Language="F#" Value="member this.EndpointConfiguration : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.EndpointConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endpointConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEndpointConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-136">Ruft ab oder legt die Endpunktkonfiguration für die Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-136">Gets or sets the endpoint configuration for the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of ComputeNodeError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-137">Ruft ab oder legt die Liste der Fehler, die derzeit von der Computeknoten auftreten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-137">Gets or sets the list of errors that are currently being encountered by the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-138">Ruft ab oder legt die ID des Serverknotens fest.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-138">Gets or sets the ID of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-139">Jeder Knoten, die einem Pool hinzugefügt werden, wird eine eindeutige ID zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-139">Every node that is added to a pool is assigned a unique ID.</span></span>
            <span data-ttu-id="9c9b0-140">Wenn ein Knoten aus einem Pool entfernt wird, werden alle seine lokalen Dateien gelöscht, und die ID wieder zugänglich gemacht wird und für neue Knoten wiederverwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-140">Whenever a node is removed from a pool, all of its local files are deleted, and the ID is reclaimed and could be reused for new nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-141">Ruft ab oder legt die IP-Adresse, die andere Serverknoten verwenden können, für die Kommunikation mit diesem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-141">Gets or sets the IP address that other compute nodes can use to communicate with this compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-142">Jeder Knoten, der zu einem Pool hinzugefügt wird, wird eine eindeutige IP-Adresse zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-142">Every node that is added to a pool is assigned a unique IP address.</span></span>
            <span data-ttu-id="9c9b0-143">Wenn ein Knoten aus einem Pool entfernt wird, werden alle seine lokalen Dateien gelöscht, und die IP-Adresse wieder zugänglich gemacht wird und für neue Knoten wiederverwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-143">Whenever a node is removed from a pool, all of its local files are deleted, and the IP address is reclaimed and could be reused for new nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDedicated">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDedicated { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDedicated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDedicated As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDedicated : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.IsDedicated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDedicated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-144">Ruft ab oder legt fest, ob diese Computeknoten einen dedizierten Knoten ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-144">Gets or sets whether this compute node is a dedicated node.</span></span> <span data-ttu-id="9c9b0-145">Wenn "false" ist der Knoten eines Knotens mit niedriger Priorität.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-145">If false, the node is a low-priority node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBootTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastBootTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastBootTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBootTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastBootTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.LastBootTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBootTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-146">Ruft ab oder legt die Zeit, an der die Serverknoten gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-146">Gets or sets the time at which the compute node was started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-147">Diese Eigenschaft möglicherweise nicht vorhanden, wenn der Zustand des Knotens nicht verwendbar ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-147">This property may not be present if the node state is unusable.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentTasks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; RecentTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property RecentTasks As IList(Of TaskInformation)" />
      <MemberSignature Language="F#" Value="member this.RecentTasks : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RecentTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recentTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-148">Ruft ab oder legt eine Liste der Aufgaben, deren Status zuletzt geändert wurde.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-148">Gets or sets a list of tasks whose state has recently changed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-149">Diese Eigenschaft ist nur vorhanden, wenn mindestens eine Aufgabe auf diesem Knoten ausgeführt wurde, da er dem Pool zugewiesen wurde.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-149">This property is present only if at least one task has run on this node since it was assigned to the pool.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RunningTasksCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RunningTasksCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RunningTasksCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RunningTasksCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RunningTasksCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.RunningTasksCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runningTasksCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-150">Ruft ab oder legt die Gesamtanzahl der aktuell ausgeführten Aufgaben auf den Computeknoten fest.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-150">Gets or sets the total number of currently running job tasks on the compute node.</span></span> <span data-ttu-id="9c9b0-151">Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-151">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SchedulingState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; SchedulingState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberSignature Language="VB.NET" Value="Public Property SchedulingState As Nullable(Of SchedulingState)" />
      <MemberSignature Language="F#" Value="member this.SchedulingState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.SchedulingState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="schedulingState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SchedulingState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-152">Ruft ab oder legt fest, ob der Computeknoten zum Planen von Task verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-152">Gets or sets whether the compute node is available for task scheduling.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-153">Folgende Werte sind möglich: "enabled", "disabled"</span><span class="sxs-lookup"><span data-stu-id="9c9b0-153">Possible values include: 'enabled', 'disabled'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Batch.Protocol.Models.StartTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-154">Ruft ab oder legt den Task auf den Computeknoten ausgeführt wird, wie sie den Pool verknüpft.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-154">Gets or sets the task specified to run on the compute node as it joins the pool.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTaskInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation StartTaskInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTaskInfo As StartTaskInformation" />
      <MemberSignature Language="F#" Value="member this.StartTaskInfo : Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StartTaskInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTaskInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-155">Ruft ab, oder legt Sie Laufzeitinformationen über die Ausführung des Tasks "Start" auf den Computeknoten fest.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-155">Gets or sets runtime information about the execution of the start task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of ComputeNodeState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-156">Ruft ab oder legt den aktuellen Zustand des Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-156">Gets or sets the current state of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-157">Der Knoten mit niedriger Priorität wurde unterbrochen.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-157">The low-priority node has been preempted.</span></span> <span data-ttu-id="9c9b0-158">Aufgaben, die auf den Knoten ausgeführt wurden, verhindert wurde werden neu geplant werden, wenn Sie einen anderen Knoten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-158">Tasks which were running on the node when it was pre-empted will be rescheduled when another node becomes available.</span></span> <span data-ttu-id="9c9b0-159">Folgende Werte sind möglich: "Leerlauf", "neu gestartet", "reimaging", "wird ausgeführt", "nicht verwendbar", "erstellen", "starten", "WaitingForStartTask", "StartTaskFailed", "unknown", "LeavingPool", "offline", "unterbrochen"</span><span class="sxs-lookup"><span data-stu-id="9c9b0-159">Possible values include: 'idle', 'rebooting', 'reimaging', 'running', 'unusable', 'creating', 'starting', 'waitingForStartTask', 'startTaskFailed', 'unknown', 'leavingPool', 'offline', 'preempted'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-160">Ruft ab oder legt die Zeit, zu der die Serverknoten seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-160">Gets or sets the time at which the compute node entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksRun { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksRun As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksRun : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-161">Ruft ab oder legt die Gesamtanzahl der Auftragsaufgaben auf den Computeknoten abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-161">Gets or sets the total number of job tasks completed on the compute node.</span></span> <span data-ttu-id="9c9b0-162">Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-162">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalTasksSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TotalTasksSucceeded { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TotalTasksSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalTasksSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TotalTasksSucceeded : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.TotalTasksSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalTasksSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-163">Ruft ab oder legt die Gesamtanzahl der Auftragsaufgaben die (mit ExitCode 0) wurde erfolgreich abgeschlossen auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-163">Gets or sets the total number of job tasks which completed successfully (with exitCode 0) on the compute node.</span></span> <span data-ttu-id="9c9b0-164">Dies schließt die Auftrags-Manager-Aufgaben und normale Vorgänge jedoch Auftrag Vorbereitung Auftrag freigeben, oder Starten von Aufgaben nicht.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-164">This includes Job Manager tasks and normal tasks, but not Job Preparation, Job Release or Start tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-165">Ruft ab oder legt die URL des Serverknotens fest.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-165">Gets or sets the URL of the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNode.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-166">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-166">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9c9b0-167">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9c9b0-167">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNode.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9c9b0-168">Ruft ab oder legt die Größe des virtuellen Computers die Compute-Knoten gehostet.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-168">Gets or sets the size of the virtual machine hosting the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9c9b0-169">Informationen zu den verfügbaren Größen von virtuellen Maschinen für Cloud-Dienste-Pools (Pools mit CloudServiceConfiguration erstellt) finden Sie unter Größen für Cloud-Dienste (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span><span class="sxs-lookup"><span data-stu-id="9c9b0-169">For information about available sizes of virtual machines for Cloud Services pools (pools created with cloudServiceConfiguration), see Sizes for Cloud Services (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/).</span></span>
            <span data-ttu-id="9c9b0-170">Batch unterstützt alle Cloud-Dienste-VM-Größen außer sind ExtraSmall, A1V2 und A2V2.</span><span class="sxs-lookup"><span data-stu-id="9c9b0-170">Batch supports all Cloud Services VM sizes except ExtraSmall, A1V2 and A2V2.</span></span> <span data-ttu-id="9c9b0-171">Informationen zu den verfügbaren VM-Größen für Anwendungspools, die mithilfe von Images aus dem virtuellen Computer Marketplace (Pools mit VirtualMachineConfiguration erstellt) finden Sie unter Größen für virtuelle Maschinen (Linux) (https://azure.microsoft.com/documentation/articles/ virtuelle Maschinen-Linux-Größen /) oder Größen für virtuelle Computer (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span><span class="sxs-lookup"><span data-stu-id="9c9b0-171">For information about available VM sizes for pools using images from the Virtual Machines Marketplace (pools created with virtualMachineConfiguration) see Sizes for Virtual Machines (Linux) (https://azure.microsoft.com/documentation/articles/virtual-machines-linux-sizes/) or Sizes for Virtual Machines (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/).</span></span>
            <span data-ttu-id="9c9b0-172">Batch unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).</span><span class="sxs-lookup"><span data-stu-id="9c9b0-172">Batch supports all Azure VM sizes except STANDARD_A0 and those with premium storage (STANDARD_GS, STANDARD_DS, and STANDARD_DSV2 series).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>