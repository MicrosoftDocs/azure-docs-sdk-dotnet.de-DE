<Type Name="JobManagerTask" FullName="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask">
  <TypeSignature Language="C#" Value="public class JobManagerTask" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobManagerTask extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
  <TypeSignature Language="VB.NET" Value="Public Class JobManagerTask" />
  <TypeSignature Language="F#" Value="type JobManagerTask = class" />
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
            <span data-ttu-id="17253-101">Gibt Details einer Auftrags-Manager-Aufgabe an.</span><span class="sxs-lookup"><span data-stu-id="17253-101">Specifies details of a Job Manager task.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="17253-102">Die Auftrags-Manager-Aufgabe wird automatisch gestartet, wenn der Auftrag erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-102">The Job Manager task is automatically started when the job is created.</span></span>
            <span data-ttu-id="17253-103">Der Batch-Dienst versucht, die Auftrags-Manager-Aufgabe vor alle anderen Aufgaben im Auftrag zu planen.</span><span class="sxs-lookup"><span data-stu-id="17253-103">The Batch service tries to schedule the Job Manager task before any other tasks in the job.</span></span> <span data-ttu-id="17253-104">Wenn ein Pool verkleinert wird, versucht der Batch-Dienst Serverknoten beizubehalten, Auftrags-Manager-Aufgaben ausgeführt werden, so lange als möglich (d. h. Knoten ausgeführten 'normale' Aufgaben vor dem Knoten ausgeführten Auftrags-Manager-Tasks entfernt werden).</span><span class="sxs-lookup"><span data-stu-id="17253-104">When shrinking a pool, the Batch service tries to preserve compute nodes where Job Manager tasks are running for as long as possible (that is, nodes running 'normal' tasks are removed before nodes running Job Manager tasks).</span></span> <span data-ttu-id="17253-105">Wenn eine Auftrags-Manager-Aufgabe fehlschlägt und neu gestartet werden muss, versucht das System mit der höchsten Priorität zu planen.</span><span class="sxs-lookup"><span data-stu-id="17253-105">When a Job Manager task fails and needs to be restarted, the system tries to schedule it at the highest priority.</span></span> <span data-ttu-id="17253-106">Wenn keine im Leerlauf Knoten vorhanden sind, kann das System Beenden eines aktiven Aufgaben im Pool und an die Warteschlange zurückgegeben werden, um Platz für die Auftrags-Manager-Aufgabe, neu zu starten.</span><span class="sxs-lookup"><span data-stu-id="17253-106">If there are no idle nodes available, the system may terminate one of the running tasks in the pool and return it to the queue in order to make room for the Job Manager task to restart.</span></span> <span data-ttu-id="17253-107">Beachten Sie, dass eine Auftrags-Manager-Aufgabe in einem Auftrag keine Priorität über Aufgaben in anderen Aufträgen verfügt.</span><span class="sxs-lookup"><span data-stu-id="17253-107">Note that a Job Manager task in one job does not have priority over tasks in other jobs.</span></span> <span data-ttu-id="17253-108">Über Aufträge hinweg werden nur Prioritäten auf Auftragsebene berücksichtigt.</span><span class="sxs-lookup"><span data-stu-id="17253-108">Across jobs, only job level priorities are observed.</span></span> <span data-ttu-id="17253-109">Z. B. wenn ein Auftrags-Manager in einem Auftrag Priorität 0 neu gestartet werden muss, wird es nicht Aufgaben eines Auftrags Priorität 1 versetzen.</span><span class="sxs-lookup"><span data-stu-id="17253-109">For example, if a Job Manager in a priority 0 job needs to be restarted, it will not displace tasks of a priority 1 job.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.#ctor" />
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
            <span data-ttu-id="17253-110">Initialisiert eine neue Instanz der JobManagerTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17253-110">Initializes a new instance of the JobManagerTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobManagerTask (string id, string commandLine, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Nullable&lt;bool&gt; killJobOnCompletion = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Nullable&lt;bool&gt; runExclusive = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null, Nullable&lt;bool&gt; allowLowPriorityNode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine, string displayName, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, valuetype System.Nullable`1&lt;bool&gt; killJobOnCompletion, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, valuetype System.Nullable`1&lt;bool&gt; runExclusive, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings, valuetype System.Nullable`1&lt;bool&gt; allowLowPriorityNode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.UserIdentity,System.Nullable{System.Boolean},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings,System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobManagerTask : string * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobManagerTask (id, commandLine, displayName, containerSettings, resourceFiles, outputFiles, environmentSettings, constraints, killJobOnCompletion, userIdentity, runExclusive, applicationPackageReferences, authenticationTokenSettings, allowLowPriorityNode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="commandLine" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="killJobOnCompletion" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="runExclusive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
        <Parameter Name="allowLowPriorityNode" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="17253-111">Eine Zeichenfolge, die die Auftrags-Manager-Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="17253-111">A string that uniquely identifies the Job Manager task within the job.</span></span></param>
        <param name="commandLine"><span data-ttu-id="17253-112">Die Befehlszeile der Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="17253-112">The command line of the Job Manager task.</span></span></param>
        <param name="displayName"><span data-ttu-id="17253-113">Der Anzeigename der Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="17253-113">The display name of the Job Manager task.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="17253-114">Die Einstellungen für den Container unter dem die Auftrags-Manager-Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-114">The settings for the container under which the Job Manager task runs.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="17253-115">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="17253-115">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="outputFiles"><span data-ttu-id="17253-116">Eine Liste der Dateien, die der Batch-Dienst nach dem Ausführen der Befehlszeile aus dem Computeknoten hochladen.</span><span class="sxs-lookup"><span data-stu-id="17253-116">A list of files that the Batch service will upload from the compute node after running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="17253-117">Eine Liste von umgebungsvariableneinstellungen für die Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="17253-117">A list of environment variable settings for the Job Manager task.</span></span></param>
        <param name="constraints"><span data-ttu-id="17253-118">Einschränkungen, die für die Auftrags-Manager-Aufgabe gelten.</span><span class="sxs-lookup"><span data-stu-id="17253-118">Constraints that apply to the Job Manager task.</span></span></param>
        <param name="killJobOnCompletion"><span data-ttu-id="17253-119">Gibt an, ob der Auftrags-Manager-Task abgeschlossen Abschluss des gesamten Auftrags gibt.</span><span class="sxs-lookup"><span data-stu-id="17253-119">Whether completion of the Job Manager task signifies completion of the entire job.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="17253-120">Die Benutzeridentität, unter der die Auftrags-Manager-Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-120">The user identity under which the Job Manager task runs.</span></span></param>
        <param name="runExclusive"><span data-ttu-id="17253-121">Gibt an, ob der Auftrags-Manager-Task exklusive Verwendung des Serverknotens erfordert, in dem er ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-121">Whether the Job Manager task requires exclusive use of the compute node where it runs.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="17253-122">Eine Liste der Anwendungspakete, die der Batch-Dienst vor dem Ausführen der Befehlszeile auf den Serverknoten bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="17253-122">A list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span></param>
        <param name="authenticationTokenSettings"><span data-ttu-id="17253-123">Die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</span><span class="sxs-lookup"><span data-stu-id="17253-123">The settings for an authentication token that the task can use to perform Batch service operations.</span></span></param>
        <param name="allowLowPriorityNode"><span data-ttu-id="17253-124">Gibt an, ob die Auftrags-Manager-Aufgabe auf einem Serverknoten mit niedriger Priorität führen kann.</span><span class="sxs-lookup"><span data-stu-id="17253-124">Whether the Job Manager task may run on a low-priority compute node.</span></span></param>
        <summary>
            <span data-ttu-id="17253-125">Initialisiert eine neue Instanz der JobManagerTask-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17253-125">Initializes a new instance of the JobManagerTask class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowLowPriorityNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowLowPriorityNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowLowPriorityNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AllowLowPriorityNode" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowLowPriorityNode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowLowPriorityNode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AllowLowPriorityNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="allowLowPriorityNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17253-126">Ruft ab oder legt sie fest, ob der Auftrags-Manager-Vorgang auf einem Serverknoten mit niedriger Priorität ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="17253-126">Gets or sets whether the Job Manager task may run on a low-priority compute node.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-127">Der Standardwert ist „false“.</span><span class="sxs-lookup"><span data-stu-id="17253-127">The default value is false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ApplicationPackageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="applicationPackageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17253-128">Ruft ab oder legt eine Liste der Anwendungspakete, die der Batch-Dienst vor dem Ausführen der Befehlszeile auf den Serverknoten bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="17253-128">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-129">Anwendungspakete heruntergeladen und in ein freigegebenes Verzeichnis, nicht die Arbeitsverzeichnis Aufgabe bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="17253-129">Application packages are downloaded and deployed to a shared directory, not the task working directory.</span></span> <span data-ttu-id="17253-130">Aus diesem Grund, wenn ein Referenziertes Paket befindet sich bereits auf dem Computeknoten und auf dem neuesten Stand ist, wird dann sie nicht erneut heruntergeladen; die vorhandene Kopie auf dem Computeknoten verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="17253-130">Therefore, if a referenced package is already on the compute node, and is up to date, then it is not re-downloaded; the existing copy on the compute node is used.</span></span> <span data-ttu-id="17253-131">Wenn ein Paket verwiesen wird, z. B. installiert werden kann, da das Paket gelöscht wurde oder weil Fehler beim Herunterladen der Task fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="17253-131">If a referenced application package cannot be installed, for example because the package has been deleted or because download failed, the task fails.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.AuthenticationTokenSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authenticationTokenSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17253-132">Ruft ab oder legt die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</span><span class="sxs-lookup"><span data-stu-id="17253-132">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-133">Wenn diese Eigenschaft festgelegt ist, enthält der Batch-Dienst die Aufgabe mit der ein Authentifizierungstoken der Batch-Dienstvorgänge zu authentifizieren, ohne einen Zugriffsschlüssel verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="17253-133">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="17253-134">Das Token wird über die Umgebungsvariable AZ_BATCH_AUTHENTICATION_TOKEN bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="17253-134">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="17253-135">Die Vorgänge, die mit dem Token die Aufgabe ausführen kann, hängen von den Einstellungen ab.</span><span class="sxs-lookup"><span data-stu-id="17253-135">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="17253-136">Ein Task kann z. B. Auftrag verfügen, um andere Aufgaben hinzufügen, um den Auftrag, oder Überprüfen Sie den Status des Auftrags oder von anderen Aufgaben unter dem Auftrag anfordern.</span><span class="sxs-lookup"><span data-stu-id="17253-136">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks under the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.CommandLine" />
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
            <span data-ttu-id="17253-137">Ruft ab oder legt die Befehlszeile der Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="17253-137">Gets or sets the command line of the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-138">Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung.</span><span class="sxs-lookup"><span data-stu-id="17253-138">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="17253-139">Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.</span><span class="sxs-lookup"><span data-stu-id="17253-139">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Constraints" />
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
            <span data-ttu-id="17253-140">Ruft ab, oder legt ihn fest, die für die Auftrags-Manager-Aufgabe gelten Einschränkungen.</span><span class="sxs-lookup"><span data-stu-id="17253-140">Gets or sets constraints that apply to the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ContainerSettings" />
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
            <span data-ttu-id="17253-141">Ruft ab oder legt die Einstellungen für den Container unter dem die Auftrags-Manager-Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-141">Gets or sets the settings for the container under which the Job Manager task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-142">Wenn Pools, den diese Aufgabe ausgeführt wird ContainerConfiguration festgelegt hat, muss diese ebenfalls festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="17253-142">If the pool that will run this task has containerConfiguration set, this must be set as well.</span></span> <span data-ttu-id="17253-143">Wenn der Pool, der diese Aufgabe ausgeführt wird keine ContainerConfiguration festgelegt hat, muss dies nicht festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="17253-143">If the pool that will run this task doesn't have containerConfiguration set, this must not be set.</span></span> <span data-ttu-id="17253-144">Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="17253-144">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.DisplayName" />
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
            <span data-ttu-id="17253-145">Ruft ab oder legt den Anzeigenamen des Tasks "Auftrags-Manager".</span><span class="sxs-lookup"><span data-stu-id="17253-145">Gets or sets the display name of the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-146">Sie müssen nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.</span><span class="sxs-lookup"><span data-stu-id="17253-146">It need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.EnvironmentSettings" />
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
            <span data-ttu-id="17253-147">Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für die Auftrags-Manager-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="17253-147">Gets or sets a list of environment variable settings for the Job Manager task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Id" />
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
            <span data-ttu-id="17253-148">Ruft ab oder legt eine Zeichenfolge, die die Auftrags-Manager-Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="17253-148">Gets or sets a string that uniquely identifies the Job Manager task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-149">Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten.</span><span class="sxs-lookup"><span data-stu-id="17253-149">The ID can contain any combination of alphanumeric characters including hyphens and underscores and cannot contain more than 64 characters.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="KillJobOnCompletion">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; KillJobOnCompletion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; KillJobOnCompletion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.KillJobOnCompletion" />
      <MemberSignature Language="VB.NET" Value="Public Property KillJobOnCompletion As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.KillJobOnCompletion : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.KillJobOnCompletion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="killJobOnCompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17253-150">Ruft ab oder legt fest, ob es sich bei Abschluss der Aufgabe Auftrags-Manager gibt Abschluss des gesamten Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="17253-150">Gets or sets whether completion of the Job Manager task signifies completion of the entire job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-151">Bei "true", wenn die Auftrags-Manager-Aufgabe abgeschlossen ist, der Batch-Dienst markiert den Auftrag als abzuschließen.</span><span class="sxs-lookup"><span data-stu-id="17253-151">If true, when the Job Manager task completes, the Batch service marks the job as complete.</span></span> <span data-ttu-id="17253-152">Wenn alle Aufgaben noch zu diesem Zeitpunkt (mit Ausnahme des Auftrags Version) ausgeführt werden, werden diese Aufgaben beendet.</span><span class="sxs-lookup"><span data-stu-id="17253-152">If any tasks are still running at this time (other than Job Release), those tasks are terminated.</span></span> <span data-ttu-id="17253-153">Wenn "false" beeinflusst der Abschluss des Auftrags-Manager-Tasks nicht der Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="17253-153">If false, the completion of the Job Manager task does not affect the job status.</span></span> <span data-ttu-id="17253-154">In diesem Fall sollte entweder mithilfe des Attributs OnAllTasksComplete den Auftrag beenden oder haben von einem Client oder Benutzer, die den Auftrag explizit beenden.</span><span class="sxs-lookup"><span data-stu-id="17253-154">In this case, you should either use the onAllTasksComplete attribute to terminate the job, or have a client or user terminate the job explicitly.</span></span> <span data-ttu-id="17253-155">Ein Beispiel hierfür ist, wenn die Auftrags-Manager einen Satz von Aufgaben erstellt jedoch dann keine weiteren Rolle in ihrer Ausführung übernimmt.</span><span class="sxs-lookup"><span data-stu-id="17253-155">An example of this is if the Job Manager creates a set of tasks but then takes no further role in their execution.</span></span> <span data-ttu-id="17253-156">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="17253-156">The default value is true.</span></span> <span data-ttu-id="17253-157">Wenn Sie die Attribute OnAllTasksComplete und OnTaskFailure Steuerelement Auftrag Lebensdauer und mit der Auftrags-Manager-Task nur zum Erstellen von Aufgaben für den Auftrag (nicht zu überwachen) verwenden, ist es wichtig, KillJobOnCompletion auf "false" festgelegt.</span><span class="sxs-lookup"><span data-stu-id="17253-157">If you are using the onAllTasksComplete and onTaskFailure attributes to control job lifetime, and using the Job Manager task only to create the tasks for the job (not to monitor progress), then it is important to set killJobOnCompletion to false.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.OutputFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputFiles")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17253-158">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst nach dem Ausführen der Befehlszeile aus dem Computeknoten hochladen.</span><span class="sxs-lookup"><span data-stu-id="17253-158">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-159">Für Vorgänge mit mehreren Instanzen werden die Dateien nur aus dem Computeknoten hochgeladen werden auf denen die primäre Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-159">For multi-instance tasks, the files will only be uploaded from the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.ResourceFiles" />
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
            <span data-ttu-id="17253-160">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.</span><span class="sxs-lookup"><span data-stu-id="17253-160">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-161">Unter diesem Element aufgelisteten Dateien befinden sich im Arbeitsverzeichnis für den Task.</span><span class="sxs-lookup"><span data-stu-id="17253-161">Files listed under this element are located in the task's working directory.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RunExclusive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RunExclusive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RunExclusive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.RunExclusive" />
      <MemberSignature Language="VB.NET" Value="Public Property RunExclusive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RunExclusive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.RunExclusive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runExclusive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="17253-162">Ruft ab oder legt fest, ob die Auftrags-Manager-Aufgabe erfordert die exklusive Verwendung des Serverknotens, wo es ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-162">Gets or sets whether the Job Manager task requires exclusive use of the compute node where it runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-163">Bei "true", werden auf dem gleichen Computeknoten für keine anderen Aufgaben ausgeführt, solange der Auftrags-Manager ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-163">If true, no other tasks will run on the same compute node for as long as the Job Manager is running.</span></span> <span data-ttu-id="17253-164">Wenn "false", können andere Tasks gleichzeitig mit der Auftrags-Manager auf einem Serverknoten ausführen.</span><span class="sxs-lookup"><span data-stu-id="17253-164">If false, other tasks can run simultaneously with the Job Manager on a compute node.</span></span> <span data-ttu-id="17253-165">Die Auftrags-Manager-Aufgabe zählt normalerweise anhand des Knotens gleichzeitige Taskgrenze, damit dies nur relevant ist, wenn der Knoten mehrere gleichzeitige Aufgaben ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="17253-165">The Job Manager task counts normally against the node's concurrent task limit, so this is only relevant if the node allows multiple concurrent tasks.</span></span> <span data-ttu-id="17253-166">Der Standardwert lautet „true“.</span><span class="sxs-lookup"><span data-stu-id="17253-166">The default value is true.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.UserIdentity" />
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
            <span data-ttu-id="17253-167">Ruft ab oder legt die Identität des Benutzers, unter der die Auftrags-Manager-Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="17253-167">Gets or sets the user identity under which the Job Manager task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17253-168">Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="17253-168">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobManagerTask.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobManagerTask.Validate " />
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
            <span data-ttu-id="17253-169">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="17253-169">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="17253-170">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="17253-170">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>