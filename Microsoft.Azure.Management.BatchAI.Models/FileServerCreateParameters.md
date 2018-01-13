<Type Name="FileServerCreateParameters" FullName="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters">
  <TypeSignature Language="C#" Value="public class FileServerCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileServerCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class FileServerCreateParameters" />
  <TypeSignature Language="F#" Value="type FileServerCreateParameters = class" />
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
      <MemberSignature Language="C#" Value="public FileServerCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der FileServerCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerCreateParameters (string location, string vmSize, Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration, Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string vmSize, class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration, class Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.#ctor(System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.SshConfiguration,Microsoft.Azure.Management.BatchAI.Models.DataDisks,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.BatchAI.Models.ResourceId)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters : string * string * Microsoft.Azure.Management.BatchAI.Models.SshConfiguration * Microsoft.Azure.Management.BatchAI.Models.DataDisks * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.BatchAI.Models.ResourceId -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters" Usage="new Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters (location, vmSize, sshConfiguration, dataDisks, tags, subnet)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="sshConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration" />
        <Parameter Name="dataDisks" Type="Microsoft.Azure.Management.BatchAI.Models.DataDisks" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
      </Parameters>
      <Docs>
        <param name="location">Die Region, in dem der Dateiserver erstellt werden soll.</param>
        <param name="vmSize">Die Größe des virtuellen Computers des Dateiservers.</param>
        <param name="sshConfiguration">SSH-Einstellungen für den Dateiserver.</param>
        <param name="dataDisks">Einstellungen für den Datenträger, der für den Dateiserver erstellt würde.</param>
        <param name="tags">Der benutzerdefinierte Tags, die Dateiserver zugeordnet.</param>
        <param name="subnet">Gibt den Bezeichner des Subnetzes.</param>
        <summary>
            Initialisiert eine neue Instanz der FileServerCreateParameters-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As DataDisks" />
      <MemberSignature Language="F#" Value="member this.DataDisks : Microsoft.Azure.Management.BatchAI.Models.DataDisks with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.DataDisks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Einstellungen für den Datenträger, der erstellt wird, für den Dateiserver.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Location" />
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
            Ruft ab oder legt die Region, in dem der Dateiserver erstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.SshConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property SshConfiguration As SshConfiguration" />
      <MemberSignature Language="F#" Value="member this.SshConfiguration : Microsoft.Azure.Management.BatchAI.Models.SshConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.SshConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sshConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest SSH-Einstellungen für den Dateiserver.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Subnet" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Tags" />
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
            Ruft ab oder legt angegebene Benutzer die Dateiserver zugeordneten Tags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileServerCreateParameters.Validate " />
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
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerCreateParameters.VmSize" />
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
            Ruft ab oder legt die Größe des virtuellen Computers des Dateiservers.
            </summary>
        <value>To be added.</value>
        <remarks>
            Informationen zu den verfügbaren VM-Größen für Dateiserver aus dem Marketplace für virtuelle Maschinen finden Sie unter Größen für virtuelle Maschinen (Linux).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>