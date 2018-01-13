<Type Name="BackupResourceConfigResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource">
  <TypeSignature Language="C#" Value="public class BackupResourceConfigResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupResourceConfigResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupResourceConfigResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupResourceConfigResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="d31cb-101">Die Details des Ressource-Speicher.</span><span class="sxs-lookup"><span data-stu-id="d31cb-101">The resource storage details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceConfigResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d31cb-102">Initialisiert eine neue Instanz der BackupResourceConfigResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d31cb-102">Initializes a new instance of the BackupResourceConfigResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceConfigResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As BackupResourceConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource (id, name, type, location, tags, eTag, properties)" />
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
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="d31cb-103">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</span><span class="sxs-lookup"><span data-stu-id="d31cb-103">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="d31cb-104">Ressourcennamen der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="d31cb-104">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="d31cb-105">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</span><span class="sxs-lookup"><span data-stu-id="d31cb-105">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="location"><span data-ttu-id="d31cb-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="d31cb-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="d31cb-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="d31cb-107">Resource tags.</span></span></param>
        <param name="eTag"><span data-ttu-id="d31cb-108">Optionale ETag.</span><span class="sxs-lookup"><span data-stu-id="d31cb-108">Optional ETag.</span></span></param>
        <param name="properties"><span data-ttu-id="d31cb-109">BackupResourceConfigResource-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="d31cb-109">BackupResourceConfigResource properties</span></span></param>
        <summary>
            <span data-ttu-id="d31cb-110">Initialisiert eine neue Instanz der BackupResourceConfigResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d31cb-110">Initializes a new instance of the BackupResourceConfigResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As BackupResourceConfig" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfigResource.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d31cb-111">Ruft ab oder legt ihn fest BackupResourceConfigResource-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="d31cb-111">Gets or sets backupResourceConfigResource properties</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>