<Type Name="BackupResourceVaultConfigResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource">
  <TypeSignature Language="C#" Value="public class BackupResourceVaultConfigResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupResourceVaultConfigResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupResourceVaultConfigResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupResourceVaultConfigResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="a3804-101">Backup-Tresor Config Ressourcendetails.</span><span class="sxs-lookup"><span data-stu-id="a3804-101">Backup resource vault config details.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceVaultConfigResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a3804-102">Initialisiert eine neue Instanz der BackupResourceVaultConfigResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3804-102">Initializes a new instance of the BackupResourceVaultConfigResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupResourceVaultConfigResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As BackupResourceVaultConfig = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource (id, name, type, location, tags, eTag, properties)" />
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
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="a3804-103">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</span><span class="sxs-lookup"><span data-stu-id="a3804-103">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="a3804-104">Ressourcennamen der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a3804-104">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="a3804-105">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</span><span class="sxs-lookup"><span data-stu-id="a3804-105">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="location"><span data-ttu-id="a3804-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="a3804-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="a3804-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="a3804-107">Resource tags.</span></span></param>
        <param name="eTag"><span data-ttu-id="a3804-108">Optionale ETag.</span><span class="sxs-lookup"><span data-stu-id="a3804-108">Optional ETag.</span></span></param>
        <param name="properties"><span data-ttu-id="a3804-109">BackupResourceVaultConfigResource-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="a3804-109">BackupResourceVaultConfigResource properties</span></span></param>
        <summary>
            <span data-ttu-id="a3804-110">Initialisiert eine neue Instanz der BackupResourceVaultConfigResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3804-110">Initializes a new instance of the BackupResourceVaultConfigResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As BackupResourceVaultConfig" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfigResource.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupResourceVaultConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a3804-111">Ruft ab oder legt ihn fest BackupResourceVaultConfigResource-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="a3804-111">Gets or sets backupResourceVaultConfigResource properties</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>