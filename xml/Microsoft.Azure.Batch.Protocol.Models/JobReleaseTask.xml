<Type Name="JobReleaseTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask">
  <TypeSignature Language="C#" Value="public class JobReleaseTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobReleaseTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobReleaseTask" />
  <TypeSignature Language="F#" Value="type JobReleaseTask = class" />
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
            <span data-ttu-id="017c2-101">Ein Auftrag Version der auszuführende Task nach Auftragsabschluss auf einem beliebigen Computeknoten, in dem der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="017c2-101">A Job Release task to run on job completion on any compute node where the job has run.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="017c2-102">Der Auftrag Release-Task ausgeführt wird, wenn der Auftrag beendet wird, aufgrund eines der folgenden: der Benutzer ruft API Auftrag beendet oder der Auftrags-API löschen, während der Auftrag noch aktiv ist, den Auftrag maximale Wand Uhr zeitbeschränkung erreicht ist und der Auftrag immer noch aktiv ist , oder der Auftrags-Auftrags-Manager-Aufgabe abgeschlossen und der Auftrag wird so konfiguriert, dass um nach Abschluss der Auftrags-Manager zu beenden.</span><span class="sxs-lookup"><span data-stu-id="017c2-102">The Job Release task runs when the job ends, because of one of the following: The user calls the Terminate Job API, or the Delete Job API while the job is still active, the job's maximum wall clock time constraint is reached, and the job is still active, or the job's Job Manager task completed, and the job is configured to terminate when the Job Manager completes.</span></span> <span data-ttu-id="017c2-103">Der Auftrag Version Taskausführung auf jedem Computeknoten, in dem Aufgaben des Auftrags ausgeführt wurden und der Auftrag zur Vorbereitung Task ausgeführt und abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="017c2-103">The Job Release task runs on each compute node where tasks of the job have run and the Job Preparation task ran and completed.</span></span> <span data-ttu-id="017c2-104">Wenn Sie ein reimaging, einen Serverknoten durchführen, nachdem sie den Auftrag zur Vorbereitung Task ausgeführt wurde, sodass der Auftrag beendet, ohne weitere Aufgaben des Auftrags auf, mit denen Knoten berechnet (und daher die Vorbereitung des Auftrags Aufgabe wird nicht erneut ausgeführt), wird die Auftrag Version Aufgabe nicht auf diesem Knoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="017c2-104">If you reimage a compute node after it has run the Job Preparation task, and the job ends without any further tasks of the job running on that compute node (and hence the Job Preparation task does not re-run), then the Job Release task does not run on that node.</span></span> <span data-ttu-id="017c2-105">Wenn Compute-Knoten neu gestartet, während die Aufgabe Auftrag Version noch ausgeführt wird, wird der Task Auftrag Version beim Start des Compute-Knotens erneut ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="017c2-105">If a compute node reboots while the Job Release task is still running, the Job Release task runs again when the compute node starts up.</span></span> <span data-ttu-id="017c2-106">Der Auftrag ist nicht als abgeschlossen gekennzeichnet, bis alle Aufgaben der Version des Auftrags abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="017c2-106">The job is not marked as complete until all Job Release tasks have completed.</span></span> <span data-ttu-id="017c2-107">Der Task Auftrag freigeben, die im Hintergrund ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="017c2-107">The Job Release task runs in the background.</span></span> <span data-ttu-id="017c2-108">Sie beansprucht keinen Planung Slot; d. h. es nicht für den MaxTasksPerNode-Grenzwert für den Pool angegeben gezählt.</span><span class="sxs-lookup"><span data-stu-id="017c2-108">It does not occupy a scheduling slot; that is, it does not count towards the maxTasksPerNode limit specified on the pool.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.#ctor" />
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
            <span data-ttu-id="017c2-109">Initialisiert eine neue Instanz der JobReleaseTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="017c2-109">Initializes a new instance of the JobReleaseTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobReleaseTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},Microsoft.Azure.Batch.Protocol.Models.UserIdentity)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity -&gt; Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, maxWallClockTime, retentionTime, userIdentity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="017c2-110">Die Befehlszeile des Tasks "Auftrag Release".</span><span class="sxs-lookup"><span data-stu-id="017c2-110">The command line of the Job Release task.</span></span></param>
        <param name="id"><span data-ttu-id="017c2-111">Eine Zeichenfolge, die die Version des Auftrags Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="017c2-111">A string that uniquely identifies the Job Release task within the job.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="017c2-112">Die Einstellungen für den Container unter dem der Auftrag Version Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-112">The settings for the container under which the Job Release task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="017c2-113">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-113">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="017c2-114">Eine Liste von umgebungsvariableneinstellungen für den Auftrag Version ausführen.</span><span class="sxs-lookup"><span data-stu-id="017c2-114">A list of environment variable settings for the Job Release task.</span></span></param>
        <param name="maxWallClockTime"><span data-ttu-id="017c2-115">Die maximal verstrichene Zeit, dass der Task kann die Auftrag-Release-Aufgabe auf einem bestimmten Serverknoten, gemessen ab dem Zeitpunkt ausgeführt wird gestartet.</span><span class="sxs-lookup"><span data-stu-id="017c2-115">The maximum elapsed time that the Job Release task may run on a given compute node, measured from the time the task starts.</span></span> <span data-ttu-id="017c2-116">Wenn die Aufgabe nicht innerhalb des Zeitlimits abgeschlossen wird, der Batch-Dienst beendet wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-116">If the task does not complete within the time limit, the Batch service terminates it.</span></span> <span data-ttu-id="017c2-117">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="017c2-117">The default value is 15 minutes.</span></span> <span data-ttu-id="017c2-118">Sie können nicht mehr als 15 Minuten Timeout angeben.</span><span class="sxs-lookup"><span data-stu-id="017c2-118">You may not specify a timeout longer than 15 minutes.</span></span> <span data-ttu-id="017c2-119">Wenn Sie dies tun, von der Batch-Dienst mit einem Fehler abgelehnt; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="017c2-119">If you do, the Batch service rejects it with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span></param>
        <param name="retentionTime"><span data-ttu-id="017c2-120">Das früheste für den Task-Verzeichnis für den Auftrag Version Task auf den Computeknoten beibehalten werden sollen.</span><span class="sxs-lookup"><span data-stu-id="017c2-120">The minimum time to retain the task directory for the Job Release task on the compute node.</span></span> <span data-ttu-id="017c2-121">Nach dieser Zeit kann der Batch-Dienst das Task-Verzeichnis und seinen gesamten Inhalt löschen.</span><span class="sxs-lookup"><span data-stu-id="017c2-121">After this time, the Batch service may delete the task directory and all its contents.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="017c2-122">Die Benutzeridentität, unter der der Auftrag Version Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-122">The user identity under which the Job Release task runs.</span></span></param>
        <summary>
            <span data-ttu-id="017c2-123">Initialisiert eine neue Instanz der JobReleaseTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="017c2-123">Initializes a new instance of the JobReleaseTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.CommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commandLine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-124">Ermittelt oder definiert die Befehlszeile des Tasks "Auftrag Release".</span><span class="sxs-lookup"><span data-stu-id="017c2-124">Gets or sets the command line of the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="017c2-125">Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung.</span><span class="sxs-lookup"><span data-stu-id="017c2-125">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="017c2-126">Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.</span><span class="sxs-lookup"><span data-stu-id="017c2-126">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-127">Ruft ab oder legt die Einstellungen für den Container unter dem der Auftrag Version Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-127">Gets or sets the settings for the container under which the Job Release task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="017c2-128">Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="017c2-128">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.EnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="environmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-129">Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für den Auftrag Version Task.</span><span class="sxs-lookup"><span data-stu-id="017c2-129">Gets or sets a list of environment variable settings for the Job Release task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Id" />
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
            <span data-ttu-id="017c2-130">Ruft ab oder legt eine Zeichenfolge, die die Version des Auftrags Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="017c2-130">Gets or sets a string that uniquely identifies the Job Release task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="017c2-131">Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten.</span><span class="sxs-lookup"><span data-stu-id="017c2-131">The ID can contain any combination of alphanumeric characters including hyphens and underscores and cannot contain more than 64 characters.</span></span> <span data-ttu-id="017c2-132">Wenn Sie diese Eigenschaft nicht angeben, weist der Batch-Dienst den Standardwert "Jobrelease".</span><span class="sxs-lookup"><span data-stu-id="017c2-132">If you do not specify this property, the Batch service assigns a default value of 'jobrelease'.</span></span> <span data-ttu-id="017c2-133">Keine andere Aufgabe im Auftrag kann die gleiche ID wie dem Task Auftrag freigeben verfügen.</span><span class="sxs-lookup"><span data-stu-id="017c2-133">No other task in the job can have the same ID as the Job Release task.</span></span> <span data-ttu-id="017c2-134">Wenn Sie versuchen, eine Aufgabe mit der gleichen Id senden, lehnt Sie ab der Batch-Dienst den Fehlercode TaskIdSameAsJobReleaseTask; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 409 (Konflikt).</span><span class="sxs-lookup"><span data-stu-id="017c2-134">If you try to submit a task with the same id, the Batch service rejects the request with error code TaskIdSameAsJobReleaseTask; if you are calling the REST API directly, the HTTP status code is 409 (Conflict).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-135">Ruft ab oder legt die maximale Zeitspanne, die der Task Auftrag Version werden, auf einem bestimmten Serverknoten ausgeführt kann, gemessen ab dem Zeitpunkt, den der Task beginnt.</span><span class="sxs-lookup"><span data-stu-id="017c2-135">Gets or sets the maximum elapsed time that the Job Release task may run on a given compute node, measured from the time the task starts.</span></span> <span data-ttu-id="017c2-136">Wenn die Aufgabe nicht innerhalb des Zeitlimits abgeschlossen wird, der Batch-Dienst beendet wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-136">If the task does not complete within the time limit, the Batch service terminates it.</span></span> <span data-ttu-id="017c2-137">Der Standardwert beträgt 15 Minuten.</span><span class="sxs-lookup"><span data-stu-id="017c2-137">The default value is 15 minutes.</span></span> <span data-ttu-id="017c2-138">Sie können nicht mehr als 15 Minuten Timeout angeben.</span><span class="sxs-lookup"><span data-stu-id="017c2-138">You may not specify a timeout longer than 15 minutes.</span></span> <span data-ttu-id="017c2-139">Wenn Sie dies tun, von der Batch-Dienst mit einem Fehler abgelehnt; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="017c2-139">If you do, the Batch service rejects it with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.ResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-140">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.</span><span class="sxs-lookup"><span data-stu-id="017c2-140">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="017c2-141">Unter diesem Element aufgelisteten Dateien befinden sich im Arbeitsverzeichnis für den Task.</span><span class="sxs-lookup"><span data-stu-id="017c2-141">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-142">Ruft ab oder legt das früheste für den Task-Verzeichnis für den Auftrag Version Task auf den Computeknoten beibehalten werden sollen.</span><span class="sxs-lookup"><span data-stu-id="017c2-142">Gets or sets the minimum time to retain the task directory for the Job Release task on the compute node.</span></span> <span data-ttu-id="017c2-143">Nach dieser Zeit kann der Batch-Dienst das Task-Verzeichnis und seinen gesamten Inhalt löschen.</span><span class="sxs-lookup"><span data-stu-id="017c2-143">After this time, the Batch service may delete the task directory and all its contents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="017c2-144">Die Standardeinstellung ist unendlich, d. h. das Verzeichnis Aufgabe werden beibehalten, bis die Compute-Knoten entfernt oder ein reimaging ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-144">The default is infinite, i.e. the task directory will be retained until the compute node is removed or reimaged.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.UserIdentity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userIdentity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.UserIdentity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="017c2-145">Ruft ab oder legt die Identität des Benutzers, unter der der Auftrag Version Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="017c2-145">Gets or sets the user identity under which the Job Release task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="017c2-146">Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="017c2-146">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobReleaseTask.Validate " />
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
            <span data-ttu-id="017c2-147">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="017c2-147">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="017c2-148">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="017c2-148">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>