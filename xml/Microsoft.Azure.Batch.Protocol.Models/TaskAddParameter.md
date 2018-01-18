<Type Name="TaskAddParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter">
  <TypeSignature Language="C#" Value="public class TaskAddParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskAddParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskAddParameter" />
  <TypeSignature Language="F#" Value="type TaskAddParameter = class" />
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
            <span data-ttu-id="cff17-101">Ein hinzuzufügende Azure Batch-Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="cff17-101">An Azure Batch task to add.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.#ctor" />
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
            <span data-ttu-id="cff17-102">Initialisiert eine neue Instanz der TaskAddParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cff17-102">Initializes a new instance of the TaskAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskAddParameter (string id, string commandLine, string displayName = null, Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings = null, Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo = null, Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity = null, Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings = null, Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences = null, Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string commandLine, string displayName, class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings containerSettings, class Microsoft.Azure.Batch.Protocol.Models.ExitConditions exitConditions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; resourceFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; outputFiles, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; environmentSettings, class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation affinityInfo, class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.UserIdentity userIdentity, class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings multiInstanceSettings, class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies dependsOn, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; applicationPackageReferences, class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings authenticationTokenSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.#ctor(System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings,Microsoft.Azure.Batch.Protocol.Models.ExitConditions,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ResourceFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.OutputFile},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.AffinityInformation,Microsoft.Azure.Batch.Protocol.Models.TaskConstraints,Microsoft.Azure.Batch.Protocol.Models.UserIdentity,Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings,Microsoft.Azure.Batch.Protocol.Models.TaskDependencies,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference},Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter : string * string * string * Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings * Microsoft.Azure.Batch.Protocol.Models.ExitConditions * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.AffinityInformation * Microsoft.Azure.Batch.Protocol.Models.TaskConstraints * Microsoft.Azure.Batch.Protocol.Models.UserIdentity * Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings * Microsoft.Azure.Batch.Protocol.Models.TaskDependencies * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; * Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter (id, commandLine, displayName, containerSettings, exitConditions, resourceFiles, outputFiles, environmentSettings, affinityInfo, constraints, userIdentity, multiInstanceSettings, dependsOn, applicationPackageReferences, authenticationTokenSettings)" />
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
        <Parameter Name="exitConditions" Type="Microsoft.Azure.Batch.Protocol.Models.ExitConditions" />
        <Parameter Name="resourceFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt;" />
        <Parameter Name="outputFiles" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt;" />
        <Parameter Name="environmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="affinityInfo" Type="Microsoft.Azure.Batch.Protocol.Models.AffinityInformation" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
        <Parameter Name="userIdentity" Type="Microsoft.Azure.Batch.Protocol.Models.UserIdentity" />
        <Parameter Name="multiInstanceSettings" Type="Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings" />
        <Parameter Name="dependsOn" Type="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" />
        <Parameter Name="applicationPackageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="authenticationTokenSettings" Type="Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="cff17-103">Eine Zeichenfolge, die die Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="cff17-103">A string that uniquely identifies the task within the job.</span></span></param>
        <param name="commandLine"><span data-ttu-id="cff17-104">Die Befehlszeile der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="cff17-104">The command line of the task.</span></span></param>
        <param name="displayName"><span data-ttu-id="cff17-105">Ein Anzeigename für den Task.</span><span class="sxs-lookup"><span data-stu-id="cff17-105">A display name for the task.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="cff17-106">Die Einstellungen für den Container unter dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-106">The settings for the container under which the task runs.</span></span></param>
        <param name="exitConditions"><span data-ttu-id="cff17-107">Wie der Batch-Dienst reagieren soll, wenn die Aufgabe abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="cff17-107">How the Batch service should respond when the task completes.</span></span></param>
        <param name="resourceFiles"><span data-ttu-id="cff17-108">Eine Liste der Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile mit dem Computeknoten heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-108">A list of files that the Batch service will download to the compute node before running the command line.</span></span></param>
        <param name="outputFiles"><span data-ttu-id="cff17-109">Eine Liste der Dateien, die der Batch-Dienst nach dem Ausführen der Befehlszeile aus dem Computeknoten hochladen.</span><span class="sxs-lookup"><span data-stu-id="cff17-109">A list of files that the Batch service will upload from the compute node after running the command line.</span></span></param>
        <param name="environmentSettings"><span data-ttu-id="cff17-110">Eine Liste von umgebungsvariableneinstellungen für den Task.</span><span class="sxs-lookup"><span data-stu-id="cff17-110">A list of environment variable settings for the task.</span></span></param>
        <param name="affinityInfo"><span data-ttu-id="cff17-111">Einen ortshinweis an, der vom Batch-Dienst verwendet werden kann, wählen Sie einen Serverknoten auf dem die neue Aufgabe beginnen.</span><span class="sxs-lookup"><span data-stu-id="cff17-111">A locality hint that can be used by the Batch service to select a compute node on which to start the new task.</span></span></param>
        <param name="constraints"><span data-ttu-id="cff17-112">Die Ausführungseinschränkungen, die für diesen Task gelten.</span><span class="sxs-lookup"><span data-stu-id="cff17-112">The execution constraints that apply to this task.</span></span></param>
        <param name="userIdentity"><span data-ttu-id="cff17-113">Die Benutzeridentität, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-113">The user identity under which the task runs.</span></span></param>
        <param name="multiInstanceSettings"><span data-ttu-id="cff17-114">Ein Objekt, das zeigt an, dass die Aufgabe eine Aufgabe mit mehreren Instanzen ist und Informationen zum Ausführen des Tasks mit mehreren Instanzen enthält.</span><span class="sxs-lookup"><span data-stu-id="cff17-114">An object that indicates that the task is a multi-instance task, and contains information about how to run the multi-instance task.</span></span></param>
        <param name="dependsOn"><span data-ttu-id="cff17-115">Die Aufgaben, denen von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="cff17-115">The tasks that this task depends on.</span></span></param>
        <param name="applicationPackageReferences"><span data-ttu-id="cff17-116">Eine Liste der Anwendungspakete, die der Batch-Dienst vor dem Ausführen der Befehlszeile auf den Serverknoten bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="cff17-116">A list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span></param>
        <param name="authenticationTokenSettings"><span data-ttu-id="cff17-117">Die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</span><span class="sxs-lookup"><span data-stu-id="cff17-117">The settings for an authentication token that the task can use to perform Batch service operations.</span></span></param>
        <summary>
            <span data-ttu-id="cff17-118">Initialisiert eine neue Instanz der TaskAddParameter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cff17-118">Initializes a new instance of the TaskAddParameter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AffinityInformation AffinityInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AffinityInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityInfo As AffinityInformation" />
      <MemberSignature Language="F#" Value="member this.AffinityInfo : Microsoft.Azure.Batch.Protocol.Models.AffinityInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AffinityInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.AffinityInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cff17-119">Ruft ab oder legt einen ortshinweis an, der vom Batch-Dienst verwendet werden kann, wählen Sie einen Serverknoten auf dem die neue Aufgabe beginnen.</span><span class="sxs-lookup"><span data-stu-id="cff17-119">Gets or sets a locality hint that can be used by the Batch service to select a compute node on which to start the new task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; ApplicationPackageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ApplicationPackageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackageReferences As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ApplicationPackageReferences" />
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
            <span data-ttu-id="cff17-120">Ruft ab oder legt eine Liste der Anwendungspakete, die der Batch-Dienst vor dem Ausführen der Befehlszeile auf den Serverknoten bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="cff17-120">Gets or sets a list of application packages that the Batch service will deploy to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-121">Anwendungspakete heruntergeladen und in ein freigegebenes Verzeichnis, nicht die Arbeitsverzeichnis Aufgabe bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="cff17-121">Application packages are downloaded and deployed to a shared directory, not the task working directory.</span></span> <span data-ttu-id="cff17-122">Aus diesem Grund, wenn ein Referenziertes Paket befindet sich bereits auf dem Computeknoten und auf dem neuesten Stand ist, wird dann sie nicht erneut heruntergeladen; die vorhandene Kopie auf dem Computeknoten verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-122">Therefore, if a referenced package is already on the compute node, and is up to date, then it is not re-downloaded; the existing copy on the compute node is used.</span></span> <span data-ttu-id="cff17-123">Wenn ein Paket verwiesen wird, z. B. installiert werden kann, da das Paket gelöscht wurde oder weil Fehler beim Herunterladen der Task fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="cff17-123">If a referenced application package cannot be installed, for example because the package has been deleted or because download failed, the task fails.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationTokenSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings AuthenticationTokenSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AuthenticationTokenSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationTokenSettings As AuthenticationTokenSettings" />
      <MemberSignature Language="F#" Value="member this.AuthenticationTokenSettings : Microsoft.Azure.Batch.Protocol.Models.AuthenticationTokenSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.AuthenticationTokenSettings" />
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
            <span data-ttu-id="cff17-124">Ruft ab oder legt die Einstellungen für ein Authentifizierungstoken, die die Aufgabe zum Ausführen von Batchvorgängen-Dienst verwenden können.</span><span class="sxs-lookup"><span data-stu-id="cff17-124">Gets or sets the settings for an authentication token that the task can use to perform Batch service operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-125">Wenn diese Eigenschaft festgelegt ist, enthält der Batch-Dienst die Aufgabe mit der ein Authentifizierungstoken der Batch-Dienstvorgänge zu authentifizieren, ohne einen Zugriffsschlüssel verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="cff17-125">If this property is set, the Batch service provides the task with an authentication token which can be used to authenticate Batch service operations without requiring an account access key.</span></span> <span data-ttu-id="cff17-126">Das Token wird über die Umgebungsvariable AZ_BATCH_AUTHENTICATION_TOKEN bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="cff17-126">The token is provided via the AZ_BATCH_AUTHENTICATION_TOKEN environment variable.</span></span> <span data-ttu-id="cff17-127">Die Vorgänge, die mit dem Token die Aufgabe ausführen kann, hängen von den Einstellungen ab.</span><span class="sxs-lookup"><span data-stu-id="cff17-127">The operations that the task can carry out using the token depend on the settings.</span></span> <span data-ttu-id="cff17-128">Ein Task kann z. B. Auftrag verfügen, um andere Aufgaben hinzufügen, um den Auftrag, oder Überprüfen Sie den Status des Auftrags oder von anderen Aufgaben unter dem Auftrag anfordern.</span><span class="sxs-lookup"><span data-stu-id="cff17-128">For example, a task can request job permissions in order to add other tasks to the job, or check the status of the job or of other tasks under the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CommandLine">
      <MemberSignature Language="C#" Value="public string CommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.CommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CommandLine : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.CommandLine" />
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
            <span data-ttu-id="cff17-129">Ruft ab oder legt die Befehlszeile der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="cff17-129">Gets or sets the command line of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-130">Die Befehlszeile wird für Vorgänge mit mehreren Instanzen als die primäre Aufgabe ausgeführt, nachdem die primäre Aufgabe und alle Unteraufgaben haben die Koordination-Befehlszeile ausführen.</span><span class="sxs-lookup"><span data-stu-id="cff17-130">For multi-instance tasks, the command line is executed as the primary task, after the primary task and all subtasks have finished executing the coordination command line.</span></span> <span data-ttu-id="cff17-131">Die Befehlszeile wird nicht unter einer Shell ausgeführt, und daher kann nicht nutzen Shell-Funktionen, z. B. umgebungsvariablenerweiterung.</span><span class="sxs-lookup"><span data-stu-id="cff17-131">The command line does not run under a shell, and therefore cannot take advantage of shell features such as environment variable expansion.</span></span> <span data-ttu-id="cff17-132">Wenn Sie solche Funktionen nutzen möchten, Sie sollten rufen Sie die Befehlsshell in der Befehlszeile z. B. mit "Cmd/c MyCommand" in Windows oder "/ Bin/sh - C MyCommand" unter Linux.</span><span class="sxs-lookup"><span data-stu-id="cff17-132">If you want to take advantage of such features, you should invoke the shell in the command line, for example using "cmd /c MyCommand" in Windows or "/bin/sh -c MyCommand" in Linux.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As TaskConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.TaskConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Constraints" />
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
            <span data-ttu-id="cff17-133">Ruft ab, oder legt ihn fest, die für diese Aufgabe gelten ausführungseinschränkungen.</span><span class="sxs-lookup"><span data-stu-id="cff17-133">Gets or sets the execution constraints that apply to this task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-134">Wenn Sie keine Einschränkungen angeben, der "maxtaskretrycount" ist der "maxtaskretrycount" für den Auftrag angegebene und die MaxWallClockTime und RetentionTime unendlich sind.</span><span class="sxs-lookup"><span data-stu-id="cff17-134">If you do not specify constraints, the maxTaskRetryCount is the maxTaskRetryCount specified for the job, and the maxWallClockTime and retentionTime are infinite.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As TaskContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ContainerSettings" />
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
            <span data-ttu-id="cff17-135">Ruft ab oder legt die Einstellungen für den Container unter dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-135">Gets or sets the settings for the container under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-136">Wenn Pools, den diese Aufgabe ausgeführt wird ContainerConfiguration festgelegt hat, muss diese ebenfalls festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="cff17-136">If the pool that will run this task has containerConfiguration set, this must be set as well.</span></span> <span data-ttu-id="cff17-137">Wenn der Pool, der diese Aufgabe ausgeführt wird keine ContainerConfiguration festgelegt hat, muss dies nicht festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="cff17-137">If the pool that will run this task doesn't have containerConfiguration set, this must not be set.</span></span> <span data-ttu-id="cff17-138">Wenn dies angegeben wird, alle Verzeichnisse rekursiv unterhalb der AZ_BATCH_NODE_ROOT_DIR (der Stamm der Azure Batch-Verzeichnisse auf dem Knoten) in den Container zugeordnet sind, alle Umgebungsvariablen für die Aufgabe in den Container zugeordnet sind und die Befehlszeile der Aufgabe ist in den Container ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cff17-138">When this is specified, all directories recursively below the AZ_BATCH_NODE_ROOT_DIR (the root of Azure Batch directories on the node) are mapped into the container, all task environment variables are mapped into the container, and the task command line is executed in the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DependsOn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskDependencies DependsOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DependsOn" />
      <MemberSignature Language="VB.NET" Value="Public Property DependsOn As TaskDependencies" />
      <MemberSignature Language="F#" Value="member this.DependsOn : Microsoft.Azure.Batch.Protocol.Models.TaskDependencies with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DependsOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dependsOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskDependencies</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cff17-139">Ruft ab oder legt die Aufgaben, denen von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="cff17-139">Gets or sets the tasks that this task depends on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-140">Diese Aufgabe wird nicht geplant werden, bis alle Aufgaben, von denen er abhängt erfolgreich abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="cff17-140">This task will not be scheduled until all tasks that it depends on have completed successfully.</span></span> <span data-ttu-id="cff17-141">Wenn keines dieser Aufgaben fehl, und ihre Wiederholung Anzahlen ausgeschöpft, wird diese Aufgabe nie geplant werden.</span><span class="sxs-lookup"><span data-stu-id="cff17-141">If any of those tasks fail and exhaust their retry counts, this task will never be scheduled.</span></span> <span data-ttu-id="cff17-142">Wenn der Auftrag keinen UsesTaskDependencies auf True festgelegt, und dieses Element vorhanden ist, die Anforderung schlägt fehl mit dem Fehlercode TaskDependenciesNotSpecifiedOnJob.</span><span class="sxs-lookup"><span data-stu-id="cff17-142">If the job does not have usesTaskDependencies set to true, and this element is present, the request fails with error code TaskDependenciesNotSpecifiedOnJob.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.DisplayName" />
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
            <span data-ttu-id="cff17-143">Ruft ab oder legt einen Anzeigenamen für den Task.</span><span class="sxs-lookup"><span data-stu-id="cff17-143">Gets or sets a display name for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-144">Der Anzeigename muss nicht eindeutig sein und darf keine Unicode-Zeichen bis zu einer maximalen Länge von 1024.</span><span class="sxs-lookup"><span data-stu-id="cff17-144">The display name need not be unique and can contain any Unicode characters up to a maximum length of 1024.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; EnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.EnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.EnvironmentSettings" />
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
            <span data-ttu-id="cff17-145">Ruft ab oder legt eine Liste von umgebungsvariableneinstellungen für den Task.</span><span class="sxs-lookup"><span data-stu-id="cff17-145">Gets or sets a list of environment variable settings for the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitConditions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ExitConditions ExitConditions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ExitConditions" />
      <MemberSignature Language="VB.NET" Value="Public Property ExitConditions As ExitConditions" />
      <MemberSignature Language="F#" Value="member this.ExitConditions : Microsoft.Azure.Batch.Protocol.Models.ExitConditions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ExitConditions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exitConditions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ExitConditions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cff17-146">Ruft ab oder legt sie fest, wie der Batch-Dienst reagieren soll, wenn die Aufgabe abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="cff17-146">Gets or sets how the Batch service should respond when the task completes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Id" />
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
            <span data-ttu-id="cff17-147">Ruft ab oder legt eine Zeichenfolge, die die Aufgabe im Auftrag eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="cff17-147">Gets or sets a string that uniquely identifies the task within the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-148">Die ID kann eine beliebige Kombination von alphanumerischen Zeichen, einschließlich der Bindestriche und Unterstriche enthalten und darf nicht mehr als 64 Zeichen enthalten.</span><span class="sxs-lookup"><span data-stu-id="cff17-148">The ID can contain any combination of alphanumeric characters including hyphens and underscores, and cannot contain more than 64 characters.</span></span> <span data-ttu-id="cff17-149">Die ID ist unter Beibehaltung von Groß-/Kleinschreibung und Groß-/Kleinschreibung (d. h., Sie verfügen nicht zwei IDs innerhalb eines Auftrags, die sich nur in Groß-bzw. Kleinschreibung unterscheiden).</span><span class="sxs-lookup"><span data-stu-id="cff17-149">The ID is case-preserving and case-insensitive (that is, you may not have two IDs within a job that differ only by case).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MultiInstanceSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings MultiInstanceSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.MultiInstanceSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property MultiInstanceSettings As MultiInstanceSettings" />
      <MemberSignature Language="F#" Value="member this.MultiInstanceSettings : Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.MultiInstanceSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="multiInstanceSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.MultiInstanceSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cff17-150">Ruft ab oder legt ein Objekt, das zeigt an, dass die Aufgabe eine Aufgabe mit mehreren Instanzen ist und Informationen zum Ausführen des Tasks mit mehreren Instanzen enthält.</span><span class="sxs-lookup"><span data-stu-id="cff17-150">Gets or sets an object that indicates that the task is a multi-instance task, and contains information about how to run the multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; OutputFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.OutputFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputFiles As IList(Of OutputFile)" />
      <MemberSignature Language="F#" Value="member this.OutputFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.OutputFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.OutputFiles" />
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
            <span data-ttu-id="cff17-151">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst nach dem Ausführen der Befehlszeile aus dem Computeknoten hochladen.</span><span class="sxs-lookup"><span data-stu-id="cff17-151">Gets or sets a list of files that the Batch service will upload from the compute node after running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-152">Für Vorgänge mit mehreren Instanzen werden die Dateien nur aus dem Computeknoten hochgeladen werden auf denen die primäre Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-152">For multi-instance tasks, the files will only be uploaded from the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; ResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.ResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.ResourceFiles" />
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
            <span data-ttu-id="cff17-153">Ruft ab oder legt eine Liste der Dateien, die der Batch-Dienst auf den Serverknoten herunterlädt, vor dem Ausführen der Befehlszeile.</span><span class="sxs-lookup"><span data-stu-id="cff17-153">Gets or sets a list of files that the Batch service will download to the compute node before running the command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-154">Für Vorgänge mit mehreren Instanzen werden die Ressourcendateien nur auf den Serverknoten heruntergeladen, auf denen die primäre Aufgabe ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-154">For multi-instance tasks, the resource files will only be downloaded to the compute node on which the primary task is executed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UserIdentity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.UserIdentity UserIdentity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.UserIdentity" />
      <MemberSignature Language="VB.NET" Value="Public Property UserIdentity As UserIdentity" />
      <MemberSignature Language="F#" Value="member this.UserIdentity : Microsoft.Azure.Batch.Protocol.Models.UserIdentity with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.UserIdentity" />
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
            <span data-ttu-id="cff17-155">Ruft ab oder legt die Identität des Benutzers, unter der der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="cff17-155">Gets or sets the user identity under which the task runs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="cff17-156">Wenn nicht angegeben, der Task als Nichtadministrator-eindeutige Benutzer an die Aufgabe ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cff17-156">If omitted, the task runs as a non-administrative user unique to the task.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskAddParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskAddParameter.Validate " />
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
            <span data-ttu-id="cff17-157">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="cff17-157">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cff17-158">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="cff17-158">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>