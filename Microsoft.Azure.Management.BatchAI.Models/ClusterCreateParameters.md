<Type Name="ClusterCreateParameters" FullName="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters">
  <TypeSignature Language="C#" Value="public class ClusterCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterCreateParameters" />
  <TypeSignature Language="F#" Value="type ClusterCreateParameters = class" />
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
            Parameter, die auf den Erstellungsvorgang angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ClusterCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterCreateParameters (string location, string vmSize, Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority = null, Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string vmSize, class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority, class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration, class Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings,System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{Microsoft.Azure.Management.BatchAI.Models.VmPriority},Microsoft.Azure.Management.BatchAI.Models.ScaleSettings,Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration,Microsoft.Azure.Management.BatchAI.Models.NodeSetup,Microsoft.Azure.Management.BatchAI.Models.ResourceId)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters : string * string * Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; * Microsoft.Azure.Management.BatchAI.Models.ScaleSettings * Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration * Microsoft.Azure.Management.BatchAI.Models.NodeSetup * Microsoft.Azure.Management.BatchAI.Models.ResourceId -&gt; Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters" Usage="new Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters (location, vmSize, userAccountSettings, tags, vmPriority, scaleSettings, virtualMachineConfiguration, nodeSetup, subnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="userAccountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmPriority" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration" />
        <Parameter Name="nodeSetup" Type="Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
      </Parameters>
      <Docs>
        <param name="location">Die Region, in der zum Erstellen des Clusters wird.</param>
        <param name="vmSize">Die Größe der virtuellen Computer im Cluster.</param>
        <param name="userAccountSettings">Einstellungen für das Benutzerkonto, das auf allen Serverknoten des Clusters erstellt werden soll.</param>
        <param name="tags">Der benutzerdefinierte Tags, die dem Cluster zugeordnet.</param>
        <param name="vmPriority">dedizierte oder Lowpriority.</param>
        <param name="scaleSettings">Gewünschte Skalierung für den Cluster.</param>
        <param name="virtualMachineConfiguration">Einstellungen für das Betriebssystem-Image und Datenvolumes bereitgestellt.</param>
        <param name="nodeSetup">Setup, um auf allen Serverknoten im Cluster ausgeführt werden.</param>
        <param name="subnet">Gibt den Bezeichner des Subnetzes.
            </param>
        <summary>
            Initialisiert eine neue Instanz der ClusterCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Location" />
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
            Ruft ab oder legt die Region, in der zum Erstellen des Clusters.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeSetup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.NodeSetup" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeSetup As NodeSetup" />
      <MemberSignature Language="F#" Value="member this.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.NodeSetup with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.NodeSetup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeSetup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.NodeSetup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Setup auf allen Serverknoten im Cluster ausgeführt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.BatchAI.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest gewünschte Skalierung für den Cluster.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den Bezeichner des Subnetzes an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Tags" />
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
            Ruft ab oder legt fest, die der Benutzer mit dem Cluster verbundenen Tags angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.UserAccountSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccountSettings As UserAccountSettings" />
      <MemberSignature Language="F#" Value="member this.UserAccountSettings : Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.UserAccountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Einstellungen für das Benutzerkonto, das auf allen Serverknoten des Clusters erstellt werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="clusterCreateParameters.Validate " />
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
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Einstellungen für Betriebssystem-Image und Datenvolumes bereitgestellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmPriority">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmPriority" />
      <MemberSignature Language="VB.NET" Value="Public Property VmPriority As Nullable(Of VmPriority)" />
      <MemberSignature Language="F#" Value="member this.VmPriority : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmPriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmPriority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder dedizierte Gruppen oder Lowpriority.
            </summary>
        <value>To be added.</value>
        <remarks>
            Standardmäßig dient. Folgende Werte sind möglich: "dediziertes", "Lowpriority"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.ClusterCreateParameters.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe der virtuellen Computer im Cluster.
            </summary>
        <value>To be added.</value>
        <remarks>
            Alle virtuellen Computer in einem Cluster haben die gleiche Größe. Informationen zu den verfügbaren VM-Größen für Cluster, die mithilfe von Images von virtuellen Maschinen Marketplace (Siehe Größen für virtuelle Maschinen (Linux) oder Größen für virtuelle Computer (Windows). AI-Batch-Dienst unterstützt alle Azure-VM-Größen außer STANDARD_A0 und die mit Premium-Speicher (STANDARD_GS STANDARD_DS und STANDARD_DSV2-Serie).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>