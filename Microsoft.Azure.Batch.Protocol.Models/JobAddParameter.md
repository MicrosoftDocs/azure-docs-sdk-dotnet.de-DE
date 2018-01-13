<Type Name="JobAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter">
  <TypeSignature Language="C#" Value="public class JobAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobAddParameter" />
  <TypeSignature Language="F#" Value="type JobAddParameter = class" />
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
            <span data-ttu-id="fb27a-101">Ein hinzuzufügende Azure Batch-Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-101">An Azure Batch job to add.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.#ctor" />
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
            <span data-ttu-id="fb27a-102">Initialisiert eine neue Instanz der JobAddParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fb27a-102">Initializes a new instance of the JobAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobAddParameter (string id, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, string displayName = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Nullable&lt;bool&gt; usesTaskDependencies = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, string displayName, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.String,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobAddParameter : string * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * string * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobAddParameter (id, poolInfo, displayName, priority, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, onAllTasksComplete, onTaskFailure, metadata, usesTaskDependencies)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="fb27a-103">Eine Zeichenfolge, die den Auftrag im Konto eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="fb27a-103">A string that uniquely identifies the job within the account.</span></span></param>
        <param name="poolInfo"><span data-ttu-id="fb27a-104">Der Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="fb27a-104">The pool on which the Batch service runs the job's tasks.</span></span></param>
        <param name="displayName"><span data-ttu-id="fb27a-105">Der Anzeigename für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-105">The display name for the job.</span></span></param>
        <param name="priority"><span data-ttu-id="fb27a-106">Die Priorität des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="fb27a-106">The priority of the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="fb27a-107">Die ausführungseinschränkungen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-107">The execution constraints for the job.</span></span></param>
        <param name="jobManagerTask"><span data-ttu-id="fb27a-108">Die Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn der Auftrag gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="fb27a-108">Details of a Job Manager task to be launched when the job is started.</span></span></param>
        <param name="jobPreparationTask"><span data-ttu-id="fb27a-109">Der Auftrag zur Vorbereitung-Task.</span><span class="sxs-lookup"><span data-stu-id="fb27a-109">The Job Preparation task.</span></span></param>
        <param name="jobReleaseTask"><span data-ttu-id="fb27a-110">Der Task Auftrag freigeben.</span><span class="sxs-lookup"><span data-stu-id="fb27a-110">The Job Release task.</span></span></param>
        <param name="commonEnvironmentSettings"><span data-ttu-id="fb27a-111">Die Liste der allgemeinen umgebungsvariableneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="fb27a-111">The list of common environment variable settings.</span></span> <span data-ttu-id="fb27a-112">Diese Umgebungsvariablen sind für alle Aufgaben im Auftrag (einschließlich der Auftrags-Manager "," Auftrag zur Vorbereitung "und" Auftrag Version Aufgaben) festgelegt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-112">These environment variables are set for all tasks in the job (including the Job Manager, Job Preparation and Job Release tasks).</span></span></param>
        <param name="onAllTasksComplete"><span data-ttu-id="fb27a-113">Sollte der Batch-Dienst Maßnahmen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="fb27a-113">The action the Batch service should take when all tasks in the job are in the completed state.</span></span></param>
        <param name="onTaskFailure"><span data-ttu-id="fb27a-114">Sollte der Batch-Dienst Maßnahmen, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-114">The action the Batch service should take when any task in the job fails.</span></span></param>
        <param name="metadata"><span data-ttu-id="fb27a-115">Eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fb27a-115">A list of name-value pairs associated with the job as metadata.</span></span></param>
        <param name="usesTaskDependencies"><span data-ttu-id="fb27a-116">Gibt an, ob Aufgaben im Auftrag Abhängigkeiten untereinander definieren können.</span><span class="sxs-lookup"><span data-stu-id="fb27a-116">Whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="fb27a-117">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="fb27a-117">The default is false.</span></span></param>
        <summary>
            <span data-ttu-id="fb27a-118">Initialisiert eine neue Instanz der JobAddParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fb27a-118">Initializes a new instance of the JobAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.CommonEnvironmentSettings" />
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
            <span data-ttu-id="fb27a-119">Ruft ab oder legt die Liste der allgemeinen umgebungsvariableneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="fb27a-119">Gets or sets the list of common environment variable settings.</span></span>
            <span data-ttu-id="fb27a-120">Diese Umgebungsvariablen sind für alle Aufgaben im Auftrag (einschließlich der Auftrags-Manager "," Auftrag zur Vorbereitung "und" Auftrag Version Aufgaben) festgelegt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-120">These environment variables are set for all tasks in the job (including the Job Manager, Job Preparation and Job Release tasks).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-121">Einzelne Vorgänge können eine umgebungseinstellung, die hier angegebene durch Angabe der gleiche Name der Einstellung mit einem anderen Wert überschreiben.</span><span class="sxs-lookup"><span data-stu-id="fb27a-121">Individual tasks can override an environment setting specified here by specifying the same setting name with a different value.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Constraints" />
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
            <span data-ttu-id="fb27a-122">Ruft ab oder legt die ausführungseinschränkungen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-122">Gets or sets the execution constraints for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.DisplayName" />
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
            <span data-ttu-id="fb27a-123">Ruft ab oder legt den Anzeigenamen für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-123">Gets or sets the display name for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-124">Der Anzeigename muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.</span><span class="sxs-lookup"><span data-stu-id="fb27a-124">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Id" />
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
            <span data-ttu-id="fb27a-125">Ruft ab oder legt eine Zeichenfolge, die den Auftrag im Konto eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="fb27a-125">Gets or sets a string that uniquely identifies the job within the account.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-126">Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten.</span><span class="sxs-lookup"><span data-stu-id="fb27a-126">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span> <span data-ttu-id="fb27a-127">Die ID ist unter Beibehaltung von Groß-/Kleinschreibung und Groß-/Kleinschreibung (d. h., Sie verfügen nicht zwei IDs innerhalb eines Kontos, die sich nur in Groß-bzw. Kleinschreibung unterscheiden).</span><span class="sxs-lookup"><span data-stu-id="fb27a-127">The ID is case-preserving and case-insensitive (that is, you may not have two IDs within an account that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobManagerTask" />
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
            <span data-ttu-id="fb27a-128">Ruft ab oder legt Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn der Auftrag gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="fb27a-128">Gets or sets details of a Job Manager task to be launched when the job is started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-129">Wenn der Auftrag nicht mit eine Auftrags-Manager-Aufgabe angegeben wird, muss der Benutzer Aufgaben explizit den Auftrag hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="fb27a-129">If the job does not specify a Job Manager task, the user must explicitly add tasks to the job.</span></span> <span data-ttu-id="fb27a-130">Wenn der Auftrag eine Aufgabe des Auftrags-Manager angegeben ist, erstellt der Batch-Dienst die Auftrags-Manager-Aufgabe aus, wenn der Auftrag wird erstellt, und es versucht wird, den Auftrags-Manager-Task zu planen, bevor die Planung von anderen Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-130">If the job does specify a Job Manager task, the Batch service creates the Job Manager task when the job is created, and will try to schedule the Job Manager task before scheduling other tasks in the job.</span></span> <span data-ttu-id="fb27a-131">Typische dient zum Steuerelement und/oder Monitor auftragsausführung, z. B. durch entscheiden, welche zusätzlichen Aufgaben ausführen, die bestimmen, wann die Arbeit abgeschlossen ist. "" usw. die Auftrags-Manager-Aufgabe. (Allerdings eine Auftrags-Manager-Aufgabe wird nicht darauf beschränkt, auf diese Aktivitäten – es ist eine fully-fledged Aufgabe im System, und führen Sie die Aktionen für den Auftrag erforderlich sind.) Z. B. kann eine Auftrags-Manager-Aufgabe Downloaden einer Datei, die als Parameter angegeben, analysieren den Inhalt dieser Datei und übermitteln zusätzliche Aufgaben basierend auf diesen Inhalt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-131">The Job Manager task's typical purpose is to control and/or monitor job execution, for example by deciding what additional tasks to run, determining when the work is complete, etc. (However, a Job Manager task is not restricted to these activities - it is a fully-fledged task in the system and perform whatever actions are required for the job.) For example, a Job Manager task might download a file specified as a parameter, analyze the contents of that file and submit additional tasks based on those contents.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobPreparationTask" />
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
            <span data-ttu-id="fb27a-132">Übernimmt oder bestimmt die Vorbereitung des Auftrags-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="fb27a-132">Gets or sets the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-133">Wenn ein Auftrag eine Auftrag zur Vorbereitung-Aufgabe verfügt, wird der Batch-Dienst den Auftrag zur Vorbereitung Task vor dem Starten alle Aufgaben dieses Auftrags auf diesem Computeknoten auf einem Serverknoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-133">If a job has a Job Preparation task, the Batch service will run the Job Preparation task on a compute node before starting any tasks of that job on that compute node.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.JobReleaseTask" />
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
            <span data-ttu-id="fb27a-134">Ruft ab oder legt die Version des Auftrags fest.</span><span class="sxs-lookup"><span data-stu-id="fb27a-134">Gets or sets the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-135">Eine Aufgabe Auftrag Version kann nicht angegeben werden, ohne dass auch eine Aufgabe Auftrag zur Vorbereitung für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fb27a-135">A Job Release task cannot be specified without also specifying a Job Preparation task for the job.</span></span> <span data-ttu-id="fb27a-136">Der Batch-Dienst führt den Auftrag Release-Task auf den Serverknoten, die die Auftrag zur Vorbereitung Aufgabe ausgeführt haben.</span><span class="sxs-lookup"><span data-stu-id="fb27a-136">The Batch service runs the Job Release task on the compute nodes that have run the Job Preparation task.</span></span> <span data-ttu-id="fb27a-137">Die Hauptaufgabe des Tasks "Auftrag Release" ist zum Rückgängigmachen von Änderungen zur Berechnung von Knoten, die von der Aufgabe des Auftrags Vorbereitung vorgenommen.</span><span class="sxs-lookup"><span data-stu-id="fb27a-137">The primary purpose of the Job Release task is to undo changes to compute nodes made by the Job Preparation task.</span></span> <span data-ttu-id="fb27a-138">Beispiel-Aktivitäten sind lokale Dateien löschen oder Herunterfahren von Diensten, die im Rahmen der Vorbereitung der Auftrag gestartet wurden.</span><span class="sxs-lookup"><span data-stu-id="fb27a-138">Example activities include deleting local files, or shutting down services that were started as part of job preparation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Metadata" />
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
            <span data-ttu-id="fb27a-139">Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fb27a-139">Gets or sets a list of name-value pairs associated with the job as metadata.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-140">Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.</span><span class="sxs-lookup"><span data-stu-id="fb27a-140">The Batch service does not assign any meaning to metadata; it is solely for the use of user code.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnAllTasksComplete" />
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
            <span data-ttu-id="fb27a-141">Ruft ab oder legt fest, die Aktion der Batch-Dienst ausgeführt werden sollen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="fb27a-141">Gets or sets the action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-142">Beachten Sie, dass wenn ein Auftrag keine Aufgaben enthält, klicken Sie dann alle Vorgänge als abgeschlossen betrachtet werden.</span><span class="sxs-lookup"><span data-stu-id="fb27a-142">Note that if a job contains no tasks, then all tasks are considered complete.</span></span> <span data-ttu-id="fb27a-143">Diese Option verwendet wird daher am häufigsten mit eine Auftrags-Manager-Aufgabe. Wenn Sie automatische Auftrag beenden, ohne eine Auftrags-Manager verwenden möchten, sollte zunächst OnAllTasksComplete "NoAction" festgelegt und Auftragseigenschaften TerminateJob OnAllTasksComplete festlegen, wenn Sie fertig sind, Hinzufügen von Tasks zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="fb27a-143">This option is therefore most commonly used with a Job Manager task; if you want to use automatic job termination without a Job Manager, you should initially set onAllTasksComplete to noAction and update the job properties to set onAllTasksComplete to terminateJob once you have finished adding tasks.</span></span> <span data-ttu-id="fb27a-144">Der Standardwert ist "NoAction".</span><span class="sxs-lookup"><span data-stu-id="fb27a-144">The default is noAction.</span></span> <span data-ttu-id="fb27a-145">Folgende Werte sind möglich: 'NoAction', 'TerminateJob'</span><span class="sxs-lookup"><span data-stu-id="fb27a-145">Possible values include: 'noAction', 'terminateJob'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.OnTaskFailure" />
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
            <span data-ttu-id="fb27a-146">Ruft ab oder legt fest, die Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-146">Gets or sets the action the Batch service should take when any task in the job fails.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-147">Eine Aufgabe wird als mit fehlerhaften If hat eine FailureInfo.</span><span class="sxs-lookup"><span data-stu-id="fb27a-147">A task is considered to have failed if has a failureInfo.</span></span> <span data-ttu-id="fb27a-148">Ein FailureInfo wird festgelegt, wenn die Aufgabe mit einem Exitcode ungleich 0 (null) abgeschlossen ist, nachdem die Wiederholungsanzahl für schwellenwertbenachrichtigungen oder wenn Fehler beim Starten der Aufgabe aufgetreten ist, z. B. aufgrund einer Ressourcendatei herunterladen Fehler.</span><span class="sxs-lookup"><span data-stu-id="fb27a-148">A failureInfo is set if the task completes with a non-zero exit code after exhausting its retry count, or if there was an error starting the task, for example due to a resource file download error.</span></span> <span data-ttu-id="fb27a-149">Der Standardwert ist "NoAction".</span><span class="sxs-lookup"><span data-stu-id="fb27a-149">The default is noAction.</span></span> <span data-ttu-id="fb27a-150">Folgende Werte sind möglich: 'NoAction', 'PerformExitOptionsJobAction'</span><span class="sxs-lookup"><span data-stu-id="fb27a-150">Possible values include: 'noAction', 'performExitOptionsJobAction'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.PoolInfo" />
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
            <span data-ttu-id="fb27a-151">Abrufen oder festlegen den Pool, auf dem der Batch-Dienst den Auftrag Aufgaben ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="fb27a-151">Gets or sets the pool on which the Batch service runs the job's tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Priority" />
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
            <span data-ttu-id="fb27a-152">Ruft ab oder legt die Priorität des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="fb27a-152">Gets or sets the priority of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fb27a-153">Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität.</span><span class="sxs-lookup"><span data-stu-id="fb27a-153">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="fb27a-154">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="fb27a-154">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.UsesTaskDependencies" />
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
            <span data-ttu-id="fb27a-155">Ruft ab oder legt fest, ob die Aufgaben im Auftrag Abhängigkeiten untereinander definieren können.</span><span class="sxs-lookup"><span data-stu-id="fb27a-155">Gets or sets whether tasks in the job can define dependencies on each other.</span></span> <span data-ttu-id="fb27a-156">Der Standardwert ist false.</span><span class="sxs-lookup"><span data-stu-id="fb27a-156">The default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobAddParameter.Validate " />
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
            <span data-ttu-id="fb27a-157">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="fb27a-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="fb27a-158">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="fb27a-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>