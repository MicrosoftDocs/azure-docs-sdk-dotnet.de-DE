<Type Name="JobPreparationTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask">
  <TypeSignature Language="C#" Value="public class JobPreparationTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPreparationTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPreparationTask" />
  <TypeSignature Language="F#" Value="type JobPreparationTask = class" />
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
            <span data-ttu-id="e0fff-101">Ein Auftrag zur Vorbereitung Task ausführen, bevor alle Aufgaben des Auftrags auf einem gegebenen Knoten zu berechnen.</span><span class="sxs-lookup"><span data-stu-id="e0fff-101">A Job Preparation task to run before any tasks of the job on any given compute node.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="e0fff-102">Auftrag zur Vorbereitung können Sie einen Serverknoten zum Ausführen von Aufgaben für den Auftrag vorbereiten.</span><span class="sxs-lookup"><span data-stu-id="e0fff-102">You can use Job Preparation to prepare a compute node to run tasks for the job.</span></span> <span data-ttu-id="e0fff-103">Auftrag zur Vorbereitung häufig ausgeführte Aktivitäten umfassen: Herunterladen von allgemeinen Ressourcendateien aller Aufgaben im Auftrag verwendet.</span><span class="sxs-lookup"><span data-stu-id="e0fff-103">Activities commonly performed in Job Preparation include: Downloading common resource files used by all the tasks in the job.</span></span> <span data-ttu-id="e0fff-104">Der Task Auftrag zur Vorbereitung kann diese allgemeine Ressourcendateien in den freigegebenen Speicherort auf den Computeknoten herunterladen.</span><span class="sxs-lookup"><span data-stu-id="e0fff-104">The Job Preparation task can download these common resource files to the shared location on the compute node.</span></span> <span data-ttu-id="e0fff-105">(AZ_BATCH_NODE_ROOT_DIR\shared), oder starten Sie einen lokalen Dienst auf den Serverknoten, damit alle Aufgaben dieses Auftrags mit ihm kommunizieren können.</span><span class="sxs-lookup"><span data-stu-id="e0fff-105">(AZ_BATCH_NODE_ROOT_DIR\shared), or starting a local service on the compute node so that all tasks of that job can communicate with it.</span></span> <span data-ttu-id="e0fff-106">Wenn der Auftrag Vorbereitung task ein Fehler auftritt (d. h. der Wiederholungsversuche vor dem Beenden mit Exitcode 0 zählen seitliches), wird der Batch nicht Aufgaben des Auftrags auf den Computeknoten ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="e0fff-106">If the Job Preparation task fails (that is, exhausts its retry count before exiting with exit code 0), Batch will not run tasks of this job on the compute node.</span></span> <span data-ttu-id="e0fff-107">Der Knoten bleibt zum Ausführen von Aufgaben des Auftrags, bis ein reimaging ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-107">The node remains ineligible to run tasks of this job until it is reimaged.</span></span> <span data-ttu-id="e0fff-108">Der Knoten aktiv bleibt und für andere Aufträge verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="e0fff-108">The node remains active and can be used for other jobs.</span></span> <span data-ttu-id="e0fff-109">Der Auftrag zur Vorbereitung-Task kann mehrere Male auf dem gleichen Computeknoten ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="e0fff-109">The Job Preparation task can run multiple times on the same compute node.</span></span> <span data-ttu-id="e0fff-110">Aus diesem Grund sollten Sie den Auftrag zur Vorbereitung-Task, um die erneute Ausführung behandeln schreiben.</span><span class="sxs-lookup"><span data-stu-id="e0fff-110">Therefore, you should write the Job Preparation task to handle re-execution.</span></span> <span data-ttu-id="e0fff-111">Wenn der Computeknoten neu gestartet wird, wird der Auftrag zur Vorbereitung Task erneut ausgeführt auf dem Knoten vor allen anderen Aufgaben des Auftrags, Planung, wenn RerunOnNodeRebootAfterSuccess auf "true" festgelegt ist oder wenn der Auftrag zur Vorbereitung Task zuvor nicht abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="e0fff-111">If the compute node is rebooted, the Job Preparation task is run again on the node before scheduling any other task of the job, if rerunOnNodeRebootAfterSuccess is true or if the Job Preparation task did not previously complete.</span></span> <span data-ttu-id="e0fff-112">Wenn der Computeknoten ein reimaging ausgeführt wird, wird der Auftrag zur Vorbereitung Task ausgeführt, erneut ausführen, bevor jede Aufgabe des Auftrags planen.</span><span class="sxs-lookup"><span data-stu-id="e0fff-112">If the compute node is reimaged, the Job Preparation task is run again before scheduling any task of the job.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor" />
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
            <span data-ttu-id="e0fff-113">Initialisiert eine neue Instanz der JobPreparationTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0fff-113">Initializes a new instance of the JobPreparationTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPreparationTask (string commandLine, string id = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; waitForSuccess = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; rerunOnNodeRebootAfterSuccess = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string commandLine, string id, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; waitForSuccess, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; rerunOnNodeRebootAfterSuccess) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask : string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask (commandLine, id, containerSettings, resourceFiles, environmentSettings, constraints, waitForSuccess, userIdentity, rerunOnNodeRebootAfterSuccess)" />
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
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="waitForSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="rerunOnNodeRebootAfterSuccess" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="commandLine"><span data-ttu-id="e0fff-114">Die Befehlszeile des Tasks "Auftrag zur Vorbereitung".</span><span class="sxs-lookup"><span data-stu-id="e0fff-114">The command line of the Job Preparation task.</span></span></param>
        <param name="id"><span data-ttu-id="e0fff-115">Eine Zeichenfolge, die den Auftrag zur Vorbereitung Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e0fff-115">A string that uniquely identifies the Job Preparation task within the job.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="e0fff-116">Die Einstellungen für den Container unter dem der Auftrag zur Vorbereitung Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-116">The settings for the container under which the Job Preparation task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="e0fff-117">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-117">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="e0fff-118">Eine Liste von umgebungsvariableneinstellungen für den Auftrag zur Vorbereitung-Task.</span><span class="sxs-lookup"><span data-stu-id="e0fff-118">A list of environment variable settings for the Job Preparation task.</span></span></param>
        <param name="constraints"><span data-ttu-id="e0fff-119">Einschränkungen, die für den Auftrag zur Vorbereitung Task gelten.</span><span class="sxs-lookup"><span data-stu-id="e0fff-119">Constraints that apply to the Job Preparation task.</span></span></param>
        <param name="waitForSuccess"><span data-ttu-id="e0fff-120">Gibt an, ob der Batch-Dienst für den Auftrag zur Vorbereitung Task erfolgreich abgeschlossen wird, vor dem Planen aller anderen Aufgaben des Auftrags auf dem Computeknoten warten soll.</span><span class="sxs-lookup"><span data-stu-id="e0fff-120">Whether the Batch service should wait for the Job Preparation task to complete successfully before scheduling any other tasks of the job on the compute node.</span></span> <span data-ttu-id="e0fff-121">Ein Auftrag zur Vorbereitung Task wurde erfolgreich abgeschlossen, wenn er mit dem Exitcode 0 beendet wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-121">A Job Preparation task has completed successfully if it exits with exit code 0.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="e0fff-122">Die Benutzeridentität, unter der der Auftrag zur Vorbereitung Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-122">The user identity under which the Job Preparation task runs.</span></span></param>
        <param name="rerunOnNodeRebootAfterSuccess"><span data-ttu-id="e0fff-123">Gibt an, ob der Batch-Dienst den Auftrag zur Vorbereitung Task solange erneut auszuführen sollte nach dem Neustart von eines Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="e0fff-123">Whether the Batch service should rerun the Job Preparation task after a compute node reboots.</span></span></param>
        <summary>
            <span data-ttu-id="e0fff-124">Initialisiert eine neue Instanz der JobPreparationTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0fff-124">Initializes a new instance of the JobPreparationTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.CommandLine" />
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
            <span data-ttu-id="e0fff-125">Ermittelt oder definiert die Befehlszeile des Tasks "Auftrag zur Vorbereitung".</span><span class="sxs-lookup"><span data-stu-id="e0fff-125">Gets or sets the command line of the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-126">Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung.</span><span class="sxs-lookup"><span data-stu-id="e0fff-126">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="e0fff-127">Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.</span><span class="sxs-lookup"><span data-stu-id="e0fff-127">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Constraints" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0fff-128">Ruft ab, oder legt ihn fest, die für den Auftrag zur Vorbereitung Task gelten Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="e0fff-128">Gets or sets constraints that apply to the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ContainerSettings" />
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
            <span data-ttu-id="e0fff-129">Ruft ab oder legt die Einstellungen für den Container unter dem der Auftrag zur Vorbereitung Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-129">Gets or sets the settings for the container under which the Job Preparation task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-130">Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="e0fff-130">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.EnvironmentSettings" />
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
            <span data-ttu-id="e0fff-131">Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für den Auftrag zur Vorbereitung-Task.</span><span class="sxs-lookup"><span data-stu-id="e0fff-131">Gets or sets a list of environment variable settings for the Job Preparation task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Id" />
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
            <span data-ttu-id="e0fff-132">Ruft ab oder legt eine Zeichenfolge, die den Auftrag zur Vorbereitung Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="e0fff-132">Gets or sets a string that uniquely identifies the Job Preparation task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-133">Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten.</span><span class="sxs-lookup"><span data-stu-id="e0fff-133">The ID can contain any combination of alphanumeric characters including hyphens and underscores and cannot contain more than 64 characters.</span></span> <span data-ttu-id="e0fff-134">Wenn Sie diese Eigenschaft nicht angeben, weist der Batch-Dienst den Standardwert "Jobpreparation".</span><span class="sxs-lookup"><span data-stu-id="e0fff-134">If you do not specify this property, the Batch service assigns a default value of 'jobpreparation'.</span></span> <span data-ttu-id="e0fff-135">Keine andere Aufgabe im Auftrag kann die gleiche ID wie der Auftrag zur Vorbereitung Task verfügen.</span><span class="sxs-lookup"><span data-stu-id="e0fff-135">No other task in the job can have the same ID as the Job Preparation task.</span></span> <span data-ttu-id="e0fff-136">Wenn Sie versuchen, eine Aufgabe mit der gleichen Id senden, lehnt Sie ab der Batch-Dienst den Fehlercode TaskIdSameAsJobPreparationTask; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 409 (Konflikt).</span><span class="sxs-lookup"><span data-stu-id="e0fff-136">If you try to submit a task with the same id, the Batch service rejects the request with error code TaskIdSameAsJobPreparationTask; if you are calling the REST API directly, the HTTP status code is 409 (Conflict).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RerunOnNodeRebootAfterSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RerunOnNodeRebootAfterSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property RerunOnNodeRebootAfterSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RerunOnNodeRebootAfterSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.RerunOnNodeRebootAfterSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="rerunOnNodeRebootAfterSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0fff-137">Ruft ab oder legt fest, ob der Batch-Dienst den Auftrag zur Vorbereitung Task solange erneut auszuführen sollte nach dem Neustart von eines Serverknotens.</span><span class="sxs-lookup"><span data-stu-id="e0fff-137">Gets or sets whether the Batch service should rerun the Job Preparation task after a compute node reboots.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-138">Der Auftrag zur Vorbereitung Task immer erneut ausgeführt, wenn ein reimaging ein Compute-Knoten ausgeführt wird oder wenn die Auftrag zur Vorbereitung Aufgabe nicht abgeschlossen wurde (z. B. weil der Neustart ist aufgetreten, während die Aufgabe ausgeführt wurde).</span><span class="sxs-lookup"><span data-stu-id="e0fff-138">The Job Preparation task is always rerun if a compute node is reimaged, or if the Job Preparation task did not complete (e.g. because the reboot occurred while the task was running).</span></span> <span data-ttu-id="e0fff-139">Aus diesem Grund sollten Sie immer einen Auftrag zur Vorbereitung Task Idempotent sein und ordnungsgemäß verhält, wenn mehrere Male ausführen schreiben.</span><span class="sxs-lookup"><span data-stu-id="e0fff-139">Therefore, you should always write a Job Preparation task to be idempotent and to behave correctly if run multiple times.</span></span> <span data-ttu-id="e0fff-140">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="e0fff-140">The default value is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.ResourceFiles" />
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
            <span data-ttu-id="e0fff-141">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.</span><span class="sxs-lookup"><span data-stu-id="e0fff-141">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-142">Unter diesem Element aufgelisteten Dateien befinden sich im Arbeitsverzeichnis für den Task.</span><span class="sxs-lookup"><span data-stu-id="e0fff-142">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.UserIdentity" />
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
            <span data-ttu-id="e0fff-143">Ruft ab oder legt die Identität des Benutzers, unter der der Auftrag zur Vorbereitung Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-143">Gets or sets the user identity under which the Job Preparation task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-144">Wenn nicht angegeben, der Task ausgeführt wird als eine eindeutige Benutzer ohne Administratorrechte für den Task auf Windows-Knoten oder ein Benutzer ohne Administratorrechte für den Pool auf Linux-Knoten eindeutig.</span><span class="sxs-lookup"><span data-stu-id="e0fff-144">If omitted, the task runs as a non-administrative user unique to the task on Windows nodes, or a a non-administrative user unique to the pool on Linux nodes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPreparationTask.Validate " />
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
            <span data-ttu-id="e0fff-145">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e0fff-145">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e0fff-146">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e0fff-146">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitForSuccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; WaitForSuccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; WaitForSuccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitForSuccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.WaitForSuccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask.WaitForSuccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitForSuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0fff-147">Ruft ab oder legt fest, ob der Batch-Dienst für den Auftrag zur Vorbereitung Task erfolgreich abgeschlossen wird, vor dem Planen aller anderen Aufgaben des Auftrags auf dem Computeknoten warten soll.</span><span class="sxs-lookup"><span data-stu-id="e0fff-147">Gets or sets whether the Batch service should wait for the Job Preparation task to complete successfully before scheduling any other tasks of the job on the compute node.</span></span> <span data-ttu-id="e0fff-148">Ein Auftrag zur Vorbereitung Task wurde erfolgreich abgeschlossen, wenn er mit dem Exitcode 0 beendet wird.</span><span class="sxs-lookup"><span data-stu-id="e0fff-148">A Job Preparation task has completed successfully if it exits with exit code 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e0fff-149">Wenn "true" und der Auftrag zur Vorbereitung Task ein Fehler auftritt, auf einen Serverknoten, wiederholt der Batch-Dienst den Auftrag zur Vorbereitung Aufgabe bis zu die maximale Anzahl von Wiederholungsversuchen (gemäß den Einschränkungen-Element).</span><span class="sxs-lookup"><span data-stu-id="e0fff-149">If true and the Job Preparation task fails on a compute node, the Batch service retries the Job Preparation task up to its maximum retry count (as specified in the constraints element).</span></span> <span data-ttu-id="e0fff-150">Wenn die Aufgabe noch nicht abgeschlossen wurde erfolgreich nachdem alle Wiederholungsversuche, und der Batch-Dienst wird nicht Planen von Aufgaben des Auftrags auf den Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="e0fff-150">If the task has still not completed successfully after all retries, then the Batch service will not schedule tasks of the job to the compute node.</span></span> <span data-ttu-id="e0fff-151">Die Serverknoten bleibt aktiv und auszuführenden Aufgaben von anderen Aufträgen geeignet.</span><span class="sxs-lookup"><span data-stu-id="e0fff-151">The compute node remains active and eligible to run tasks of other jobs.</span></span> <span data-ttu-id="e0fff-152">Wenn "false" wird der Batch-Dienst nicht für Auftrag Vorbereitung Abschluss der Aufgabe zu warten.</span><span class="sxs-lookup"><span data-stu-id="e0fff-152">If false, the Batch service will not wait for the Job Preparation task to complete.</span></span> <span data-ttu-id="e0fff-153">In diesem Fall können andere Aufgaben des Auftrags starten auf dem Computeknoten ausgeführt werden, während die Auftrag zur Vorbereitung Aufgabe noch ausgeführt wird; und auch wenn der Auftrag zur Vorbereitung Task fehlschlägt, neue Aufgaben weiterhin auf dem Knoten geplant werden.</span><span class="sxs-lookup"><span data-stu-id="e0fff-153">In this case, other tasks of the job can start executing on the compute node while the Job Preparation task is still running; and even if the Job Preparation task fails, new tasks will continue to be scheduled on the node.</span></span> <span data-ttu-id="e0fff-154">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="e0fff-154">The default value is true.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>