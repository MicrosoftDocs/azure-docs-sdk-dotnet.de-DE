<Type Name="StartTaskInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation">
  <TypeSignature Language="C#" Value="public class StartTaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartTaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class StartTaskInformation" />
  <TypeSignature Language="F#" Value="type StartTaskInformation = class" />
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
            <span data-ttu-id="91fcb-101">Informationen über eine Startaufgabe, die auf einem Serverknoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="91fcb-101">Information about a start task running on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTaskInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.#ctor" />
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
            <span data-ttu-id="91fcb-102">Initialisiert eine neue Instanz der StartTaskInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="91fcb-102">Initializes a new instance of the StartTaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartTaskInformation (Microsoft.Azure.Batch.Protocol.Models.StartTaskState state, DateTime startTime, int retryCount, Nullable&lt;DateTime&gt; endTime = null, Nullable&lt;int&gt; exitCode = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo = null, Nullable&lt;DateTime&gt; lastRetryTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.StartTaskState state, valuetype System.DateTime startTime, int32 retryCount, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, valuetype System.Nullable`1&lt;int32&gt; exitCode, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation containerInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation failureInfo, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRetryTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; result) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.#ctor(Microsoft.Azure.Batch.Protocol.Models.StartTaskState,System.DateTime,System.Int32,System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (state As StartTaskState, startTime As DateTime, retryCount As Integer, Optional endTime As Nullable(Of DateTime) = null, Optional exitCode As Nullable(Of Integer) = null, Optional containerInfo As TaskContainerExecutionInformation = null, Optional failureInfo As TaskFailureInformation = null, Optional lastRetryTime As Nullable(Of DateTime) = null, Optional result As Nullable(Of TaskExecutionResult) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation : Microsoft.Azure.Batch.Protocol.Models.StartTaskState * DateTime * int * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation (state, startTime, retryCount, endTime, exitCode, containerInfo, failureInfo, lastRetryTime, result)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="state" Type="Microsoft.Azure.Batch.Protocol.Models.StartTaskState" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="retryCount" Type="System.Int32" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="exitCode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation" />
        <Parameter Name="failureInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation" />
        <Parameter Name="lastRetryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt;" />
      </Parameters>
      <Docs>
        <param name="state"><span data-ttu-id="91fcb-103">Der Status der Startaufgabe auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="91fcb-103">The state of the start task on the compute node.</span></span></param>
        <param name="startTime"><span data-ttu-id="91fcb-104">Der Zeitpunkt, an dem die Startaufgabe Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-104">The time at which the start task started running.</span></span></param>
        <param name="retryCount"><span data-ttu-id="91fcb-105">Die Häufigkeit, mit der der Task vom Batch-Dienst wiederholt wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-105">The number of times the task has been retried by the Batch service.</span></span></param>
        <param name="endTime"><span data-ttu-id="91fcb-106">Der Zeitpunkt, an dem die Startaufgabe nicht mehr ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="91fcb-106">The time at which the start task stopped running.</span></span></param>
        <param name="exitCode"><span data-ttu-id="91fcb-107">Der Exitcode des Programms in der Start-Task-Befehlszeile angegeben.</span><span class="sxs-lookup"><span data-stu-id="91fcb-107">The exit code of the program specified on the start task command line.</span></span></param>
        <param name="containerInfo"><span data-ttu-id="91fcb-108">Informationen über den Container, die unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="91fcb-108">Information about the container under which the task is executing.</span></span></param>
        <param name="failureInfo"><span data-ttu-id="91fcb-109">Informationen, die den Aufgabenfehler beschreibt, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="91fcb-109">Information describing the task failure, if any.</span></span></param>
        <param name="lastRetryTime"><span data-ttu-id="91fcb-110">Der letzte Zeitpunkt, zu denen eine Wiederholung des Vorgangs Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-110">The most recent time at which a retry of the task started running.</span></span></param>
        <param name="result"><span data-ttu-id="91fcb-111">Das Ergebnis der Taskausführung.</span><span class="sxs-lookup"><span data-stu-id="91fcb-111">The result of the task execution.</span></span></param>
        <summary>
            <span data-ttu-id="91fcb-112">Initialisiert eine neue Instanz der StartTaskInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="91fcb-112">Initializes a new instance of the StartTaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation ContainerInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ContainerInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerInfo As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInfo : Microsoft.Azure.Batch.Protocol.Models.TaskContainerExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ContainerInfo" />
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
            <span data-ttu-id="91fcb-113">Ruft ab oder legt Informationen über den Container unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="91fcb-113">Gets or sets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-114">Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe in einem Container-Kontext ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="91fcb-114">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.EndTime" />
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
            <span data-ttu-id="91fcb-115">Ruft ab oder legt die Zeit, an dem die Startaufgabe nicht mehr ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="91fcb-115">Gets or sets the time at which the start task stopped running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-116">Dadurch wird die Endzeit der letzten der Startaufgabe, ausgeführt, wenn, ausgeführt werden (auch wenn, die Fehler bei der Ausführung und eine Wiederholung steht aus) abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-116">This is the end time of the most recent run of the start task, if that run has completed (even if that run failed and a retry is pending).</span></span> <span data-ttu-id="91fcb-117">Dieses Element ist nicht vorhanden, wenn die Startaufgabe derzeit ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="91fcb-117">This element is not present if the start task is currently running.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.ExitCode" />
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
            <span data-ttu-id="91fcb-118">Ruft ab oder legt den Exitcode des Programms in der Befehlszeile des Start-Task angegeben.</span><span class="sxs-lookup"><span data-stu-id="91fcb-118">Gets or sets the exit code of the program specified on the start task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-119">Diese Eigenschaft wird festgelegt, nur dann, wenn die Startaufgabe in den abgeschlossenen Zustand versetzt wird.</span><span class="sxs-lookup"><span data-stu-id="91fcb-119">This property is set only if the start task is in the completed state.</span></span> <span data-ttu-id="91fcb-120">Der Exitcode für einen Prozess gibt im Allgemeinen die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert.</span><span class="sxs-lookup"><span data-stu-id="91fcb-120">In general, the exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="91fcb-121">Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet.</span><span class="sxs-lookup"><span data-stu-id="91fcb-121">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="91fcb-122">Wenn der Batch-Dienst beendet, die Startaufgabe (aufgrund eines Timeouts oder Beendigung der Benutzer über die API wird) möglicherweise jedoch einen vom Betriebssystem definierte Exitcode angezeigt.</span><span class="sxs-lookup"><span data-stu-id="91fcb-122">However, if the Batch service terminates the start task (due to timeout, or user termination via the API) you may see an operating system-defined exit code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation FailureInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.FailureInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property FailureInfo As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInfo : Microsoft.Azure.Batch.Protocol.Models.TaskFailureInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.FailureInfo" />
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
            <span data-ttu-id="91fcb-123">Ruft ab oder legt sie fest, die den Taskfehler beschreibt ggf.</span><span class="sxs-lookup"><span data-stu-id="91fcb-123">Gets or sets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-124">Diese Eigenschaft wird festgelegt, wenn der Task in den abgeschlossenen Zustand befindet und hat einen Fehler festgestellt.</span><span class="sxs-lookup"><span data-stu-id="91fcb-124">This property is set only if the task is in the completed state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.LastRetryTime" />
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
            <span data-ttu-id="91fcb-125">Abrufen oder Festlegen der letzte Zeitpunkt, zu denen eine Wiederholung des Vorgangs Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-125">Gets or sets the most recent time at which a retry of the task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-126">Dieses Element ist nur vorhanden, wenn der Vorgang wiederholt wurde (d. h. RetryCount ist ungleich null).</span><span class="sxs-lookup"><span data-stu-id="91fcb-126">This element is present only if the task was retried (i.e. retryCount is nonzero).</span></span> <span data-ttu-id="91fcb-127">Falls vorhanden, dies ist i. d. r. StartTime identisch, jedoch möglicherweise anders, wenn die Aufgabe Gründen als dem Wiederholen Sie den Vorgang neu gestartet wurde; z. B. wenn Serverknoten, während ein erneuter Versuch neu gestartet wurde, klicken Sie dann den StartTime wird aktualisiert, aber die LastRetryTime ist nicht.</span><span class="sxs-lookup"><span data-stu-id="91fcb-127">If present, this is typically the same as startTime, but may be different if the task has been restarted for reasons other than retry; for example, if the compute node was rebooted during a retry, then the startTime is updated but the lastRetryTime is not.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.Result" />
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
            <span data-ttu-id="91fcb-128">Ruft ab oder legt das Ergebnis der Taskausführung fest.</span><span class="sxs-lookup"><span data-stu-id="91fcb-128">Gets or sets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-129">Wenn der Wert "fehlgeschlagen", können die Details des Fehlers in der Eigenschaft FailureInfo gefunden werden.</span><span class="sxs-lookup"><span data-stu-id="91fcb-129">If the value is 'failed', then the details of the failure can be found in the failureInfo property.</span></span> <span data-ttu-id="91fcb-130">Folgende Werte sind möglich: "Success", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="91fcb-130">Possible values include: 'success', 'failure'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.RetryCount" />
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
            <span data-ttu-id="91fcb-131">Ruft ab oder legt die Anzahl der Häufigkeit, mit die Aufgabe vom batchdienst wiederholt wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-131">Gets or sets the number of times the task has been retried by the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-132">Aufgabe Anwendungsfehlern (Exitcode ungleich 0) werden wiederholt, vorab Verarbeitungsfehlern (der Task konnte nicht ausgeführt werden) und Upload Fehler nicht wiederholt werden.</span><span class="sxs-lookup"><span data-stu-id="91fcb-132">Task application failures (non-zero exit code) are retried, pre-processing errors (the task could not be run) and file upload errors are not retried.</span></span> <span data-ttu-id="91fcb-133">Der batchdienst wiederholt den Vorgang maximal der Größe, die durch die Einschränkungen angegeben.</span><span class="sxs-lookup"><span data-stu-id="91fcb-133">The Batch service will retry the task up to the limit specified by the constraints.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.StartTime" />
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
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91fcb-134">Ruft ab oder legt die Zeit, zu denen die Startaufgabe Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="91fcb-134">Gets or sets the time at which the start task started running.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-135">Dieser Wert wird zurückgesetzt, jedes Mal, wenn der Vorgang wiederholt oder neu gestartet wird (d. h., dies ist die letzte Zeitpunkt, an dem die Startaufgabe Ausführung gestartet wurde).</span><span class="sxs-lookup"><span data-stu-id="91fcb-135">This value is reset every time the task is restarted or retried (that is, this is the most recent time at which the start task started running).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.StartTaskState State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.StartTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As StartTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Protocol.Models.StartTaskState with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.State" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.StartTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="91fcb-136">Ruft ab oder legt den Status des Tasks "Start" auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="91fcb-136">Gets or sets the state of the start task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="91fcb-137">Folgende Werte sind möglich: "wird ausgeführt", "abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="91fcb-137">Possible values include: 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.StartTaskInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="startTaskInformation.Validate " />
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
            <span data-ttu-id="91fcb-138">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="91fcb-138">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="91fcb-139">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="91fcb-139">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>