<Type Name="Job" FullName="Microsoft.Azure.Management.BatchAI.Models.Job">
  <TypeSignature Language="C#" Value="public class Job : Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Job extends Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.Job" />
  <TypeSignature Language="VB.NET" Value="Public Class Job&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Job = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BatchAI.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f301b-101">Enthält Informationen zu dem Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-101">Contains information about the job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Job ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Job.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f301b-102">Initialisiert eine neue Instanz der Klasse Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-102">Initializes a new instance of the Job class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Job (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string experimentName = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId cluster = null, Nullable&lt;int&gt; nodeCount = null, Microsoft.Azure.Management.BatchAI.Models.ContainerSettings containerSettings = null, string toolType = null, Microsoft.Azure.Management.BatchAI.Models.CNTKsettings cntkSettings = null, Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings tensorFlowSettings = null, Microsoft.Azure.Management.BatchAI.Models.CaffeSettings caffeSettings = null, Microsoft.Azure.Management.BatchAI.Models.ChainerSettings chainerSettings = null, Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings customToolkitSettings = null, Microsoft.Azure.Management.BatchAI.Models.JobPreparation jobPreparation = null, string stdOutErrPathPrefix = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; inputDirectories = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; outputDirectories = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables = null, Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints constraints = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.BatchAI.Models.ProvisioningState.Creating, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; executionState = null, Nullable&lt;DateTime&gt; executionStateTransitionTime = null, Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo executionInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string experimentName, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Management.BatchAI.Models.ResourceId cluster, valuetype System.Nullable`1&lt;int32&gt; nodeCount, class Microsoft.Azure.Management.BatchAI.Models.ContainerSettings containerSettings, string toolType, class Microsoft.Azure.Management.BatchAI.Models.CNTKsettings cntkSettings, class Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings tensorFlowSettings, class Microsoft.Azure.Management.BatchAI.Models.CaffeSettings caffeSettings, class Microsoft.Azure.Management.BatchAI.Models.ChainerSettings chainerSettings, class Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings customToolkitSettings, class Microsoft.Azure.Management.BatchAI.Models.JobPreparation jobPreparation, string stdOutErrPathPrefix, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; inputDirectories, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; outputDirectories, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables, class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints constraints, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; executionState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; executionStateTransitionTime, class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo executionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Job.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.ContainerSettings,System.String,Microsoft.Azure.Management.BatchAI.Models.CNTKsettings,Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings,Microsoft.Azure.Management.BatchAI.Models.CaffeSettings,Microsoft.Azure.Management.BatchAI.Models.ChainerSettings,Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings,Microsoft.Azure.Management.BatchAI.Models.JobPreparation,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.InputDirectory},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.OutputDirectory},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting},Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints,System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.ProvisioningState,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.BatchAI.Models.ExecutionState},System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.Job : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.ResourceId * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.ContainerSettings * string * Microsoft.Azure.Management.BatchAI.Models.CNTKsettings * Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings * Microsoft.Azure.Management.BatchAI.Models.CaffeSettings * Microsoft.Azure.Management.BatchAI.Models.ChainerSettings * Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings * Microsoft.Azure.Management.BatchAI.Models.JobPreparation * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; * Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.ProvisioningState * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="new Microsoft.Azure.Management.BatchAI.Models.Job (id, name, type, location, tags, experimentName, priority, cluster, nodeCount, containerSettings, toolType, cntkSettings, tensorFlowSettings, caffeSettings, chainerSettings, customToolkitSettings, jobPreparation, stdOutErrPathPrefix, inputDirectories, outputDirectories, environmentVariables, constraints, creationTime, provisioningState, provisioningStateTransitionTime, executionState, executionStateTransitionTime, executionInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="experimentName" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cluster" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="nodeCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ContainerSettings" />
        <Parameter Name="toolType" Type="System.String" />
        <Parameter Name="cntkSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings" />
        <Parameter Name="tensorFlowSettings" Type="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" />
        <Parameter Name="caffeSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" />
        <Parameter Name="chainerSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" />
        <Parameter Name="customToolkitSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings" />
        <Parameter Name="jobPreparation" Type="Microsoft.Azure.Management.BatchAI.Models.JobPreparation" />
        <Parameter Name="stdOutErrPathPrefix" Type="System.String" />
        <Parameter Name="inputDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt;" />
        <Parameter Name="outputDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt;" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="executionState" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt;" />
        <Parameter Name="executionStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="f301b-103">Die ID der Ressource</span><span class="sxs-lookup"><span data-stu-id="f301b-103">The ID of the resource</span></span></param>
        <param name="name"><span data-ttu-id="f301b-104">Der Name der Ressource</span><span class="sxs-lookup"><span data-stu-id="f301b-104">The name of the resource</span></span></param>
        <param name="type"><span data-ttu-id="f301b-105">Der Typ der Ressource</span><span class="sxs-lookup"><span data-stu-id="f301b-105">The type of the resource</span></span></param>
        <param name="location"><span data-ttu-id="f301b-106">Der Speicherort der Ressource</span><span class="sxs-lookup"><span data-stu-id="f301b-106">The location of the resource</span></span></param>
        <param name="tags"><span data-ttu-id="f301b-107">Die Tags der Ressource</span><span class="sxs-lookup"><span data-stu-id="f301b-107">The tags of the resource</span></span></param>
        <param name="experimentName"><span data-ttu-id="f301b-108">Beschreiben Sie das Experiment Informationen des Auftrags</span><span class="sxs-lookup"><span data-stu-id="f301b-108">Describe the experiment information of the job</span></span></param>
        <param name="priority"><span data-ttu-id="f301b-109">Priorität, die dem Auftrag zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-109">Priority associated with the job.</span></span></param>
        <param name="cluster"><span data-ttu-id="f301b-110">Gibt die Id des Clusters, auf denen dieser Auftrag ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="f301b-110">Specifies the Id of the cluster on which this job will run.</span></span></param>
        <param name="nodeCount"><span data-ttu-id="f301b-111">Die Anzahl von Compute-Knoten, auf denen der Auftrag ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f301b-111">Number of compute nodes to run the job on.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="f301b-112">Wenn angegeben, dass der Auftrag im angegebenen Container ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="f301b-112">If provided the job will run in the specified container.</span></span></param>
        <param name="toolType"><span data-ttu-id="f301b-113">Das Toolkit-Typ des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-113">The toolkit type of this job.</span></span></param>
        <param name="cntkSettings"><span data-ttu-id="f301b-114">Gibt die Einstellungen für den Auftrag CNTK (d. h. Microsoft Cognitive Toolkit).</span><span class="sxs-lookup"><span data-stu-id="f301b-114">Specifies the settings for CNTK (aka Microsoft Cognitive Toolkit) job.</span></span></param>
        <param name="tensorFlowSettings"><span data-ttu-id="f301b-115">Gibt die Einstellungen für den Auftrag Tensor fließen.</span><span class="sxs-lookup"><span data-stu-id="f301b-115">Specifies the settings for Tensor Flow job.</span></span></param>
        <param name="caffeSettings"><span data-ttu-id="f301b-116">Gibt die Einstellungen für Caffe Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-116">Specifies the settings for Caffe job.</span></span></param>
        <param name="chainerSettings"><span data-ttu-id="f301b-117">Gibt die Einstellungen für Chainer-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-117">Specifies the settings for Chainer job.</span></span></param>
        <param name="customToolkitSettings"><span data-ttu-id="f301b-118">Gibt die Einstellungen für benutzerdefiniertes Tool Kit Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-118">Specifies the settings for custom tool kit job.</span></span></param>
        <param name="jobPreparation"><span data-ttu-id="f301b-119">Gibt die Aktionen ausgeführt werden, bevor das Toolkit gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="f301b-119">Specifies the actions to be performed before tool kit is launched.</span></span></param>
        <param name="stdOutErrPathPrefix"><span data-ttu-id="f301b-120">Der Pfad, in dem der Batch AI-Dienst "stdout" und Stderror des Auftrags hochgeladen wird.</span><span class="sxs-lookup"><span data-stu-id="f301b-120">The path where the Batch AI service will upload stdout and stderror of the job.</span></span></param>
        <param name="inputDirectories"><span data-ttu-id="f301b-121">Gibt die Liste der Eingabe Verzeichnisse für den Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-121">Specifies the list of input directories for the Job.</span></span></param>
        <param name="outputDirectories"><span data-ttu-id="f301b-122">Gibt die Liste der Ausgabeverzeichnisse, in denen die Modelle erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-122">Specifies the list of output directories where the models will be created.</span></span> <span data-ttu-id="f301b-123">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="f301b-123">.</span></span></param>
        <param name="environmentVariables"><span data-ttu-id="f301b-124">Zusätzliche Umgebungsvariablen, die dem Auftrag übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-124">Additional environment variables to be passed to the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="f301b-125">Einschränkungen, die dem Auftrag zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-125">Constraints associated with the Job.</span></span></param>
        <param name="creationTime"><span data-ttu-id="f301b-126">Die Erstellungszeit des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-126">The job creation time.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="f301b-127">Der Bereitstellungsstatus des Batch-AI-Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-127">The provisioned state of the Batch AI job.</span></span> <span data-ttu-id="f301b-128">Folgende Werte sind möglich: "erstellen", "erfolgreich abgeschlossen", "fehlgeschlagen", "löschen"</span><span class="sxs-lookup"><span data-stu-id="f301b-128">Possible values include: 'creating', 'succeeded', 'failed', 'deleting'</span></span></param>
        <param name="provisioningStateTransitionTime"><span data-ttu-id="f301b-129">Der Zeitpunkt, an dem der Auftrag seiner aktuellen Bereitstellungsstatus angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-129">The time at which the job entered its current provisioning state.</span></span></param>
        <param name="executionState"><span data-ttu-id="f301b-130">Der aktuelle Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-130">The current state of the job.</span></span></param>
        <param name="executionStateTransitionTime"><span data-ttu-id="f301b-131">Der Zeitpunkt, an dem der Auftrag den aktuellen Ausführungsstatus angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-131">The time at which the job entered its current execution state.</span></span></param>
        <param name="executionInfo"><span data-ttu-id="f301b-132">Enthält Informationen zur Ausführung eines Auftrags in der Azure Batch-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="f301b-132">Contains information about the execution of a job in the Azure Batch service.</span></span></param>
        <summary>
            <span data-ttu-id="f301b-133">Initialisiert eine neue Instanz der Klasse Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-133">Initializes a new instance of the Job class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaffeSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CaffeSettings CaffeSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CaffeSettings CaffeSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CaffeSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CaffeSettings As CaffeSettings" />
      <MemberSignature Language="F#" Value="member this.CaffeSettings : Microsoft.Azure.Management.BatchAI.Models.CaffeSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CaffeSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.caffeSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.CaffeSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-134">Ruft ab oder legt gibt die Einstellungen für Caffe Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-134">Gets or sets specifies the settings for Caffe job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ChainerSettings ChainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ChainerSettings ChainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ChainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ChainerSettings As ChainerSettings" />
      <MemberSignature Language="F#" Value="member this.ChainerSettings : Microsoft.Azure.Management.BatchAI.Models.ChainerSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ChainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.chainerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ChainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-135">Ruft ab oder legt gibt die Einstellungen für Chainer-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-135">Gets or sets specifies the settings for Chainer job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cluster">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Cluster { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Cluster" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.Cluster" />
      <MemberSignature Language="VB.NET" Value="Public Property Cluster As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Cluster : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.Cluster" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cluster")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-136">Ruft ab oder legt gibt die Id des Clusters, auf denen dieser Auftrag ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="f301b-136">Gets or sets specifies the Id of the cluster on which this job will run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CntkSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CNTKsettings CntkSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CNTKsettings CntkSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CntkSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CntkSettings As CNTKsettings" />
      <MemberSignature Language="F#" Value="member this.CntkSettings : Microsoft.Azure.Management.BatchAI.Models.CNTKsettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CntkSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.cntkSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.CNTKsettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-137">Ruft ab oder legt gibt die Einstellungen für CNTK (d. h. Microsoft Cognitive Toolkit) Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-137">Gets or sets specifies the settings for CNTK (aka Microsoft Cognitive Toolkit) job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobPropertiesConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobPropertiesConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-138">Ruft ab oder legt Einschränkungen, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f301b-138">Gets or sets constraints associated with the Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As ContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Management.BatchAI.Models.ContainerSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ContainerSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containerSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ContainerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-139">Ruft ab, oder legt sie fest, wenn angegeben, dass der Auftrag im angegebenen Container ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="f301b-139">Gets or sets if provided the job will run in the specified container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-140">Wenn der Container im Rahmen des Cluster-Setup nicht heruntergeladen wurde, wird der gleiche Container-Image verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-140">If the container was downloaded as part of cluster setup then the same container image will be used.</span></span> <span data-ttu-id="f301b-141">Wenn nicht angegeben ist, wird der Auftrag auf dem virtuellen Computer ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f301b-141">If not provided, the job will run on the VM.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-142">Ruft die Erstellungszeit des Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="f301b-142">Gets the job creation time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-143">Der Zeitpunkt der Erstellung des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-143">The creation time of the job.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomToolkitSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings CustomToolkitSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings CustomToolkitSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.CustomToolkitSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomToolkitSettings As CustomToolkitSettings" />
      <MemberSignature Language="F#" Value="member this.CustomToolkitSettings : Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.CustomToolkitSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customToolkitSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-144">Ruft ab oder legt gibt die Einstellungen für benutzerdefiniertes Tool Kit Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-144">Gets or sets specifies the settings for custom tool kit job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.EnvironmentVariables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.environmentVariables")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-145">Ermittelt oder definiert zusätzliche Umgebungsvariablen, die dem Auftrag übergeben werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-145">Gets or sets additional environment variables to be passed to the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-146">Batch AI-Dienste legt die folgenden Umgebungsvariablen für alle Aufträge: AZ_BATCHAI_INPUT_id, AZ_BATCHAI_OUTPUT_id, AZ_BATCHAI_NUM_GPUS_PER_NODE, für die verteilte TensorFlow Aufträge folgende zusätzliche Umgebungsvariablen festgelegt sind, vom Batchdienst AI : AZ_BATCHAI_PS_HOSTS AZ_BATCHAI_WORKER_HOSTS.</span><span class="sxs-lookup"><span data-stu-id="f301b-146">Batch AI services sets the following environment variables for all jobs: AZ_BATCHAI_INPUT_id, AZ_BATCHAI_OUTPUT_id, AZ_BATCHAI_NUM_GPUS_PER_NODE, For distributed TensorFlow jobs, following additional environment variables are set by the Batch AI Service: AZ_BATCHAI_PS_HOSTS, AZ_BATCHAI_WORKER_HOSTS.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As JobPropertiesExecutionInfo" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.executionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobPropertiesExecutionInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-147">Ruft ab oder legt enthält Informationen zur Ausführung eines Auftrags in der Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="f301b-147">Gets or sets contains information about the execution of a job in the Azure Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; ExecutionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; ExecutionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionState As Nullable(Of ExecutionState)" />
      <MemberSignature Language="F#" Value="member this.ExecutionState : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.executionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.ExecutionState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-148">Ruft ab oder legt den aktuellen Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-148">Gets or sets the current state of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-149">Der aktuelle Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-149">The current state of the job.</span></span> <span data-ttu-id="f301b-150">Mögliche Werte sind: in der Warteschlange - der Auftrag befindet sich in der Warteschlange und ausführen.</span><span class="sxs-lookup"><span data-stu-id="f301b-150">Possible values are: queued - The job is queued and able to run.</span></span> <span data-ttu-id="f301b-151">Ein Auftrag geht in diesen Zustand, bei der Erstellung oder wenn es eine Wiederholung nach einer fehlgeschlagenen Ausführung wartet.</span><span class="sxs-lookup"><span data-stu-id="f301b-151">A job enters this state when it is created, or when it is awaiting a retry after a failed run.</span></span> <span data-ttu-id="f301b-152">Ausführen</span><span class="sxs-lookup"><span data-stu-id="f301b-152">running</span></span>
            - <span data-ttu-id="f301b-153">Der Auftrag wird auf einem Computercluster ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f301b-153">The job is running on a compute cluster.</span></span> <span data-ttu-id="f301b-154">Hierin ist das Projekt auf Dokumentebene zur Vorbereitung, einschließlich des Herunterladens von Ressourcendateien, oder richten Sie für den Auftrag - angegebene Container es bedeutet nicht unbedingt, dass die Befehlszeile für den Auftrag mit der Ausführung begonnen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-154">This includes job-level preparation such as downloading resource files or set up container specified on the job - it does not necessarily mean that the job command line has started executing.</span></span> <span data-ttu-id="f301b-155">Beenden - der Auftrag wurde vom Benutzer beendet, der Vorgang "Beenden" wird ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f301b-155">terminating - The job is terminated by the user, the terminate operation is in progress.</span></span>
            <span data-ttu-id="f301b-156">erfolgreich - wurde der Auftrag ausgeführten erfolgreich abgeschlossen und wurde mit Exitcode 0 beendet.</span><span class="sxs-lookup"><span data-stu-id="f301b-156">succeeded - The job has completed running succesfully and exited with exit code 0.</span></span> <span data-ttu-id="f301b-157">Fehler - der Auftrag wurde nicht erfolgreich (mit einem Exitcode ungleich 0 nicht erfüllt) und das Wiederholungslimit erreicht wurde.</span><span class="sxs-lookup"><span data-stu-id="f301b-157">failed - The job has finished unsuccessfully (failed with a non-zero exit code) and has exhausted its retry limit.</span></span> <span data-ttu-id="f301b-158">Ein Auftrag wird als Fehler, wenn ein Fehler aufgetreten ist, starten den Auftrag auch markiert.</span><span class="sxs-lookup"><span data-stu-id="f301b-158">A job is also marked as failed if an error occurred launching the job.</span></span> <span data-ttu-id="f301b-159">Folgende Werte sind möglich: "queued", "wird ausgeführt", "Beenden", "erfolgreich abgeschlossen", "fehlgeschlagen"</span><span class="sxs-lookup"><span data-stu-id="f301b-159">Possible values include: 'queued', 'running', 'terminating', 'succeeded', 'failed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExecutionStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExecutionStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExecutionStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExecutionStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExecutionStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.executionStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-160">Ruft den Zeitpunkt, an dem der Auftrag den aktuellen Ausführungsstatus angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-160">Gets the time at which the job entered its current execution state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-161">Der Zeitpunkt, an dem der Auftrag den aktuellen Ausführungsstatus angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-161">The time at which the job entered its current execution state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExperimentName">
      <MemberSignature Language="C#" Value="public string ExperimentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExperimentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ExperimentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExperimentName As String" />
      <MemberSignature Language="F#" Value="member this.ExperimentName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ExperimentName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.experimentName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-162">Ruft ab oder legt beschreiben das Experiment Informationen des Auftrags</span><span class="sxs-lookup"><span data-stu-id="f301b-162">Gets or sets describe the experiment information of the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; InputDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; InputDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.InputDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property InputDirectories As IList(Of InputDirectory)" />
      <MemberSignature Language="F#" Value="member this.InputDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.InputDirectories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputDirectories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-163">Ruft ab oder legt gibt die Liste der Eingabe Verzeichnisse für den Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="f301b-163">Gets or sets specifies the list of input directories for the Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPreparation JobPreparation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPreparation JobPreparation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.JobPreparation" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparation As JobPreparation" />
      <MemberSignature Language="F#" Value="member this.JobPreparation : Microsoft.Azure.Management.BatchAI.Models.JobPreparation with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.JobPreparation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobPreparation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobPreparation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-164">Gibt an die Aktionen, die ausgeführt werden, bevor das Toolkit gestartet wird, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="f301b-164">Gets or sets specifies the actions to be performed before tool kit is launched.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-165">Die angegebenen Aktionen werden auf allen Knoten ausführen, die Teil des Auftrags sind</span><span class="sxs-lookup"><span data-stu-id="f301b-165">The specified actions will run on all the nodes that are part of the job</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.NodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NodeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.NodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-166">Ruft ab oder legt die Anzahl von Compute-Knoten, auf denen der Auftrag ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="f301b-166">Gets or sets number of compute nodes to run the job on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-167">Der Auftrag wird Gang geplant werden, die viele Knoten berechnen</span><span class="sxs-lookup"><span data-stu-id="f301b-167">The job will be gang scheduled on that many compute nodes</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; OutputDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; OutputDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.OutputDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputDirectories As IList(Of OutputDirectory)" />
      <MemberSignature Language="F#" Value="member this.OutputDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.OutputDirectories" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputDirectories")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-168">Ruft ab oder legt gibt die Liste der Ausgabeverzeichnisse, in denen die Modelle erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-168">Gets or sets specifies the list of output directories where the models will be created.</span></span> <span data-ttu-id="f301b-169">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="f301b-169">.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-170">Ruft ab oder legt die Priorität, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="f301b-170">Gets or sets priority associated with the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-171">Priorität, die dem Auftrag zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="f301b-171">Priority associated with the job.</span></span> <span data-ttu-id="f301b-172">Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität.</span><span class="sxs-lookup"><span data-stu-id="f301b-172">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="f301b-173">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="f301b-173">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-174">Ruft den Bereitstellungsstatus des Batch-AI-Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="f301b-174">Gets the provisioned state of the Batch AI job.</span></span> <span data-ttu-id="f301b-175">Folgende Werte sind möglich: "erstellen", "erfolgreich abgeschlossen", "fehlgeschlagen", "löschen"</span><span class="sxs-lookup"><span data-stu-id="f301b-175">Possible values include: 'creating', 'succeeded', 'failed', 'deleting'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-176">Ruft den Zeitpunkt, an dem der Auftrag seiner aktuellen Bereitstellungsstatus angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-176">Gets the time at which the job entered its current provisioning state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-177">Der Zeitpunkt, an dem der Auftrag seiner aktuellen Bereitstellungsstatus angenommen hat.</span><span class="sxs-lookup"><span data-stu-id="f301b-177">The time at which the job entered its current provisioning state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StdOutErrPathPrefix">
      <MemberSignature Language="C#" Value="public string StdOutErrPathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StdOutErrPathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.StdOutErrPathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property StdOutErrPathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.StdOutErrPathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.StdOutErrPathPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.stdOutErrPathPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-178">Ruft ab oder legt den Pfad fest, in dem der Batch AI-Dienst "stdout" und Stderror des Auftrags hochladen.</span><span class="sxs-lookup"><span data-stu-id="f301b-178">Gets or sets the path where the Batch AI service will upload stdout and stderror of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TensorFlowSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings TensorFlowSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings TensorFlowSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.TensorFlowSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TensorFlowSettings As TensorFlowSettings" />
      <MemberSignature Language="F#" Value="member this.TensorFlowSettings : Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.TensorFlowSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tensorFlowSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-179">Ruft ab oder legt ihn fest gibt die Einstellungen für den Auftrag Tensor fließen.</span><span class="sxs-lookup"><span data-stu-id="f301b-179">Gets or sets specifies the settings for Tensor Flow job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToolType">
      <MemberSignature Language="C#" Value="public string ToolType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ToolType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Job.ToolType" />
      <MemberSignature Language="VB.NET" Value="Public Property ToolType As String" />
      <MemberSignature Language="F#" Value="member this.ToolType : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Job.ToolType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.toolType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f301b-180">Ruft ab, oder legt ihn fest den Toolkit-Typ des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="f301b-180">Gets or sets the toolkit type of this job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="f301b-181">Mögliche Werte sind: Cntk Tensorflow, Caffe, caffe2, Chainer, benutzerdefinierte.</span><span class="sxs-lookup"><span data-stu-id="f301b-181">Possible values are: cntk, tensorflow, caffe, caffe2, chainer, custom.</span></span> <span data-ttu-id="f301b-182">Folgende Werte sind möglich: "Cntk", "Tensorflow", "Caffe", "caffe2", "Chainer", "Benutzerdefiniert"</span><span class="sxs-lookup"><span data-stu-id="f301b-182">Possible values include: 'cntk', 'tensorflow', 'caffe', 'caffe2', 'chainer', 'custom'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Job.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="job.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f301b-183">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="f301b-183">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="f301b-184">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="f301b-184">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>