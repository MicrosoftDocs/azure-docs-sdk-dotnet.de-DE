<Type Name="JobResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource">
  <TypeSignature Language="C#" Value="public class JobResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource" />
  <TypeSignature Language="VB.NET" Value="Public Class JobResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type JobResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Definiert die Arbeitslast agnostisch Eigenschaften für einen Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As Job = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource (id, name, type, location, tags, eTag, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</param>
        <param name="name">Ressourcennamen der Ressource zugeordnet.</param>
        <param name="type">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</param>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="eTag">Optionale ETag.</param>
        <param name="properties">JobResource-Eigenschaften</param>
        <summary>
            Initialisiert eine neue Instanz der JobResource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As Job" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobResource.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.Job</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest JobResource-Eigenschaften
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>