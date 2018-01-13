<Type Name="ProtectionPolicyResource" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource">
  <TypeSignature Language="C#" Value="public class ProtectionPolicyResource : Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectionPolicyResource extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectionPolicyResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ProtectionPolicyResource = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="bd53b-101">Die Basisklasse für die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="bd53b-101">Base class for backup policy.</span></span> <span data-ttu-id="bd53b-102">Spezifische Sicherungsrichtlinien werden von dieser Klasse abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="bd53b-102">Workload-specific backup policies are derived from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionPolicyResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bd53b-103">Initialisiert eine neue Instanz der ProtectionPolicyResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bd53b-103">Initializes a new instance of the ProtectionPolicyResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionPolicyResource (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string eTag = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string eTag, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional eTag As String = null, Optional properties As ProtectionPolicy = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource (id, name, type, location, tags, eTag, properties)" />
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
        <Parameter Name="properties" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="bd53b-104">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</span><span class="sxs-lookup"><span data-stu-id="bd53b-104">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="bd53b-105">Ressourcennamen der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bd53b-105">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="bd53b-106">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</span><span class="sxs-lookup"><span data-stu-id="bd53b-106">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="location"><span data-ttu-id="bd53b-107">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="bd53b-107">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="bd53b-108">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="bd53b-108">Resource tags.</span></span></param>
        <param name="eTag"><span data-ttu-id="bd53b-109">Optionale ETag.</span><span class="sxs-lookup"><span data-stu-id="bd53b-109">Optional ETag.</span></span></param>
        <param name="properties"><span data-ttu-id="bd53b-110">ProtectionPolicyResource-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="bd53b-110">ProtectionPolicyResource properties</span></span></param>
        <summary>
            <span data-ttu-id="bd53b-111">Initialisiert eine neue Instanz der ProtectionPolicyResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bd53b-111">Initializes a new instance of the ProtectionPolicyResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As ProtectionPolicy" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicyResource.Properties" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd53b-112">Ruft ab oder legt ihn fest ProtectionPolicyResource-Eigenschaften</span><span class="sxs-lookup"><span data-stu-id="bd53b-112">Gets or sets protectionPolicyResource properties</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>