<Type Name="JobSpecification" FullName="Microsoft.Azure.Batch.Protocol.Models.JobSpecification">
  <TypeSignature Language="C#" Value="public class JobSpecification" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobSpecification extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobSpecification" />
  <TypeSignature Language="VB.NET" Value="Public Class JobSpecification" />
  <TypeSignature Language="F#" Value="type JobSpecification = class" />
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
            <span data-ttu-id="762c1-101">Gibt die Details der Aufträge nach einem Zeitplan erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="762c1-101">Specifies details of the jobs to be created on a schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.#ctor" />
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
            <span data-ttu-id="762c1-102">Initialisiert eine neue Instanz der Klasse jobspecification wirken.</span><span class="sxs-lookup"><span data-stu-id="762c1-102">Initializes a new instance of the JobSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobSpecification (Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, Nullable&lt;int&gt; priority = null, string displayName = null, Nullable&lt;bool&gt; usesTaskDependencies = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, valuetype System.Nullable`1&lt;int32&gt; priority, string displayName, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.#ctor(Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Nullable{System.Int32},System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobSpecification : Microsoft.Azure.Batch.Protocol.Models.PoolInformation * Nullable&lt;int&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSpecification" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobSpecification (poolInfo, priority, displayName, usesTaskDependencies, onAllTasksComplete, onTaskFailure, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="poolInfo"><span data-ttu-id="762c1-103">Der Pool, auf dem die Aufgaben der Aufträge, die unter diesem Zeitplan erstellt der Batch-Dienst ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="762c1-103">The pool on which the Batch service runs the tasks of jobs created under this schedule.</span></span></param>
        <param name="priority"><span data-ttu-id="762c1-104">Die Priorität der Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-104">The priority of jobs created under this schedule.</span></span></param>
        <param name="displayName"><span data-ttu-id="762c1-105">Der Anzeigename für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-105">The display name for jobs created under this schedule.</span></span></param>
        <param name="usesTaskDependencies"><span data-ttu-id="762c1-106">Gibt an, ob Aufgaben im Auftrag Abhängigkeiten untereinander definieren können.</span><span class="sxs-lookup"><span data-stu-id="762c1-106">Whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="762c1-107">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="762c1-107">The default is false.</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="762c1-108">Sollte der Batch-Dienst Maßnahmen, wenn alle Aufgaben in einem Auftrag unter diesem Zeitplan erstellt in den Zustand abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="762c1-108">The action the Batch service should take when all tasks in a job created under this schedule are in the completed state.</span></span></param>
        <param name="onTaskFailure"><span data-ttu-id="762c1-109">Sollte der Batch-Dienst Maßnahmen, wenn ein Task, in einem Auftrag unter diesem Zeitplan erstellt fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="762c1-109">The action the Batch service should take when any task fails in a job created under this schedule.</span></span> <span data-ttu-id="762c1-110">Eine Aufgabe gilt als fehlgeschlagen betrachtet, wenn diese fehlgeschlagen sind, wenn eine FailureInfo hat.</span><span class="sxs-lookup"><span data-stu-id="762c1-110">A task is considered to have failed if it have failed if has a failureInfo.</span></span> <span data-ttu-id="762c1-111">Ein FailureInfo wird festgelegt, wenn die Aufgabe mit einem Exitcode ungleich 0 (null) abgeschlossen ist, nachdem die Wiederholungsanzahl für schwellenwertbenachrichtigungen oder wenn Fehler beim Starten der Aufgabe aufgetreten ist, z. B. aufgrund einer Ressourcendatei herunterladen Fehler.</span><span class="sxs-lookup"><span data-stu-id="762c1-111">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span></param>
        <param name="constraints"><span data-ttu-id="762c1-112">Die ausführungseinschränkungen für Aufträge, die unter diesem Zeitplan erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="762c1-112">The execution constraints for jobs created under this schedule.</span></span></param>
        <param name="jobManagerTask"><span data-ttu-id="762c1-113">Die Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn ein Auftrag unter diesem Zeitplan gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="762c1-113">The details of a Job Manager task to be launched when a job is started under this schedule.</span></span></param>
        <param name="jobPreparationTask"><span data-ttu-id="762c1-114">Der Auftrag zur Vorbereitung Task für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-114">The Job Preparation task for jobs created under this schedule.</span></span></param>
        <param name="jobReleaseTask"><span data-ttu-id="762c1-115">Der Auftrag Version Task für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-115">The Job Release task for jobs created under this schedule.</span></span></param>
        <param name="commonEnvironmentSettings"><span data-ttu-id="762c1-116">Eine Liste der allgemeinen umgebungsvariableneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="762c1-116">A list of common environment variable settings.</span></span> <span data-ttu-id="762c1-117">Diese Umgebungsvariablen sind für alle Vorgänge im unter diesen Zeitplan (u. a. die Auftrags-Manager, Auftrag zur Vorbereitung und Auftrag Release-Tasks) erstellten Aufträge festlegen.</span><span class="sxs-lookup"><span data-stu-id="762c1-117">These environment variables are set for all tasks in jobs created under this schedule (including the Job Manager, Job Preparation and Job Release tasks).</span></span></param>
        <param name="metadata"><span data-ttu-id="762c1-118">Eine Liste von Name / Wert-Paaren, die jeden Auftrag erstellt, die unter diesem Plan als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="762c1-118">A list of name-value pairs associated with each job created under this schedule as metadata.</span></span></param>
        <summary>
            <span data-ttu-id="762c1-119">Initialisiert eine neue Instanz der Klasse jobspecification wirken.</span><span class="sxs-lookup"><span data-stu-id="762c1-119">Initializes a new instance of the JobSpecification class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonEnvironmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-120">Ruft ab oder legt eine Liste der allgemeinen umgebungsvariableneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="762c1-120">Gets or sets a list of common environment variable settings.</span></span> <span data-ttu-id="762c1-121">Diese Umgebungsvariablen sind für alle Vorgänge im unter diesen Zeitplan (u. a. die Auftrags-Manager, Auftrag zur Vorbereitung und Auftrag Release-Tasks) erstellten Aufträge festlegen.</span><span class="sxs-lookup"><span data-stu-id="762c1-121">These environment variables are set for all tasks in jobs created under this schedule (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-122">Einzelne Vorgänge können eine umgebungseinstellung, die hier angegebene durch Angabe der gleiche Name der Einstellung mit einem anderen Wert überschreiben.</span><span class="sxs-lookup"><span data-stu-id="762c1-122">Individual tasks can override an environment setting specified here by specifying the same setting name with a different value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-123">Ermittelt oder definiert die ausführungseinschränkungen für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-123">Gets or sets the execution constraints for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-124">Ruft ab oder legt den Anzeigenamen für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-124">Gets or sets the display name for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-125">Der Name muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.</span><span class="sxs-lookup"><span data-stu-id="762c1-125">The name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobManagerTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-126">Ruft ab oder legt die Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn ein Auftrag unter diesem Zeitplan gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="762c1-126">Gets or sets the details of a Job Manager task to be launched when a job is started under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-127">Wenn der Auftrag nicht mit eine Auftrags-Manager-Aufgabe angegeben wird, muss der Benutzer Aufgaben explizit den Auftrag mit der Task-API hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="762c1-127">If the job does not specify a Job Manager task, the user must explicitly add tasks to the job using the Task API.</span></span> <span data-ttu-id="762c1-128">Wenn der Auftrag eine Aufgabe des Auftrags-Manager angegeben ist, erstellt der Batch-Dienst die Auftrags-Manager-Aufgabe aus, wenn der Auftrag wird erstellt, und es versucht wird, den Auftrags-Manager-Task zu planen, bevor die Planung von anderen Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="762c1-128">If the job does specify a Job Manager task, the Batch service creates the Job Manager task when the job is created, and will try to schedule the Job Manager task before scheduling other tasks in the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobPreparationTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-129">Ruft ab, oder legt ihn fest Aufgabe Auftrag zur Vorbereitung für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-129">Gets or sets the Job Preparation task for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-130">Wenn ein Auftrag eine Auftrag zur Vorbereitung-Aufgabe verfügt, wird der Batch-Dienst den Auftrag zur Vorbereitung Task vor dem Starten alle Aufgaben dieses Auftrags auf diesem Computeknoten auf einem Serverknoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="762c1-130">If a job has a Job Preparation task, the Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobReleaseTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-131">Ruft ab, oder legt ihn fest Auftrag Version Aufgabe für Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-131">Gets or sets the Job Release task for jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-132">Die Hauptaufgabe des Tasks "Auftrag Release" ist zum Rückgängigmachen von Änderungen zur Berechnung von Knoten, die von der Aufgabe des Auftrags Vorbereitung vorgenommen.</span><span class="sxs-lookup"><span data-stu-id="762c1-132">The primary purpose of the Job Release task is to undo changes to compute nodes made by the Job Preparation task.</span></span> <span data-ttu-id="762c1-133">Beispiel-Aktivitäten sind lokale Dateien löschen oder Herunterfahren von Diensten, die im Rahmen der Vorbereitung der Auftrag gestartet wurden.</span><span class="sxs-lookup"><span data-stu-id="762c1-133">Example activities include deleting local files, or shutting down services that were started as part of job preparation.</span></span> <span data-ttu-id="762c1-134">Eine Aufgabe Auftrag Version kann nicht angegeben werden, ohne dass auch eine Aufgabe Auftrag zur Vorbereitung für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="762c1-134">A Job Release task cannot be specified without also specifying a Job Preparation task for the job.</span></span> <span data-ttu-id="762c1-135">Der Batch-Dienst führt den Auftrag Release-Task auf den Serverknoten, die die Auftrag zur Vorbereitung Aufgabe ausgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="762c1-135">The Batch service runs the Job Release task on the compute nodes that have run the Job Preparation task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-136">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die jeden Auftrag erstellt, die unter diesem Plan als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="762c1-136">Gets or sets a list of name-value pairs associated with each job created under this schedule as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-137">Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.</span><span class="sxs-lookup"><span data-stu-id="762c1-137">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-138">Ruft ab oder legt fest, die Aktion der Batch-Dienst ausgeführt werden sollen, wenn alle Aufgaben in einem Auftrag unter diesem Zeitplan erstellt in den Zustand abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="762c1-138">Gets or sets the action the Batch service should take when all tasks in a job created under this schedule are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-139">Beachten Sie, dass wenn ein Auftrag keine Aufgaben enthält, klicken Sie dann alle Vorgänge als abgeschlossen betrachtet werden.</span><span class="sxs-lookup"><span data-stu-id="762c1-139">Note that if a job contains no tasks, then all tasks are considered complete.</span></span> <span data-ttu-id="762c1-140">Diese Option verwendet wird daher am häufigsten mit eine Auftrags-Manager-Aufgabe. Wenn Sie automatische Auftrag beenden, ohne eine Auftrags-Manager verwenden möchten, sollte zunächst OnAllTasksComplete "NoAction" festgelegt und Auftragseigenschaften TerminateJob OnAllTasksComplete festlegen, wenn Sie fertig sind, Hinzufügen von Tasks zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="762c1-140">This option is therefore most commonly used with a Job Manager task; if you want to use automatic job termination without a Job Manager, you should initially set onAllTasksComplete to noAction and update the job properties to set onAllTasksComplete to terminateJob once you have finished adding tasks.</span></span> <span data-ttu-id="762c1-141">Der Standardwert ist "NoAction".</span><span class="sxs-lookup"><span data-stu-id="762c1-141">The default is noAction.</span></span> <span data-ttu-id="762c1-142">Folgende Werte sind möglich: 'NoAction', 'TerminateJob'</span><span class="sxs-lookup"><span data-stu-id="762c1-142">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onTaskFailure")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-143">Ruft ab oder legt fest, die Aktion der Batch-Dienst ausgeführt werden sollen, wenn ein Task, in einem Auftrag unter diesem Zeitplan erstellt fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="762c1-143">Gets or sets the action the Batch service should take when any task fails in a job created under this schedule.</span></span> <span data-ttu-id="762c1-144">Eine Aufgabe gilt als fehlgeschlagen betrachtet, wenn diese fehlgeschlagen sind, wenn eine FailureInfo hat.</span><span class="sxs-lookup"><span data-stu-id="762c1-144">A task is considered to have failed if it have failed if has a failureInfo.</span></span> <span data-ttu-id="762c1-145">Ein FailureInfo wird festgelegt, wenn die Aufgabe mit einem Exitcode ungleich 0 (null) abgeschlossen ist, nachdem die Wiederholungsanzahl für schwellenwertbenachrichtigungen oder wenn Fehler beim Starten der Aufgabe aufgetreten ist, z. B. aufgrund einer Ressourcendatei herunterladen Fehler.</span><span class="sxs-lookup"><span data-stu-id="762c1-145">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-146">Der Standardwert ist "NoAction".</span><span class="sxs-lookup"><span data-stu-id="762c1-146">The default is noAction.</span></span> <span data-ttu-id="762c1-147">Folgende Werte sind möglich: 'NoAction', 'PerformExitOptionsJobAction'</span><span class="sxs-lookup"><span data-stu-id="762c1-147">Possible values include: 'noAction', 'performExitOptionsJobAction'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-148">Abrufen oder festlegen den Pool, auf dem die Aufgaben der Aufträge, die unter diesem Zeitplan erstellt der Batch-Dienst ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="762c1-148">Gets or sets the pool on which the Batch service runs the tasks of jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-149">Ruft ab oder legt die Priorität der Aufträge, die unter diesem Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="762c1-149">Gets or sets the priority of jobs created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="762c1-150">Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität.</span><span class="sxs-lookup"><span data-stu-id="762c1-150">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="762c1-151">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="762c1-151">The default value is 0.</span></span> <span data-ttu-id="762c1-152">Die Priorität wird als Standard für alle Aufträge in der der Auftragszeitplan verwendet.</span><span class="sxs-lookup"><span data-stu-id="762c1-152">This priority is used as the default for all jobs under the job schedule.</span></span> <span data-ttu-id="762c1-153">Sie können die Priorität eines Auftrags aktualisieren, nachdem sie mithilfe der Aktualisierungsauftrag API erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="762c1-153">You can update a job's priority after it has been created using by using the update job API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobSpecification.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usesTaskDependencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="762c1-154">Ruft ab oder legt fest, ob die Aufgaben im Auftrag Abhängigkeiten untereinander definieren können.</span><span class="sxs-lookup"><span data-stu-id="762c1-154">Gets or sets whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="762c1-155">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="762c1-155">The default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobSpecification.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobSpecification.Validate " />
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
            <span data-ttu-id="762c1-156">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="762c1-156">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="762c1-157">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="762c1-157">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>