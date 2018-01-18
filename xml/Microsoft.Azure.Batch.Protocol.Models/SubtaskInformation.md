<Type Name="SubtaskInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation">
  <TypeSignature Language="C#" Value="public class SubtaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubtaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class SubtaskInformation" />
  <TypeSignature Language="F#" Value="type SubtaskInformation = class" />
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
            <span data-ttu-id="b31a0-101">Informationen über ein Azure Batch-Teilvorgang.</span><span class="sxs-lookup"><span data-stu-id="b31a0-101">Information about an Azure Batch subtask.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubtaskInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.#ctor" />
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
            <span data-ttu-id="b31a0-102">Initialisiert eine neue Instanz der SubtaskInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b31a0-102">Initializes a new instance of the SubtaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubtaskInformation (Nullable&lt;int&gt; id = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation nodeInfo = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; id, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation nodeInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.#ctor(System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SubtaskState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.SubtaskState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As Nullable(Of Integer) = null, Optional nodeInfo As ComputeNodeInformation = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional state As Nullable(Of SubtaskState) = null, Optional stateTransitionTime As Nullable(Of DateTime) = null, Optional previousState As Nullable(Of SubtaskState) = null, Optional previousStateTransitionTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation : Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation (id, nodeInfo, startTime, endTime, exitCode, containerInfo, failureInfo, state, stateTransitionTime, previousState, previousStateTransitionTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="nodeInfo" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="b31a0-103">Die ID der Fall.</span><span class="sxs-lookup"><span data-stu-id="b31a0-103">The ID of the subtask.</span></span></param>
        <param name="nodeInfo"><span data-ttu-id="b31a0-104">Informationen zu den Compute-Knoten, auf dem die Unteraufgabe ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-104">Information about the compute node on which the subtask ran.</span></span></param>
        <param name="startTime"><span data-ttu-id="b31a0-105">Der Zeitpunkt, an dem die Unteraufgabe Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-105">The time at which the subtask started running.</span></span> <span data-ttu-id="b31a0-106">Wenn die Unteraufgabe neu gestartet oder wiederholt wurde, ist dies der letzte Zeitpunkt, zu dem die Unteraufgabe Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-106">If the subtask has been restarted or retried, this is the most recent time at which the subtask started running.</span></span></param>
        <param name="endTime"><span data-ttu-id="b31a0-107">Der Zeitpunkt, an dem die Unteraufgabe abgeschlossen war.</span><span class="sxs-lookup"><span data-stu-id="b31a0-107">The time at which the subtask completed.</span></span></param>
        <param name="exitCode"><span data-ttu-id="b31a0-108">Der Exitcode des Programms in der Befehlszeile Unteraufgabe angegeben.</span><span class="sxs-lookup"><span data-stu-id="b31a0-108">The exit code of the program specified on the subtask command line.</span></span></param>
        <param name="containerInfo"><span data-ttu-id="b31a0-109">Informationen über den Container, die unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b31a0-109">Information about the container under which the task is executing.</span></span></param>
        <param name="failureInfo"><span data-ttu-id="b31a0-110">Informationen, die den Aufgabenfehler beschreibt, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="b31a0-110">Information describing the task failure, if any.</span></span></param>
        <param name="state"><span data-ttu-id="b31a0-111">Der aktuelle Status des der Fall.</span><span class="sxs-lookup"><span data-stu-id="b31a0-111">The current state of the subtask.</span></span></param>
        <param name="stateTransitionTime"><span data-ttu-id="b31a0-112">Der Zeitpunkt, zu dem die Unteraufgabe seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="b31a0-112">The time at which the subtask entered its current state.</span></span></param>
        <param name="previousState"><span data-ttu-id="b31a0-113">Der vorherige Status des der Fall.</span><span class="sxs-lookup"><span data-stu-id="b31a0-113">The previous state of the subtask.</span></span></param>
        <param name="previousStateTransitionTime"><span data-ttu-id="b31a0-114">Die Zeit, zu der der Teilvorgang den vorherigen Zustand angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="b31a0-114">The time at which the subtask entered its previous state.</span></span></param>
        <param name="result"><span data-ttu-id="b31a0-115">Das Ergebnis der Taskausführung.</span><span class="sxs-lookup"><span data-stu-id="b31a0-115">The result of the task execution.</span></span></param>
        <summary>
            <span data-ttu-id="b31a0-116">Initialisiert eine neue Instanz der SubtaskInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b31a0-116">Initializes a new instance of the SubtaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ContainerInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-117">Ruft ab oder legt Informationen über den Container unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b31a0-117">Gets or sets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-118">Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe in einem Container-Kontext ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b31a0-118">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-119">Ruft ab oder legt die Zeit, zu der die Unteraufgabe abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-119">Gets or sets the time at which the subtask completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-120">Diese Eigenschaft wird festgelegt, nur, wenn die Unteraufgabe im Status "abgeschlossen".</span><span class="sxs-lookup"><span data-stu-id="b31a0-120">This property is set only if the subtask is in the Completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitCode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-121">Abrufen oder festlegen den Exitcode des Programms in der Befehlszeile Unteraufgabe angegeben.</span><span class="sxs-lookup"><span data-stu-id="b31a0-121">Gets or sets the exit code of the program specified on the subtask command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-122">Diese Eigenschaft wird festgelegt, nur dann, wenn die Unteraufgabe in den abgeschlossenen Zustand versetzt wird.</span><span class="sxs-lookup"><span data-stu-id="b31a0-122">This property is set only if the subtask is in the completed state.</span></span>
            <span data-ttu-id="b31a0-123">Der Exitcode für einen Prozess gibt im Allgemeinen die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert.</span><span class="sxs-lookup"><span data-stu-id="b31a0-123">In general, the exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="b31a0-124">Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet.</span><span class="sxs-lookup"><span data-stu-id="b31a0-124">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="b31a0-125">Wenn der Batch-Dienst beendet, die Unteraufgabe (aufgrund eines Timeouts oder Beendigung der Benutzer über die API wird) möglicherweise jedoch einen vom Betriebssystem definierte Exitcode angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b31a0-125">However, if the Batch service terminates the subtask (due to timeout, or user termination via the API) you may see an operating system-defined exit code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.FailureInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failureInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-126">Ruft ab oder legt sie fest, die den Taskfehler beschreibt ggf.</span><span class="sxs-lookup"><span data-stu-id="b31a0-126">Gets or sets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-127">Diese Eigenschaft wird festgelegt, wenn der Task in den abgeschlossenen Zustand befindet und hat einen Fehler festgestellt.</span><span class="sxs-lookup"><span data-stu-id="b31a0-127">This property is set only if the task is in the completed state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Id : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Id" />
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
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-128">Ruft ab oder legt die ID des dem Unteraufgabe.</span><span class="sxs-lookup"><span data-stu-id="b31a0-128">Gets or sets the ID of the subtask.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation NodeInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation NodeInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.NodeInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeInfo As ComputeNodeInformation" />
      <MemberSignature Language="F#" Value="member this.NodeInfo : Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.NodeInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-129">Abrufen oder Festlegen von Informationen zu den Compute-Knoten, auf dem die Unteraufgabe ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-129">Gets or sets information about the compute node on which the subtask ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-130">Abrufen oder festlegen den vorherigen Status des der Fall.</span><span class="sxs-lookup"><span data-stu-id="b31a0-130">Gets or sets the previous state of the subtask.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-131">Diese Eigenschaft ist nicht festgelegt werden, wenn die Unteraufgabe in seinem Ausgangszustand ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b31a0-131">This property is not set if the subtask is in its initial running state.</span></span> <span data-ttu-id="b31a0-132">Folgende Werte sind möglich: "vorbereitet", "wird ausgeführt", "abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="b31a0-132">Possible values include: 'preparing', 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-133">Ruft ab oder legt die Zeit, zu der der Teilvorgang den vorherigen Zustand angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="b31a0-133">Gets or sets the time at which the subtask entered its previous state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-134">Diese Eigenschaft ist nicht festgelegt werden, wenn die Unteraufgabe in seinem Ausgangszustand ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="b31a0-134">This property is not set if the subtask is in its initial running state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-135">Ruft ab oder legt das Ergebnis der Taskausführung fest.</span><span class="sxs-lookup"><span data-stu-id="b31a0-135">Gets or sets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-136">Wenn der Wert "fehlgeschlagen", können die Details des Fehlers in der Eigenschaft FailureInfo gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="b31a0-136">If the value is 'failed', then the details of the failure can be found in the failureInfo property.</span></span> <span data-ttu-id="b31a0-137">Folgende Werte sind möglich: "Success", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="b31a0-137">Possible values include: 'success', 'failure'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-138">Ruft ab oder legt die Zeit, zu dem die Unteraufgabe Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-138">Gets or sets the time at which the subtask started running.</span></span> <span data-ttu-id="b31a0-139">Wenn die Unteraufgabe neu gestartet oder wiederholt wurde, ist dies der letzte Zeitpunkt, zu dem die Unteraufgabe Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="b31a0-139">If the subtask has been restarted or retried, this is the most recent time at which the subtask started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of SubtaskState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.State" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.SubtaskState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b31a0-140">Ruft ab oder legt den aktuellen Zustand des der Fall.</span><span class="sxs-lookup"><span data-stu-id="b31a0-140">Gets or sets the current state of the subtask.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="b31a0-141">Folgende Werte sind möglich: "vorbereitet", "wird ausgeführt", "abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="b31a0-141">Possible values include: 'preparing', 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.StateTransitionTime" />
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
            <span data-ttu-id="b31a0-142">Ruft ab oder legt die Zeit, zu der die Unteraufgabe seinem aktuellen Status erlangt hat.</span><span class="sxs-lookup"><span data-stu-id="b31a0-142">Gets or sets the time at which the subtask entered its current state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.SubtaskInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="subtaskInformation.Validate " />
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
            <span data-ttu-id="b31a0-143">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b31a0-143">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b31a0-144">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b31a0-144">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>