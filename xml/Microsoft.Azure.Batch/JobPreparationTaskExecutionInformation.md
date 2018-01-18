<Type Name="JobPreparationTaskExecutionInformation" FullName="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobPreparationTaskExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTaskExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTaskExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobPreparationTaskExecutionInformation = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="fc4c9-101">Details über die Ausführung einer <see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask">Auftrag Preparation Task</see> auf einem Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-101">Details about the execution of a <see cref="P:Microsoft.Azure.Batch.CloudJob.JobPreparationTask">Job Preparation task</see> on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContainerInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskContainerExecutionInformation ContainerInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.ContainerInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerInformation As TaskContainerExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ContainerInformation : Microsoft.Azure.Batch.TaskContainerExecutionInformation" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.ContainerInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskContainerExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-102">Ruft Informationen über den Container unter dem die Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-102">Gets information about the container under which the task is executing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-103">Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe in einem Container-Kontext ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-103">This property is set only if the task runs in a container context.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-104">Ruft den Zeitpunkt, zu dem die Aufgabe abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-104">Gets the time at which the task completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-105">Diese Eigenschaft wird nur zurückgegeben, wenn die Aufgabe in der <see cref="F:Microsoft.Azure.Batch.Common.JobPreparationTaskState.Completed" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-105">This property is only returned if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.JobPreparationTaskState.Completed" /> state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitCode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ExitCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ExitCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.ExitCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitCode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ExitCode : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.ExitCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-106">Ruft den Exitcode des Programms angegeben, in der Befehlszeile der Aufgabe ab.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-106">Gets the exit code of the program specified on the task command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-107">Diese Eigenschaft wird nur zurückgegeben, wenn die Aufgabe in der <see cref="F:Microsoft.Azure.Batch.Common.JobPreparationTaskState.Completed" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-107">This property is only returned if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.JobPreparationTaskState.Completed" /> state.</span></span> <span data-ttu-id="fc4c9-108">Der Exitcode für einen Prozess spiegelt wider, die spezifische Konvention, die vom Anwendungsentwickler für diesen Prozess implementiert wird.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-108">The exit code for a process reflects the specific convention implemented by the application developer for that process.</span></span> <span data-ttu-id="fc4c9-109">Wenn Sie den Exitcodewert für Entscheidungen in Ihrem Code verwenden, achten Sie darauf, dass Sie wissen, dass die Exit Code Konvention, die von der Anwendungsprozess verwendet.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-109">If you use the exit code value to make decisions in your code, be sure that you know the exit code convention used by the application process.</span></span> <span data-ttu-id="fc4c9-110">Beachten Sie, dass der Exitcode von Compute Knoten ausgeführt wird, z. B. wenn ein Prozess abgebrochen wird ebenfalls generiert werden kann.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-110">Note that the exit code may also be generated by the compute node operating system, such as when a process is forcibly terminated.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FailureInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskFailureInformation FailureInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.TaskFailureInformation FailureInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.FailureInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailureInformation As TaskFailureInformation" />
      <MemberSignature Language="F#" Value="member this.FailureInformation : Microsoft.Azure.Batch.TaskFailureInformation" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.FailureInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskFailureInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-111">Ruft Informationen den Taskfehler ggf., beschreiben.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-111">Gets information describing the task failure, if any.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-112">Diese Eigenschaft wird festgelegt, nur dann, wenn die Aufgabe ist die <see cref="F:Microsoft.Azure.Batch.Common.JobPreparationTaskState.Completed" /> Status und hat einen Fehler festgestellt.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-112">This property is set only if the task is in the <see cref="F:Microsoft.Azure.Batch.Common.JobPreparationTaskState.Completed" /> state and encountered a failure.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRetryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRetryTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRetryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.LastRetryTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRetryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRetryTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.LastRetryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-113">Ruft ab, der letzte Zeitpunkt, an dem die Ausführung dieser Aufgabe vom batchdienst wiederholt wurde.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-113">Gets the most recent time at which this task's execution was retried by the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-114">Dies wird nur zurückgegeben, wenn die <see cref="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.RetryCount" /> ist nicht 0 ist.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-114">This is only returned if the <see cref="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.RetryCount" /> is not 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of TaskExecutionResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.TaskExecutionResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-115">Ruft das Ergebnis der Taskausführung ab.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-115">Gets the result of the task execution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-116">Wenn der Wert <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, und klicken Sie dann die Details des Fehlers können, in gefunden werden der <see cref="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.FailureInformation" /> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-116">If the value is <see cref="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />, then the details of the failure can be found in the <see cref="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.FailureInformation" /> property.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryCount">
      <MemberSignature Language="C#" Value="public int RetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.RetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.RetryCount : int" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.RetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-117">Ruft die Anzahl der Häufigkeit, mit die Aufgabe vom batchdienst wiederholt wurde.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-117">Gets the number of times the task has been retried by the Batch service.</span></span> <span data-ttu-id="fc4c9-118">Jedes Mal, wenn die Aufgabe mit einem Exitcode ungleich 0 (null) beendet wird, wird er einen Taskfehler angesehen.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-118">Every time the task exits with a non-zero exit code, it is deemed a task failure.</span></span> <span data-ttu-id="fc4c9-119">Der batchdienst wiederholt die Aufgabe gilt ein Grenzwert gemäß der <see cref="P:Microsoft.Azure.Batch.JobPreparationTask.Constraints" />.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-119">The Batch service will retry the task up to the limit specified by the <see cref="P:Microsoft.Azure.Batch.JobPreparationTask.Constraints" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-120">Ruft den Zeitpunkt, an dem der Task die Ausführung gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-120">Gets the time at which the task started running.</span></span> <span data-ttu-id="fc4c9-121">Beachten Sie, dass jedes Mal, wenn der Task neu gestartet wird, diesen Wert aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-121">Note that every time the task is restarted, this value is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.JobPreparationTaskState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.JobPreparationTaskState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As JobPreparationTaskState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.Azure.Batch.Common.JobPreparationTaskState" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.JobPreparationTaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-122">Ruft den aktuellen Status der Aufgabe ab.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-122">Gets the current state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fc4c9-123">Ausführen bedeutet, dass die Aufgabe gerade ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-123">Running means the task is currently running.</span></span> <span data-ttu-id="fc4c9-124">Abgeschlossen bedeutet, dass die Aufgabe abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-124">Completed means the task has completed.</span></span> <span data-ttu-id="fc4c9-125">Der Status "Completed" enthält die Groß-/Kleinschreibung, in dem die Aufgabe wurde erfolgreich mit Exitcode 0 beendet wird, sowie die Fälle, in denen das System zum Starten des Prozesses Vorgang wegen planungsfehlern oder nach zahlreiche verursacht das Wiederholungslimit erreicht wurde.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-125">The Completed state includes the case where the task exits successfully with exit code 0 and the cases where the system fails to start the task process due to scheduling errors or the retry limit has reached after numerous task failures.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectory">
      <MemberSignature Language="C#" Value="public string TaskRootDirectory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.TaskRootDirectory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRootDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectory : string" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.TaskRootDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-126">Ruft das Stammverzeichnis des Tasks "Auftrag zur Vorbereitung" auf den Computeknoten ab.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-126">Gets the root directory of the Job Preparation task on the compute node.</span></span> <span data-ttu-id="fc4c9-127">Sie können diesen Pfad verwenden, zum Abrufen von Dateien, die von der Aufgabe, wie z. B. Protokolldateien erstellt.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-127">You can use this path to retrieve files created by the task, such as log files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectoryUrl">
      <MemberSignature Language="C#" Value="public string TaskRootDirectoryUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRootDirectoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectoryUrl : string" Usage="Microsoft.Azure.Batch.JobPreparationTaskExecutionInformation.TaskRootDirectoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fc4c9-128">Ruft die URL in das Stammverzeichnis des Tasks "Auftrag zur Vorbereitung" auf den Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="fc4c9-128">Gets the URL to the root directory of the Job Preparation task on the compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>