<Type Name="VaultExtendedInfoResource" FullName="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource">
  <TypeSignature Language="C#" Value="public class VaultExtendedInfoResource : Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultExtendedInfoResource extends Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultExtendedInfoResource&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VaultExtendedInfoResource = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
    <AssemblyVersion>4.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="49555-101">Tresor erweiterte Informationen.</span><span class="sxs-lookup"><span data-stu-id="49555-101">Vault extended information.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultExtendedInfoResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="49555-102">Initialisiert eine neue Instanz der VaultExtendedInfoResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49555-102">Initializes a new instance of the VaultExtendedInfoResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultExtendedInfoResource (string id = null, string name = null, string type = null, string eTag = null, string integrityKey = null, string encryptionKey = null, string encryptionKeyThumbprint = null, string algorithm = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string eTag, string integrityKey, string encryptionKey, string encryptionKeyThumbprint, string algorithm) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional eTag As String = null, Optional integrityKey As String = null, Optional encryptionKey As String = null, Optional encryptionKeyThumbprint As String = null, Optional algorithm As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource (id, name, type, eTag, integrityKey, encryptionKey, encryptionKeyThumbprint, algorithm)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="integrityKey" Type="System.String" />
        <Parameter Name="encryptionKey" Type="System.String" />
        <Parameter Name="encryptionKeyThumbprint" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="49555-103">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</span><span class="sxs-lookup"><span data-stu-id="49555-103">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="49555-104">Ressourcennamen der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="49555-104">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="49555-105">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</span><span class="sxs-lookup"><span data-stu-id="49555-105">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="eTag"><span data-ttu-id="49555-106">Optionale ETag.</span><span class="sxs-lookup"><span data-stu-id="49555-106">Optional ETag.</span></span></param>
        <param name="integrityKey"><span data-ttu-id="49555-107">Schlüssel der Integrität.</span><span class="sxs-lookup"><span data-stu-id="49555-107">Integrity key.</span></span></param>
        <param name="encryptionKey"><span data-ttu-id="49555-108">Verschlüsselungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="49555-108">Encryption key.</span></span></param>
        <param name="encryptionKeyThumbprint"><span data-ttu-id="49555-109">Fingerabdruck des Verschlüsselungsschlüssels.</span><span class="sxs-lookup"><span data-stu-id="49555-109">Encryption key thumbprint.</span></span></param>
        <param name="algorithm"><span data-ttu-id="49555-110">Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="49555-110">Algorithm.</span></span></param>
        <summary>
            <span data-ttu-id="49555-111">Initialisiert eine neue Instanz der VaultExtendedInfoResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="49555-111">Initializes a new instance of the VaultExtendedInfoResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Algorithm">
      <MemberSignature Language="C#" Value="public string Algorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Algorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.Algorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property Algorithm As String" />
      <MemberSignature Language="F#" Value="member this.Algorithm : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.Algorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.algorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49555-112">Ruft ab oder legt der Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="49555-112">Gets or sets algorithm.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKey">
      <MemberSignature Language="C#" Value="public string EncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKey As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKey : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49555-113">Ruft ab, oder legt ihn fest Verschlüsselungsschlüssel.</span><span class="sxs-lookup"><span data-stu-id="49555-113">Gets or sets encryption key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeyThumbprint">
      <MemberSignature Language="C#" Value="public string EncryptionKeyThumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EncryptionKeyThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKeyThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionKeyThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeyThumbprint : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.EncryptionKeyThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryptionKeyThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49555-114">Abrufen oder Festlegen der Fingerabdruck des Verschlüsselungsschlüssels.</span><span class="sxs-lookup"><span data-stu-id="49555-114">Gets or sets encryption key thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntegrityKey">
      <MemberSignature Language="C#" Value="public string IntegrityKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IntegrityKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.IntegrityKey" />
      <MemberSignature Language="VB.NET" Value="Public Property IntegrityKey As String" />
      <MemberSignature Language="F#" Value="member this.IntegrityKey : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.VaultExtendedInfoResource.IntegrityKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.integrityKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="49555-115">Ruft ab oder legt Schlüssel der Integrität.</span><span class="sxs-lookup"><span data-stu-id="49555-115">Gets or sets integrity key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>