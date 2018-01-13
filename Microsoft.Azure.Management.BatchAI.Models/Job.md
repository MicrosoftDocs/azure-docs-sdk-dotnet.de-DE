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
            Enthält Informationen zu dem Auftrag an.
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
            Initialisiert eine neue Instanz der Klasse Auftrag an.
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
        <param name="id">Die ID der Ressource</param>
        <param name="name">Der Name der Ressource</param>
        <param name="type">Der Typ der Ressource</param>
        <param name="location">Der Speicherort der Ressource</param>
        <param name="tags">Die Tags der Ressource</param>
        <param name="experimentName">Beschreiben Sie das Experiment Informationen des Auftrags</param>
        <param name="priority">Priorität, die dem Auftrag zugeordnet werden.</param>
        <param name="cluster">Gibt die Id des Clusters, auf denen dieser Auftrag ausgeführt wird.</param>
        <param name="nodeCount">Die Anzahl von Compute-Knoten, auf denen der Auftrag ausgeführt.</param>
        <param name="containerSettings">Wenn angegeben, dass der Auftrag im angegebenen Container ausgeführt wird.</param>
        <param name="toolType">Das Toolkit-Typ des Auftrags.</param>
        <param name="cntkSettings">Gibt die Einstellungen für den Auftrag CNTK (d. h. Microsoft Cognitive Toolkit).</param>
        <param name="tensorFlowSettings">Gibt die Einstellungen für den Auftrag Tensor fließen.</param>
        <param name="caffeSettings">Gibt die Einstellungen für Caffe Auftrag an.</param>
        <param name="chainerSettings">Gibt die Einstellungen für Chainer-Auftrag an.</param>
        <param name="customToolkitSettings">Gibt die Einstellungen für benutzerdefiniertes Tool Kit Auftrag an.</param>
        <param name="jobPreparation">Gibt die Aktionen ausgeführt werden, bevor das Toolkit gestartet wird.</param>
        <param name="stdOutErrPathPrefix">Der Pfad, in dem der Batch AI-Dienst "stdout" und Stderror des Auftrags hochgeladen wird.</param>
        <param name="inputDirectories">Gibt die Liste der Eingabe Verzeichnisse für den Auftrag an.</param>
        <param name="outputDirectories">Gibt die Liste der Ausgabeverzeichnisse, in denen die Modelle erstellt werden. zu erstellen und zu verwalten.</param>
        <param name="environmentVariables">Zusätzliche Umgebungsvariablen, die dem Auftrag übergeben werden.</param>
        <param name="constraints">Einschränkungen, die dem Auftrag zugeordnet werden.</param>
        <param name="creationTime">Die Erstellungszeit des Auftrags.</param>
        <param name="provisioningState">Der Bereitstellungsstatus des Batch-AI-Auftrags. Folgende Werte sind möglich: "erstellen", "erfolgreich abgeschlossen", "fehlgeschlagen", "löschen"</param>
        <param name="provisioningStateTransitionTime">Der Zeitpunkt, an dem der Auftrag seiner aktuellen Bereitstellungsstatus angenommen hat.</param>
        <param name="executionState">Der aktuelle Status des Auftrags.</param>
        <param name="executionStateTransitionTime">Der Zeitpunkt, an dem der Auftrag den aktuellen Ausführungsstatus angenommen hat.</param>
        <param name="executionInfo">Enthält Informationen zur Ausführung eines Auftrags in der Azure Batch-Dienst an.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Auftrag an.
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
            Ruft ab oder legt gibt die Einstellungen für Caffe Auftrag an.
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
            Ruft ab oder legt gibt die Einstellungen für Chainer-Auftrag an.
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
            Ruft ab oder legt gibt die Id des Clusters, auf denen dieser Auftrag ausgeführt wird.
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
            Ruft ab oder legt gibt die Einstellungen für CNTK (d. h. Microsoft Cognitive Toolkit) Auftrag an.
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
            Ruft ab oder legt Einschränkungen, die dem Auftrag zugeordnet.
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
            Ruft ab, oder legt sie fest, wenn angegeben, dass der Auftrag im angegebenen Container ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn der Container im Rahmen des Cluster-Setup nicht heruntergeladen wurde, wird der gleiche Container-Image verwendet werden. Wenn nicht angegeben ist, wird der Auftrag auf dem virtuellen Computer ausgeführt.
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
            Ruft die Erstellungszeit des Auftrags ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Zeitpunkt der Erstellung des Auftrags.
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
            Ruft ab oder legt gibt die Einstellungen für benutzerdefiniertes Tool Kit Auftrag an.
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
            Ermittelt oder definiert zusätzliche Umgebungsvariablen, die dem Auftrag übergeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Batch AI-Dienste legt die folgenden Umgebungsvariablen für alle Aufträge: AZ_BATCHAI_INPUT_id, AZ_BATCHAI_OUTPUT_id, AZ_BATCHAI_NUM_GPUS_PER_NODE, für die verteilte TensorFlow Aufträge folgende zusätzliche Umgebungsvariablen festgelegt sind, vom Batchdienst AI : AZ_BATCHAI_PS_HOSTS AZ_BATCHAI_WORKER_HOSTS.
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
            Ruft ab oder legt enthält Informationen zur Ausführung eines Auftrags in der Azure Batch-Dienst.
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
            Ruft ab oder legt den aktuellen Status des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der aktuelle Status des Auftrags. Mögliche Werte sind: in der Warteschlange - der Auftrag befindet sich in der Warteschlange und ausführen. Ein Auftrag geht in diesen Zustand, bei der Erstellung oder wenn es eine Wiederholung nach einer fehlgeschlagenen Ausführung wartet. Ausführen
            - Der Auftrag wird auf einem Computercluster ausgeführt. Hierin ist das Projekt auf Dokumentebene zur Vorbereitung, einschließlich des Herunterladens von Ressourcendateien, oder richten Sie für den Auftrag - angegebene Container es bedeutet nicht unbedingt, dass die Befehlszeile für den Auftrag mit der Ausführung begonnen hat. Beenden - der Auftrag wurde vom Benutzer beendet, der Vorgang "Beenden" wird ausgeführt.
            erfolgreich - wurde der Auftrag ausgeführten erfolgreich abgeschlossen und wurde mit Exitcode 0 beendet. Fehler - der Auftrag wurde nicht erfolgreich (mit einem Exitcode ungleich 0 nicht erfüllt) und das Wiederholungslimit erreicht wurde. Ein Auftrag wird als Fehler, wenn ein Fehler aufgetreten ist, starten den Auftrag auch markiert. Folgende Werte sind möglich: "queued", "wird ausgeführt", "Beenden", "erfolgreich abgeschlossen", "fehlgeschlagen"
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
            Ruft den Zeitpunkt, an dem der Auftrag den aktuellen Ausführungsstatus angenommen hat.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Zeitpunkt, an dem der Auftrag den aktuellen Ausführungsstatus angenommen hat.
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
            Ruft ab oder legt beschreiben das Experiment Informationen des Auftrags
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
            Ruft ab oder legt gibt die Liste der Eingabe Verzeichnisse für den Auftrag an.
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
            Gibt an die Aktionen, die ausgeführt werden, bevor das Toolkit gestartet wird, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die angegebenen Aktionen werden auf allen Knoten ausführen, die Teil des Auftrags sind
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
            Ruft ab oder legt die Anzahl von Compute-Knoten, auf denen der Auftrag ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Auftrag wird Gang geplant werden, die viele Knoten berechnen
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
            Ruft ab oder legt gibt die Liste der Ausgabeverzeichnisse, in denen die Modelle erstellt werden. zu erstellen und zu verwalten.
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
            Ruft ab oder legt die Priorität, die dem Auftrag zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Priorität, die dem Auftrag zugeordnet werden. Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität. Der Standardwert ist 0.
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
            Ruft den Bereitstellungsstatus des Batch-AI-Auftrags ab. Folgende Werte sind möglich: "erstellen", "erfolgreich abgeschlossen", "fehlgeschlagen", "löschen"
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
            Ruft den Zeitpunkt, an dem der Auftrag seiner aktuellen Bereitstellungsstatus angenommen hat.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Zeitpunkt, an dem der Auftrag seiner aktuellen Bereitstellungsstatus angenommen hat.
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
            Ruft ab oder legt den Pfad fest, in dem der Batch AI-Dienst "stdout" und Stderror des Auftrags hochladen.
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
            Ruft ab oder legt ihn fest gibt die Einstellungen für den Auftrag Tensor fließen.
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
            Ruft ab, oder legt ihn fest den Toolkit-Typ des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Mögliche Werte sind: Cntk Tensorflow, Caffe, caffe2, Chainer, benutzerdefinierte. Folgende Werte sind möglich: "Cntk", "Tensorflow", "Caffe", "caffe2", "Chainer", "Benutzerdefiniert"
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>