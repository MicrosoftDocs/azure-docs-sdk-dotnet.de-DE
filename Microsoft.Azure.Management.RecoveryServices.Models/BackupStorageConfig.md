<Type Name="BackupStorageConfig" FullName="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig">
  <TypeSignature Language="C#" Value="public class BackupStorageConfig : Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupStorageConfig extends Microsoft.Azure.Management.RecoveryServices.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupStorageConfig&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BackupStorageConfig = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="1ba79-101">Die backup-Storage-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="1ba79-101">The backup storage config.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupStorageConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ba79-102">Initialisiert eine neue Instanz der BackupStorageConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ba79-102">Initializes a new instance of the BackupStorageConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupStorageConfig (string id = null, string name = null, string type = null, string eTag = null, string storageModelType = null, string storageType = null, string storageTypeState = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string eTag, string storageModelType, string storageType, string storageTypeState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional eTag As String = null, Optional storageModelType As String = null, Optional storageType As String = null, Optional storageTypeState As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig : string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig" Usage="new Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig (id, name, type, eTag, storageModelType, storageType, storageTypeState)" />
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
        <Parameter Name="storageModelType" Type="System.String" />
        <Parameter Name="storageType" Type="System.String" />
        <Parameter Name="storageTypeState" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1ba79-103">Ressourcen-Id stellt den vollständigen Pfad zur Ressource dar.</span><span class="sxs-lookup"><span data-stu-id="1ba79-103">Resource Id represents the complete path to the resource.</span></span></param>
        <param name="name"><span data-ttu-id="1ba79-104">Ressourcennamen der Ressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="1ba79-104">Resource name associated with the resource.</span></span></param>
        <param name="type"><span data-ttu-id="1ba79-105">Ressourcentyp "" stellt den vollständigen Pfad des Formulars Namespace/ResourceType/ResourceType /...</span><span class="sxs-lookup"><span data-stu-id="1ba79-105">Resource type represents the complete path of the form Namespace/ResourceType/ResourceType/...</span></span></param>
        <param name="eTag"><span data-ttu-id="1ba79-106">Optionale ETag.</span><span class="sxs-lookup"><span data-stu-id="1ba79-106">Optional ETag.</span></span></param>
        <param name="storageModelType"><span data-ttu-id="1ba79-107">Speicher-Modelltyp.</span><span class="sxs-lookup"><span data-stu-id="1ba79-107">Storage model type.</span></span> <span data-ttu-id="1ba79-108">Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</span><span class="sxs-lookup"><span data-stu-id="1ba79-108">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span></param>
        <param name="storageType"><span data-ttu-id="1ba79-109">Speichertyp.</span><span class="sxs-lookup"><span data-stu-id="1ba79-109">Storage type.</span></span> <span data-ttu-id="1ba79-110">Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</span><span class="sxs-lookup"><span data-stu-id="1ba79-110">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span></param>
        <param name="storageTypeState"><span data-ttu-id="1ba79-111">Gesperrt oder entsperrt.</span><span class="sxs-lookup"><span data-stu-id="1ba79-111">Locked or Unlocked.</span></span> <span data-ttu-id="1ba79-112">Sobald ein Computer für eine Ressource registriert wurde, wird die StorageTypeState immer gesperrt.</span><span class="sxs-lookup"><span data-stu-id="1ba79-112">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="1ba79-113">Folgende Werte sind möglich: "Ungültig", "Gesperrt", "Gesperrt"</span><span class="sxs-lookup"><span data-stu-id="1ba79-113">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span></param>
        <summary>
            <span data-ttu-id="1ba79-114">Initialisiert eine neue Instanz der BackupStorageConfig-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ba79-114">Initializes a new instance of the BackupStorageConfig class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageModelType">
      <MemberSignature Language="C#" Value="public string StorageModelType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageModelType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageModelType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageModelType As String" />
      <MemberSignature Language="F#" Value="member this.StorageModelType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageModelType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageModelType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba79-115">Ruft ab oder legt ihn fest Speicher Modell.</span><span class="sxs-lookup"><span data-stu-id="1ba79-115">Gets or sets storage model type.</span></span> <span data-ttu-id="1ba79-116">Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</span><span class="sxs-lookup"><span data-stu-id="1ba79-116">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageType">
      <MemberSignature Language="C#" Value="public string StorageType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageType" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageType As String" />
      <MemberSignature Language="F#" Value="member this.StorageType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba79-117">Ruft ab oder legt ihn fest Speicher.</span><span class="sxs-lookup"><span data-stu-id="1ba79-117">Gets or sets storage type.</span></span> <span data-ttu-id="1ba79-118">Folgende Werte sind möglich: "Ungültig", "GeoRedundant", "LocallyRedundant"</span><span class="sxs-lookup"><span data-stu-id="1ba79-118">Possible values include: 'Invalid', 'GeoRedundant', 'LocallyRedundant'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageTypeState">
      <MemberSignature Language="C#" Value="public string StorageTypeState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageTypeState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageTypeState" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageTypeState As String" />
      <MemberSignature Language="F#" Value="member this.StorageTypeState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Models.BackupStorageConfig.StorageTypeState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices</AssemblyName>
        <AssemblyVersion>4.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageTypeState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba79-119">Ruft ab oder legt sie fest, gesperrt oder entsperrt.</span><span class="sxs-lookup"><span data-stu-id="1ba79-119">Gets or sets locked or Unlocked.</span></span> <span data-ttu-id="1ba79-120">Sobald ein Computer für eine Ressource registriert wurde, wird die StorageTypeState immer gesperrt.</span><span class="sxs-lookup"><span data-stu-id="1ba79-120">Once a machine is registered against a resource, the storageTypeState is always Locked.</span></span> <span data-ttu-id="1ba79-121">Folgende Werte sind möglich: "Ungültig", "Gesperrt", "Gesperrt"</span><span class="sxs-lookup"><span data-stu-id="1ba79-121">Possible values include: 'Invalid', 'Locked', 'Unlocked'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>