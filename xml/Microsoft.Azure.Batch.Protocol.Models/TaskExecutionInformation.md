<Type Name="TaskExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class TaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type TaskExecutionInformation = class" />
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
            <span data-ttu-id="676e7-101">Informationen zur Ausführung einer Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="676e7-101">Information about the execution of a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.#ctor" />
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
            <span data-ttu-id="676e7-102">Initialisiert eine neue Instanz der TaskExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="676e7-102">Initializes a new instance of the TaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskExecutionInformation (int retryCount, int requeueCount, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;DateTime&gt; lastRetryTime = null, Nullable&lt;DateTime&gt; lastRequeueTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 retryCount, int32 requeueCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRetryTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRequeueTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.#ctor(System.Int32,System.Int32,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (retryCount As Integer, requeueCount As Integer, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional lastRetryTime As Nullable(Of DateTime) = null, Optional lastRequeueTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation : int * int * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation (retryCount, requeueCount, startTime, endTime, exitCode, containerInfo, failureInfo, lastRetryTime, lastRequeueTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="requeueCount" Type="System.Int32" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="lastRetryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastRequeueTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="retryCount"><span data-ttu-id="676e7-103">Die Häufigkeit, mit der der Task vom Batch-Dienst wiederholt wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-103">The number of times the task has been retried by the Batch service.</span></span></param>
        <param name="requeueCount"><span data-ttu-id="676e7-104">Die Häufigkeit, mit der der Tasks vom Batch-Dienst als Ergebnis einer Benutzeranforderung erneut in die Warteschlange gestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-104">The number of times the task has been requeued by the Batch service as the result of a user request.</span></span></param>
        <param name="startTime"><span data-ttu-id="676e7-105">Der Zeitpunkt, an dem die Ausführung des Tasks gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-105">The time at which the task started running.</span></span></param>
        <param name="endTime"><span data-ttu-id="676e7-106">Der Zeitpunkt, an dem die Ausführung des Tasks beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-106">The time at which the task completed.</span></span></param>
        <param name="exitCode"><span data-ttu-id="676e7-107">Der Exitcode des Programms in der Befehlszeile der Aufgabe angegeben.</span><span class="sxs-lookup"><span data-stu-id="676e7-107">The exit code of the program specified on the task command line.</span></span></param>
        <param name="containerInfo"><span data-ttu-id="676e7-108">Informationen über den Container, die unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="676e7-108">Information about the container under which the task is executing.</span></span></param>
        <param name="failureInfo"><span data-ttu-id="676e7-109">Informationen, die den Aufgabenfehler beschreibt, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="676e7-109">Information describing the task failure, if any.</span></span></param>
        <param name="lastRetryTime"><span data-ttu-id="676e7-110">Der letzte Zeitpunkt, zu denen eine Wiederholung des Vorgangs Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-110">The most recent time at which a retry of the task started running.</span></span></param>
        <param name="lastRequeueTime"><span data-ttu-id="676e7-111">Der letzte Zeitpunkt, an dem die Aufgabe vom batchdienst als Ergebnis einer Anforderung des Benutzers in die Warteschlange wurde hat.</span><span class="sxs-lookup"><span data-stu-id="676e7-111">The most recent time at which the task has been requeued by the Batch service as the result of a user request.</span></span></param>
        <param name="result"><span data-ttu-id="676e7-112">Das Ergebnis der Taskausführung.</span><span class="sxs-lookup"><span data-stu-id="676e7-112">The result of the task execution.</span></span></param>
        <summary>
            <span data-ttu-id="676e7-113">Initialisiert eine neue Instanz der TaskExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="676e7-113">Initializes a new instance of the TaskExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ContainerInfo" />
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
            <span data-ttu-id="676e7-114">Ruft ab oder legt Informationen über den Container unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="676e7-114">Gets or sets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-115">Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe in einem Container-Kontext ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="676e7-115">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.EndTime" />
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
            <span data-ttu-id="676e7-116">Ruft ab oder legt die Zeit, zu der die Aufgabe abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-116">Gets or sets the time at which the task completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-117">Diese Eigenschaft wird festgelegt, nur dann, wenn der Task in den Status "Completed" befindet.</span><span class="sxs-lookup"><span data-stu-id="676e7-117">This property is set only if the task is in the Completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.ExitCode" />
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
            <span data-ttu-id="676e7-118">Ruft ab oder legt den Exitcode des Programms in der Befehlszeile der Aufgabe angegeben.</span><span class="sxs-lookup"><span data-stu-id="676e7-118">Gets or sets the exit code of the program specified on the task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-119">Diese Eigenschaft wird festgelegt, nur dann, wenn der Task in den abgeschlossenen Zustand befindet.</span><span class="sxs-lookup"><span data-stu-id="676e7-119">This property is set only if the task is in the completed state.</span></span> <span data-ttu-id="676e7-120">Der Exitcode für einen Prozess gibt im Allgemeinen die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert.</span><span class="sxs-lookup"><span data-stu-id="676e7-120">In general, the exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="676e7-121">Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet.</span><span class="sxs-lookup"><span data-stu-id="676e7-121">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="676e7-122">Wenn der Batch-Dienst den Task (aufgrund eines Timeouts oder Beendigung der Benutzer über die API) beendet wird, möglicherweise jedoch einen vom Betriebssystem definierte Exitcode angezeigt.</span><span class="sxs-lookup"><span data-stu-id="676e7-122">However, if the Batch service terminates the task (due to timeout, or user termination via the API) you may see an operating system-defined exit code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.FailureInfo" />
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
            <span data-ttu-id="676e7-123">Ruft ab oder legt sie fest, die den Taskfehler beschreibt ggf.</span><span class="sxs-lookup"><span data-stu-id="676e7-123">Gets or sets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-124">Diese Eigenschaft wird festgelegt, wenn der Task in den abgeschlossenen Zustand befindet und hat einen Fehler festgestellt.</span><span class="sxs-lookup"><span data-stu-id="676e7-124">This property is set only if the task is in the completed state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRequeueTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRequeueTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRequeueTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRequeueTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRequeueTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRequeueTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRequeueTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRequeueTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="676e7-125">Abrufen oder Festlegen der letzte Zeitpunkt, an dem die Aufgabe vom batchdienst als Ergebnis einer Anforderung des Benutzers in die Warteschlange wurde hat.</span><span class="sxs-lookup"><span data-stu-id="676e7-125">Gets or sets the most recent time at which the task has been requeued by the Batch service as the result of a user request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-126">Diese Eigenschaft wird festgelegt, nur, wenn "requeuecount" ungleich NULL ist.</span><span class="sxs-lookup"><span data-stu-id="676e7-126">This property is set only if the requeueCount is nonzero.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.LastRetryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRetryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="676e7-127">Abrufen oder Festlegen der letzte Zeitpunkt, zu denen eine Wiederholung des Vorgangs Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-127">Gets or sets the most recent time at which a retry of the task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-128">Dieses Element ist nur vorhanden, wenn der Vorgang wiederholt wurde (d. h. RetryCount ist ungleich null).</span><span class="sxs-lookup"><span data-stu-id="676e7-128">This element is present only if the task was retried (i.e. retryCount is nonzero).</span></span> <span data-ttu-id="676e7-129">Falls vorhanden, dies ist i. d. r. StartTime identisch, jedoch möglicherweise anders, wenn die Aufgabe Gründen als dem Wiederholen Sie den Vorgang neu gestartet wurde; z. B. wenn Serverknoten, während ein erneuter Versuch neu gestartet wurde, klicken Sie dann den StartTime wird aktualisiert, aber die LastRetryTime ist nicht.</span><span class="sxs-lookup"><span data-stu-id="676e7-129">If present, this is typically the same as startTime, but may be different if the task has been restarted for reasons other than retry; for example, if the compute node was rebooted during a retry, then the startTime is updated but the lastRetryTime is not.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RequeueCount">
      <MemberSignature Language="C#" Value="public int RequeueCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RequeueCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RequeueCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RequeueCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RequeueCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RequeueCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="requeueCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="676e7-130">Ruft ab oder legt die Anzahl der Häufigkeit, mit die Aufgabe vom batchdienst als Ergebnis einer Anforderung des Benutzers in die Warteschlange wurde hat.</span><span class="sxs-lookup"><span data-stu-id="676e7-130">Gets or sets the number of times the task has been requeued by the Batch service as the result of a user request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-131">Wenn die Benutzer entfernt einen Knoten aus einem Pool (durch Ändern der Größe von/Verkleinern des Pools) oder wenn der Auftrag deaktiviert wird, kann der Benutzer angeben, dass auf den Knoten ausgeführter tasks werden in die Warteschlange für die Ausführung.</span><span class="sxs-lookup"><span data-stu-id="676e7-131">When the user removes nodes from a pool (by resizing/shrinking the pool) or when the job is being disabled, the user can specify that running tasks on the nodes be requeued for execution.</span></span> <span data-ttu-id="676e7-132">Dieser Zähler überwacht, wie oft der Task aus diesen Gründen in die Warteschlange gestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-132">This count tracks how many times the task has been requeued for these reasons.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.Result" />
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
            <span data-ttu-id="676e7-133">Ruft ab oder legt das Ergebnis der Taskausführung fest.</span><span class="sxs-lookup"><span data-stu-id="676e7-133">Gets or sets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-134">Wenn der Wert "fehlgeschlagen", können die Details des Fehlers in der Eigenschaft FailureInfo gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="676e7-134">If the value is 'failed', then the details of the failure can be found in the failureInfo property.</span></span> <span data-ttu-id="676e7-135">Folgende Werte sind möglich: "Success", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="676e7-135">Possible values include: 'success', 'failure'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="676e7-136">Ruft ab oder legt die Anzahl der Häufigkeit, mit die Aufgabe vom batchdienst wiederholt wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-136">Gets or sets the number of times the task has been retried by the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-137">Aufgabe Anwendungsfehlern (Exitcode ungleich 0) werden wiederholt, vorab Verarbeitungsfehlern (der Task konnte nicht ausgeführt werden) und Upload Fehler nicht wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="676e7-137">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="676e7-138">Der batchdienst wiederholt den Vorgang maximal der Größe, die durch die Einschränkungen angegeben.</span><span class="sxs-lookup"><span data-stu-id="676e7-138">The Batch service will retry the task up to the limit specified by the constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.StartTime" />
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
            <span data-ttu-id="676e7-139">Ruft ab oder legt die Zeit, an dem der Task die Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-139">Gets or sets the time at which the task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="676e7-140">"Ausführen" in den Ausführungsstatus entspricht, also, wenn die Aufgabe Ressourcendateien oder Anwendungspakete, wird die Startzeit gibt die Zeit, zu dem der Task begonnen hat, herunterladen oder bereitstellen, diese, widerspiegelt.</span><span class="sxs-lookup"><span data-stu-id="676e7-140">'Running' corresponds to the running state, so if the task specifies resource files or application packages, then the start time reflects the time at which the task started downloading or deploying these.</span></span> <span data-ttu-id="676e7-141">Wenn der Task neu gestartet oder wiederholt wurde, ist dies der letzte Zeitpunkt, an dem die Ausführung des Tasks gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="676e7-141">If the task has been restarted or retried, this is the most recent time at which the task started running.</span></span> <span data-ttu-id="676e7-142">Diese Eigenschaft ist nur für Aufgaben, die im laufenden oder abgeschlossenen Zustand befinden.</span><span class="sxs-lookup"><span data-stu-id="676e7-142">This property is present only for tasks that are in the running or completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskExecutionInformation.Validate " />
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
            <span data-ttu-id="676e7-143">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="676e7-143">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="676e7-144">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="676e7-144">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>