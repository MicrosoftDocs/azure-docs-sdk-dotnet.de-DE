<Type Name="JobCreateParameters" FullName="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters">
  <TypeSignature Language="C#" Value="public class JobCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class JobCreateParameters" />
  <TypeSignature Language="F#" Value="type JobCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c8778-101">Parameter, die auf den Erstellungsvorgang angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-101">Parameters supplied to the Create operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c8778-102">Initialisiert eine neue Instanz der JobCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c8778-102">Initializes a new instance of the JobCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobCreateParameters (string location, Microsoft.Azure.Management.BatchAI.Models.ResourceId cluster, int nodeCount, string stdOutErrPathPrefix, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string experimentName = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Management.BatchAI.Models.ContainerSettings containerSettings = null, Microsoft.Azure.Management.BatchAI.Models.CNTKsettings cntkSettings = null, Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings tensorFlowSettings = null, Microsoft.Azure.Management.BatchAI.Models.CaffeSettings caffeSettings = null, Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings caffe2Settings = null, Microsoft.Azure.Management.BatchAI.Models.ChainerSettings chainerSettings = null, Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings customToolkitSettings = null, Microsoft.Azure.Management.BatchAI.Models.JobPreparation jobPreparation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; inputDirectories = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; outputDirectories = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables = null, Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints constraints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.BatchAI.Models.ResourceId cluster, int32 nodeCount, string stdOutErrPathPrefix, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string experimentName, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Management.BatchAI.Models.ContainerSettings containerSettings, class Microsoft.Azure.Management.BatchAI.Models.CNTKsettings cntkSettings, class Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings tensorFlowSettings, class Microsoft.Azure.Management.BatchAI.Models.CaffeSettings caffeSettings, class Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings caffe2Settings, class Microsoft.Azure.Management.BatchAI.Models.ChainerSettings chainerSettings, class Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings customToolkitSettings, class Microsoft.Azure.Management.BatchAI.Models.JobPreparation jobPreparation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; inputDirectories, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; outputDirectories, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; environmentVariables, class Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints constraints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.#ctor(System.String,Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.Int32,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.ContainerSettings,Microsoft.Azure.Management.BatchAI.Models.CNTKsettings,Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings,Microsoft.Azure.Management.BatchAI.Models.CaffeSettings,Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings,Microsoft.Azure.Management.BatchAI.Models.ChainerSettings,Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings,Microsoft.Azure.Management.BatchAI.Models.JobPreparation,System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.InputDirectory},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.OutputDirectory},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting},Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters : string * Microsoft.Azure.Management.BatchAI.Models.ResourceId * int * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.ContainerSettings * Microsoft.Azure.Management.BatchAI.Models.CNTKsettings * Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings * Microsoft.Azure.Management.BatchAI.Models.CaffeSettings * Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings * Microsoft.Azure.Management.BatchAI.Models.ChainerSettings * Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings * Microsoft.Azure.Management.BatchAI.Models.JobPreparation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; * Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints -&gt; Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" Usage="new Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters (location, cluster, nodeCount, stdOutErrPathPrefix, tags, experimentName, priority, containerSettings, cntkSettings, tensorFlowSettings, caffeSettings, caffe2Settings, chainerSettings, customToolkitSettings, jobPreparation, inputDirectories, outputDirectories, environmentVariables, constraints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cluster" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="nodeCount" Type="System.Int32" />
        <Parameter Name="stdOutErrPathPrefix" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="experimentName" Type="System.String" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="containerSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ContainerSettings" />
        <Parameter Name="cntkSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CNTKsettings" />
        <Parameter Name="tensorFlowSettings" Type="Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings" />
        <Parameter Name="caffeSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CaffeSettings" />
        <Parameter Name="caffe2Settings" Type="Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings" />
        <Parameter Name="chainerSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ChainerSettings" />
        <Parameter Name="customToolkitSettings" Type="Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings" />
        <Parameter Name="jobPreparation" Type="Microsoft.Azure.Management.BatchAI.Models.JobPreparation" />
        <Parameter Name="inputDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt;" />
        <Parameter Name="outputDirectories" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt;" />
        <Parameter Name="environmentVariables" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="c8778-103">Die Region, in dem den Auftrag erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="c8778-103">The region in which to create the job.</span></span></param>
        <param name="cluster"><span data-ttu-id="c8778-104">Gibt die Id des Clusters, auf denen dieser Auftrag ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c8778-104">Specifies the Id of the cluster on which this job will run.</span></span></param>
        <param name="nodeCount"><span data-ttu-id="c8778-105">Die Anzahl von Compute-Knoten, auf denen der Auftrag ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c8778-105">Number of compute nodes to run the job on.</span></span></param>
        <param name="stdOutErrPathPrefix"><span data-ttu-id="c8778-106">Der Pfad, in dem der Batch AI-Dienst "stdout" und Stderror des Auftrags hochgeladen wird.</span><span class="sxs-lookup"><span data-stu-id="c8778-106">The path where the Batch AI service will upload stdout and stderror of the job.</span></span></param>
        <param name="tags"><span data-ttu-id="c8778-107">Der benutzerdefinierte Tags, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c8778-107">The user specified tags associated with the job.</span></span></param>
        <param name="experimentName"><span data-ttu-id="c8778-108">Beschreiben Sie das Experiment Informationen des Auftrags</span><span class="sxs-lookup"><span data-stu-id="c8778-108">Describe the experiment information of the job</span></span></param>
        <param name="priority"><span data-ttu-id="c8778-109">Priorität, die dem Auftrag zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-109">Priority associated with the job.</span></span></param>
        <param name="containerSettings"><span data-ttu-id="c8778-110">Wenn angegeben, dass der Auftrag im angegebenen Container ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c8778-110">If provided the job will run in the specified container.</span></span></param>
        <param name="cntkSettings"><span data-ttu-id="c8778-111">Gibt die Einstellungen für den Auftrag CNTK (d. h. Microsoft Cognitive Toolkit).</span><span class="sxs-lookup"><span data-stu-id="c8778-111">Specifies the settings for CNTK (aka Microsoft Cognitive Toolkit) job.</span></span></param>
        <param name="tensorFlowSettings"><span data-ttu-id="c8778-112">Gibt die Einstellungen für den Auftrag Tensor fließen.</span><span class="sxs-lookup"><span data-stu-id="c8778-112">Specifies the settings for Tensor Flow job.</span></span></param>
        <param name="caffeSettings"><span data-ttu-id="c8778-113">Gibt die Einstellungen für Caffe Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-113">Specifies the settings for Caffe job.</span></span></param>
        <param name="caffe2Settings"><span data-ttu-id="c8778-114">Gibt die Einstellungen für Caffe2 Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-114">Specifies the settings for Caffe2 job.</span></span></param>
        <param name="chainerSettings"><span data-ttu-id="c8778-115">Gibt die Einstellungen für Chainer-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-115">Specifies the settings for Chainer job.</span></span></param>
        <param name="customToolkitSettings"><span data-ttu-id="c8778-116">Gibt die Einstellungen für benutzerdefiniertes Tool Kit Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-116">Specifies the settings for custom tool kit job.</span></span></param>
        <param name="jobPreparation"><span data-ttu-id="c8778-117">Gibt die Befehlszeile ausgeführt werden, bevor das Toolkit gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="c8778-117">Specifies the command line to be executed before tool kit is launched.</span></span></param>
        <param name="inputDirectories"><span data-ttu-id="c8778-118">Gibt die Liste der Eingabe Verzeichnisse für den Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-118">Specifies the list of input directories for the Job.</span></span></param>
        <param name="outputDirectories"><span data-ttu-id="c8778-119">Gibt die Liste der Ausgabeverzeichnisse, in denen die Modelle erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-119">Specifies the list of output directories where the models will be created.</span></span> <span data-ttu-id="c8778-120">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="c8778-120">.</span></span></param>
        <param name="environmentVariables"><span data-ttu-id="c8778-121">Zusätzliche Umgebungsvariablen, die für den Auftrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="c8778-121">Additional environment variables to set on the job.</span></span></param>
        <param name="constraints"><span data-ttu-id="c8778-122">Einschränkungen, die dem Auftrag zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-122">Constraints associated with the Job.</span></span></param>
        <summary>
            <span data-ttu-id="c8778-123">Initialisiert eine neue Instanz der JobCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c8778-123">Initializes a new instance of the JobCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caffe2Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings Caffe2Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings Caffe2Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Caffe2Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property Caffe2Settings As Caffe2Settings" />
      <MemberSignature Language="F#" Value="member this.Caffe2Settings : Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Caffe2Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.caffe2Settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Caffe2Settings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8778-124">Ruft ab oder legt gibt die Einstellungen für Caffe2 Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-124">Gets or sets specifies the settings for Caffe2 job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaffeSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CaffeSettings CaffeSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CaffeSettings CaffeSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.CaffeSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CaffeSettings As CaffeSettings" />
      <MemberSignature Language="F#" Value="member this.CaffeSettings : Microsoft.Azure.Management.BatchAI.Models.CaffeSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.CaffeSettings" />
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
            <span data-ttu-id="c8778-125">Ruft ab oder legt gibt die Einstellungen für Caffe Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-125">Gets or sets specifies the settings for Caffe job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ChainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ChainerSettings ChainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ChainerSettings ChainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.ChainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ChainerSettings As ChainerSettings" />
      <MemberSignature Language="F#" Value="member this.ChainerSettings : Microsoft.Azure.Management.BatchAI.Models.ChainerSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.ChainerSettings" />
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
            <span data-ttu-id="c8778-126">Ruft ab oder legt gibt die Einstellungen für Chainer-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-126">Gets or sets specifies the settings for Chainer job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cluster">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Cluster { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Cluster" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Cluster" />
      <MemberSignature Language="VB.NET" Value="Public Property Cluster As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Cluster : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Cluster" />
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
            <span data-ttu-id="c8778-127">Ruft ab oder legt gibt die Id des Clusters, auf denen dieser Auftrag ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c8778-127">Gets or sets specifies the Id of the cluster on which this job will run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CntkSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CNTKsettings CntkSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CNTKsettings CntkSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.CntkSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CntkSettings As CNTKsettings" />
      <MemberSignature Language="F#" Value="member this.CntkSettings : Microsoft.Azure.Management.BatchAI.Models.CNTKsettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.CntkSettings" />
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
            <span data-ttu-id="c8778-128">Ruft ab oder legt gibt die Einstellungen für CNTK (d. h. Microsoft Cognitive Toolkit) Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-128">Gets or sets specifies the settings for CNTK (aka Microsoft Cognitive Toolkit) job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobBasePropertiesConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Constraints" />
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
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.JobBasePropertiesConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8778-129">Ruft ab oder legt Einschränkungen, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c8778-129">Gets or sets constraints associated with the Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ContainerSettings ContainerSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ContainerSettings ContainerSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.ContainerSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerSettings As ContainerSettings" />
      <MemberSignature Language="F#" Value="member this.ContainerSettings : Microsoft.Azure.Management.BatchAI.Models.ContainerSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.ContainerSettings" />
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
            <span data-ttu-id="c8778-130">Ruft ab, oder legt sie fest, wenn angegeben, dass der Auftrag im angegebenen Container ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c8778-130">Gets or sets if provided the job will run in the specified container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8778-131">Wenn der Container im Rahmen des Cluster-Setup nicht heruntergeladen wurde, wird der gleiche Container-Image verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-131">If the container was downloaded as part of cluster setup then the same container image will be used.</span></span> <span data-ttu-id="c8778-132">Wenn nicht angegeben ist, wird der Auftrag auf dem virtuellen Computer ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c8778-132">If not provided, the job will run on the VM.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomToolkitSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings CustomToolkitSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings CustomToolkitSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.CustomToolkitSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomToolkitSettings As CustomToolkitSettings" />
      <MemberSignature Language="F#" Value="member this.CustomToolkitSettings : Microsoft.Azure.Management.BatchAI.Models.CustomToolkitSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.CustomToolkitSettings" />
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
            <span data-ttu-id="c8778-133">Ruft ab oder legt gibt die Einstellungen für benutzerdefiniertes Tool Kit Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-133">Gets or sets specifies the settings for custom tool kit job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnvironmentVariables">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; EnvironmentVariables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.EnvironmentVariables" />
      <MemberSignature Language="VB.NET" Value="Public Property EnvironmentVariables As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.EnvironmentVariables : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.EnvironmentVariables" />
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
            <span data-ttu-id="c8778-134">Ermittelt oder definiert zusätzliche Umgebungsvariablen zum für den Auftrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="c8778-134">Gets or sets additional environment variables to set on the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8778-135">AI batchdienst legt die folgenden Umgebungsvariablen für alle Aufträge: AZ_BATCHAI_INPUT_id, AZ_BATCHAI_OUTPUT_id, AZ_BATCHAI_NUM_GPUS_PER_NODE.</span><span class="sxs-lookup"><span data-stu-id="c8778-135">Batch AI service sets the following environment variables for all jobs: AZ_BATCHAI_INPUT_id, AZ_BATCHAI_OUTPUT_id, AZ_BATCHAI_NUM_GPUS_PER_NODE.</span></span> <span data-ttu-id="c8778-136">Für verteilte TensorFlow Aufträge werden folgende zusätzliche Umgebungsvariablen vom Batchdienst AI festgelegt: AZ_BATCHAI_PS_HOSTS, AZ_BATCHAI_WORKER_HOSTS</span><span class="sxs-lookup"><span data-stu-id="c8778-136">For distributed TensorFlow jobs, following additional environment variables are set by the Batch AI Service: AZ_BATCHAI_PS_HOSTS, AZ_BATCHAI_WORKER_HOSTS</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExperimentName">
      <MemberSignature Language="C#" Value="public string ExperimentName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExperimentName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.ExperimentName" />
      <MemberSignature Language="VB.NET" Value="Public Property ExperimentName As String" />
      <MemberSignature Language="F#" Value="member this.ExperimentName : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.ExperimentName" />
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
            <span data-ttu-id="c8778-137">Ruft ab oder legt beschreiben das Experiment Informationen des Auftrags</span><span class="sxs-lookup"><span data-stu-id="c8778-137">Gets or sets describe the experiment information of the job</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InputDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; InputDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; InputDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.InputDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property InputDirectories As IList(Of InputDirectory)" />
      <MemberSignature Language="F#" Value="member this.InputDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.InputDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.InputDirectories" />
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
            <span data-ttu-id="c8778-138">Ruft ab oder legt gibt die Liste der Eingabe Verzeichnisse für den Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="c8778-138">Gets or sets specifies the list of input directories for the Job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.JobPreparation JobPreparation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.JobPreparation JobPreparation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.JobPreparation" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparation As JobPreparation" />
      <MemberSignature Language="F#" Value="member this.JobPreparation : Microsoft.Azure.Management.BatchAI.Models.JobPreparation with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.JobPreparation" />
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
            <span data-ttu-id="c8778-139">Gibt an der Befehlszeile ausgeführt werden, bevor das Toolkit gestartet wird, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="c8778-139">Gets or sets specifies the command line to be executed before tool kit is launched.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8778-140">Die angegebenen Aktionen werden auf allen Knoten ausführen, die Teil des Auftrags sind</span><span class="sxs-lookup"><span data-stu-id="c8778-140">The specified actions will run on all the nodes that are part of the job</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8778-141">Ruft ab oder legt die Region, in dem den Auftrag erstellt.</span><span class="sxs-lookup"><span data-stu-id="c8778-141">Gets or sets the region in which to create the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeCount">
      <MemberSignature Language="C#" Value="public int NodeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.NodeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeCount As Integer" />
      <MemberSignature Language="F#" Value="member this.NodeCount : int with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.NodeCount" />
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
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8778-142">Ruft ab oder legt die Anzahl von Compute-Knoten, auf denen der Auftrag ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="c8778-142">Gets or sets number of compute nodes to run the job on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8778-143">Der Auftrag wird Gang geplant werden, die viele Knoten berechnen</span><span class="sxs-lookup"><span data-stu-id="c8778-143">The job will be gang scheduled on that many compute nodes</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputDirectories">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; OutputDirectories { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; OutputDirectories" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.OutputDirectories" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputDirectories As IList(Of OutputDirectory)" />
      <MemberSignature Language="F#" Value="member this.OutputDirectories : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.OutputDirectory&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.OutputDirectories" />
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
            <span data-ttu-id="c8778-144">Ruft ab oder legt gibt die Liste der Ausgabeverzeichnisse, in denen die Modelle erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-144">Gets or sets specifies the list of output directories where the models will be created.</span></span> <span data-ttu-id="c8778-145">zu erstellen und zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="c8778-145">.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Priority" />
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
            <span data-ttu-id="c8778-146">Ruft ab oder legt die Priorität, die dem Auftrag zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c8778-146">Gets or sets priority associated with the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="c8778-147">Priorität, die dem Auftrag zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="c8778-147">Priority associated with the job.</span></span> <span data-ttu-id="c8778-148">Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität.</span><span class="sxs-lookup"><span data-stu-id="c8778-148">Priority values can range from -1000 to 1000, with -1000 being the lowest priority and 1000 being the highest priority.</span></span> <span data-ttu-id="c8778-149">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="c8778-149">The default value is 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StdOutErrPathPrefix">
      <MemberSignature Language="C#" Value="public string StdOutErrPathPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StdOutErrPathPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.StdOutErrPathPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property StdOutErrPathPrefix As String" />
      <MemberSignature Language="F#" Value="member this.StdOutErrPathPrefix : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.StdOutErrPathPrefix" />
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
            <span data-ttu-id="c8778-150">Ruft ab oder legt den Pfad fest, in dem der Batch AI-Dienst "stdout" und Stderror des Auftrags hochladen.</span><span class="sxs-lookup"><span data-stu-id="c8778-150">Gets or sets the path where the Batch AI service will upload stdout and stderror of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c8778-151">Ruft ab oder legt fest, die der Benutzer dem Auftrag zugeordneten Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="c8778-151">Gets or sets the user specified tags associated with the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TensorFlowSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings TensorFlowSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings TensorFlowSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.TensorFlowSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TensorFlowSettings As TensorFlowSettings" />
      <MemberSignature Language="F#" Value="member this.TensorFlowSettings : Microsoft.Azure.Management.BatchAI.Models.TensorFlowSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.TensorFlowSettings" />
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
            <span data-ttu-id="c8778-152">Ruft ab oder legt ihn fest gibt die Einstellungen für den Auftrag Tensor fließen.</span><span class="sxs-lookup"><span data-stu-id="c8778-152">Gets or sets specifies the settings for Tensor Flow job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobCreateParameters.Validate " />
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
            <span data-ttu-id="c8778-153">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c8778-153">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c8778-154">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c8778-154">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>