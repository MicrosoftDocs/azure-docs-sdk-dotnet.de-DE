<Type Name="IaasVMRestoreRequest" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest">
  <TypeSignature Language="C#" Value="public class IaasVMRestoreRequest : Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaasVMRestoreRequest extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class IaasVMRestoreRequest&#xA;Inherits RestoreRequest" />
  <TypeSignature Language="F#" Value="type IaasVMRestoreRequest = class&#xA;    inherit RestoreRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.RestoreRequest</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="18ad9-101">IaaS-VM arbeitsauslastungsspezifischen wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="18ad9-101">IaaS VM workload-specific restore.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMRestoreRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-102">Initialisiert eine neue Instanz der IaasVMRestoreRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="18ad9-102">Initializes a new instance of the IaasVMRestoreRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaasVMRestoreRequest (string recoveryPointId = null, string recoveryType = null, string sourceResourceId = null, string targetVirtualMachineId = null, string targetResourceGroupId = null, string storageAccountId = null, string virtualNetworkId = null, string subnetId = null, string targetDomainNameId = null, string region = null, string affinityGroup = null, Nullable&lt;bool&gt; createNewCloudService = null, Nullable&lt;bool&gt; originalStorageAccountOption = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails encryptionDetails = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string recoveryPointId, string recoveryType, string sourceResourceId, string targetVirtualMachineId, string targetResourceGroupId, string storageAccountId, string virtualNetworkId, string subnetId, string targetDomainNameId, string region, string affinityGroup, valuetype System.Nullable`1&lt;bool&gt; createNewCloudService, valuetype System.Nullable`1&lt;bool&gt; originalStorageAccountOption, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails encryptionDetails) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest : string * string * string * string * string * string * string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest (recoveryPointId, recoveryType, sourceResourceId, targetVirtualMachineId, targetResourceGroupId, storageAccountId, virtualNetworkId, subnetId, targetDomainNameId, region, affinityGroup, createNewCloudService, originalStorageAccountOption, encryptionDetails)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recoveryPointId" Type="System.String" />
        <Parameter Name="recoveryType" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
        <Parameter Name="targetVirtualMachineId" Type="System.String" />
        <Parameter Name="targetResourceGroupId" Type="System.String" />
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="virtualNetworkId" Type="System.String" />
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="targetDomainNameId" Type="System.String" />
        <Parameter Name="region" Type="System.String" />
        <Parameter Name="affinityGroup" Type="System.String" />
        <Parameter Name="createNewCloudService" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="originalStorageAccountOption" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="encryptionDetails" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails" />
      </Parameters>
      <Docs>
        <param name="recoveryPointId"><span data-ttu-id="18ad9-103">ID der Sicherungskopie wiederhergestellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="18ad9-103">ID of the backup copy to be recovered.</span></span></param>
        <param name="recoveryType"><span data-ttu-id="18ad9-104">Der Typ dieser Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="18ad9-104">Type of this recovery.</span></span> <span data-ttu-id="18ad9-105">Folgende Werte sind möglich: "Ungültig", "OriginalLocation", "AlternateLocation", "RestoreDisks"</span><span class="sxs-lookup"><span data-stu-id="18ad9-105">Possible values include: 'Invalid', 'OriginalLocation', 'AlternateLocation', 'RestoreDisks'</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="18ad9-106">Vollqualifizierte ARM-ID des virtuellen Computers die wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-106">Fully qualified ARM ID of the VM which is being recovered.</span></span></param>
        <param name="targetVirtualMachineId"><span data-ttu-id="18ad9-107">Dies ist die vollständige ARM-Id des virtuellen Computers, der erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-107">This is the complete ARM Id of the VM that will be created.</span></span>
            <span data-ttu-id="18ad9-108">Für z. B. /subscriptions/{subId}/resourcegroups/{rg}/provider/Microsoft.Compute/virtualmachines/{vm}</span><span class="sxs-lookup"><span data-stu-id="18ad9-108">For e.g. /subscriptions/{subId}/resourcegroups/{rg}/provider/Microsoft.Compute/virtualmachines/{vm}</span></span></param>
        <param name="targetResourceGroupId"><span data-ttu-id="18ad9-109">Dies ist die ARM-Id der Ressourcengruppe, die Sie für diesen virtuellen Computer und anderen Artefakten erstellen möchten.</span><span class="sxs-lookup"><span data-stu-id="18ad9-109">This is the ARM Id of the resource group that you want to create for this Virtual machine and other artifacts.</span></span>
            <span data-ttu-id="18ad9-110">Für z. B./Subscriptions / {SubId} / ResourceGroups / {Rg}</span><span class="sxs-lookup"><span data-stu-id="18ad9-110">For e.g. /subscriptions/{subId}/resourcegroups/{rg}</span></span></param>
        <param name="storageAccountId"><span data-ttu-id="18ad9-111">Vollqualifizierte ARM-ID des Speicherkontos zu dem der virtuelle Computer muss wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="18ad9-111">Fully qualified ARM ID of the storage account to which the VM has to be restored.</span></span></param>
        <param name="virtualNetworkId"><span data-ttu-id="18ad9-112">Dies ist das virtuelle Netzwerk-Id des vnets, die an den virtuellen Computer angefügt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-112">This is the virtual network Id of the vnet that will be attached to the virtual machine.</span></span>
            <span data-ttu-id="18ad9-113">Benutzer werden Berechtigungen in der verknüpften Access Join überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="18ad9-113">User will be validated for join action permissions in the linked access.</span></span></param>
        <param name="subnetId"><span data-ttu-id="18ad9-114">Subnetz-ID ist im Subnetz-ID zugeordnet der werden VM wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="18ad9-114">Subnet ID, is the subnet ID associated with the to be restored VM.</span></span> <span data-ttu-id="18ad9-115">Für klassische virtuelle Computer wäre {VnetID} /Subnet/ {SubnetName}, und für die Azure-Ressourcen-Manager für virtuellen Computer wäre es ARM-Ressourcen-ID verwendet, um das Subnetz darzustellen.</span><span class="sxs-lookup"><span data-stu-id="18ad9-115">For Classic VMs it would be {VnetID}/Subnet/{SubnetName} and, for the Azure Resource Manager VMs it would be ARM resource ID used to represent the subnet.</span></span></param>
        <param name="targetDomainNameId"><span data-ttu-id="18ad9-116">Vollqualifizierte ARM-ID des Domänennamens zugeordnet, mit dem virtuellen Computer wiederhergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="18ad9-116">Fully qualified ARM ID of the domain name to be associated to the VM being restored.</span></span> <span data-ttu-id="18ad9-117">Dies gilt nur, klassische virtuelle Computer.</span><span class="sxs-lookup"><span data-stu-id="18ad9-117">This applies only to Classic Virtual Machines.</span></span></param>
        <param name="region"><span data-ttu-id="18ad9-118">Die Region, in dem der virtuelle Computer wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-118">Region in which the virtual machine is restored.</span></span></param>
        <param name="affinityGroup"><span data-ttu-id="18ad9-119">Die Affinitätsgruppe, virtuelle Computer wiederhergestellt werden, zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="18ad9-119">Affinity group associated to VM to be restored.</span></span> <span data-ttu-id="18ad9-120">Nur für klassische Compute virtuelle Maschinen verwendet.</span><span class="sxs-lookup"><span data-stu-id="18ad9-120">Used only for Classic Compute Virtual Machines.</span></span></param>
        <param name="createNewCloudService"><span data-ttu-id="18ad9-121">Ein neuen Clouddienst beim Wiederherstellen des virtuellen Computers erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="18ad9-121">Should a new cloud service be created while restoring the VM.</span></span> <span data-ttu-id="18ad9-122">Wenn dies falsch ist, wird VM zum selben Clouddienst wiederhergestellt werden, zum Zeitpunkt der Sicherung vorlag.</span><span class="sxs-lookup"><span data-stu-id="18ad9-122">If this is false, VM will be restored to the same cloud service as it was at the time of backup.</span></span></param>
        <param name="originalStorageAccountOption">To be added.</param>
        <param name="encryptionDetails"><span data-ttu-id="18ad9-123">Details erforderlich, wenn die VM zum Zeitpunkt der Sicherung verschlüsselt wurde.</span><span class="sxs-lookup"><span data-stu-id="18ad9-123">Details needed if the VM was encrypted at the time of backup.</span></span></param>
        <summary>
            <span data-ttu-id="18ad9-124">Initialisiert eine neue Instanz der IaasVMRestoreRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="18ad9-124">Initializes a new instance of the IaasVMRestoreRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityGroup">
      <MemberSignature Language="C#" Value="public string AffinityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.AffinityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityGroup As String" />
      <MemberSignature Language="F#" Value="member this.AffinityGroup : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.AffinityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-125">Ruft ab, oder legt ihn fest Affinitätsgruppe verknüpften virtuellen Computer wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="18ad9-125">Gets or sets affinity group associated to VM to be restored.</span></span> <span data-ttu-id="18ad9-126">Nur für klassische Compute virtuelle Maschinen verwendet.</span><span class="sxs-lookup"><span data-stu-id="18ad9-126">Used only for Classic Compute Virtual Machines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNewCloudService">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CreateNewCloudService { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CreateNewCloudService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.CreateNewCloudService" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateNewCloudService As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CreateNewCloudService : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.CreateNewCloudService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createNewCloudService")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-127">Ruft ab oder legt ihn fest sollten beim Wiederherstellen des virtuellen Computers ein neuen Clouddienst erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="18ad9-127">Gets or sets should a new cloud service be created while restoring the VM.</span></span> <span data-ttu-id="18ad9-128">Wenn dies falsch ist, wird VM zum selben Clouddienst wiederhergestellt werden, zum Zeitpunkt der Sicherung vorlag.</span><span class="sxs-lookup"><span data-stu-id="18ad9-128">If this is false, VM will be restored to the same cloud service as it was at the time of backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionDetails">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails EncryptionDetails { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails EncryptionDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.EncryptionDetails" />
      <MemberSignature Language="VB.NET" Value="Public Property EncryptionDetails As EncryptionDetails" />
      <MemberSignature Language="F#" Value="member this.EncryptionDetails : Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.EncryptionDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encryptionDetails")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.EncryptionDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-129">Ruft ab, oder legt ihn fest Details erforderlich, wenn die VM zum Zeitpunkt der Sicherung verschlüsselt wurde.</span><span class="sxs-lookup"><span data-stu-id="18ad9-129">Gets or sets details needed if the VM was encrypted at the time of backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginalStorageAccountOption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OriginalStorageAccountOption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OriginalStorageAccountOption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.OriginalStorageAccountOption" />
      <MemberSignature Language="VB.NET" Value="Public Property OriginalStorageAccountOption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OriginalStorageAccountOption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.OriginalStorageAccountOption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="originalStorageAccountOption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryPointId">
      <MemberSignature Language="C#" Value="public string RecoveryPointId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryPointId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryPointId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryPointId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryPointId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryPointId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryPointId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-130">Ruft ab oder legt die ID der Sicherungskopie wiederhergestellt werden sollen.</span><span class="sxs-lookup"><span data-stu-id="18ad9-130">Gets or sets ID of the backup copy to be recovered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryType">
      <MemberSignature Language="C#" Value="public string RecoveryType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryType" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryType As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.RecoveryType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recoveryType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-131">Ruft ab oder legt ihn fest diese Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="18ad9-131">Gets or sets type of this recovery.</span></span> <span data-ttu-id="18ad9-132">Folgende Werte sind möglich: "Ungültig", "OriginalLocation", "AlternateLocation", "RestoreDisks"</span><span class="sxs-lookup"><span data-stu-id="18ad9-132">Possible values include: 'Invalid', 'OriginalLocation', 'AlternateLocation', 'RestoreDisks'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public string Region { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.Region" />
      <MemberSignature Language="VB.NET" Value="Public Property Region As String" />
      <MemberSignature Language="F#" Value="member this.Region : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="region")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-133">Ruft ab, oder legt ihn fest Region, in dem der virtuelle Computer wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-133">Gets or sets region in which the virtual machine is restored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceResourceId">
      <MemberSignature Language="C#" Value="public string SourceResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SourceResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceResourceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceResourceId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SourceResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-134">Ruft ab, oder legt ihn fest vollqualifizierte ARM-ID des virtuellen Computers die wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-134">Gets or sets fully qualified ARM ID of the VM which is being recovered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountId">
      <MemberSignature Language="C#" Value="public string StorageAccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.StorageAccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccountId As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.StorageAccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageAccountId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-135">Ruft ab, oder legt ihn fest vollqualifizierte ARM-ID des Speicherkontos zu dem der virtuelle Computer muss wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="18ad9-135">Gets or sets fully qualified ARM ID of the storage account to which the VM has to be restored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-136">Ruft ab oder legt die Subnetz-ID, die Subnetz-ID zugeordnet ist die werden VM wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="18ad9-136">Gets or sets subnet ID, is the subnet ID associated with the to be restored VM.</span></span> <span data-ttu-id="18ad9-137">Für klassische virtuelle Computer wäre {VnetID} /Subnet/ {SubnetName}, und für die Azure-Ressourcen-Manager für virtuellen Computer wäre es ARM-Ressourcen-ID verwendet, um das Subnetz darzustellen.</span><span class="sxs-lookup"><span data-stu-id="18ad9-137">For Classic VMs it would be {VnetID}/Subnet/{SubnetName} and, for the Azure Resource Manager VMs it would be ARM resource ID used to represent the subnet.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetDomainNameId">
      <MemberSignature Language="C#" Value="public string TargetDomainNameId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetDomainNameId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetDomainNameId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetDomainNameId As String" />
      <MemberSignature Language="F#" Value="member this.TargetDomainNameId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetDomainNameId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetDomainNameId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-138">Ruft ab, oder legt ihn fest vollqualifizierte ARM-ID des Domänennamens zugeordnet, mit dem virtuellen Computer wiederhergestellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="18ad9-138">Gets or sets fully qualified ARM ID of the domain name to be associated to the VM being restored.</span></span> <span data-ttu-id="18ad9-139">Dies gilt nur, klassische virtuelle Computer.</span><span class="sxs-lookup"><span data-stu-id="18ad9-139">This applies only to Classic Virtual Machines.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetResourceGroupId">
      <MemberSignature Language="C#" Value="public string TargetResourceGroupId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetResourceGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetResourceGroupId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetResourceGroupId As String" />
      <MemberSignature Language="F#" Value="member this.TargetResourceGroupId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetResourceGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetResourceGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-140">Ruft ab oder legt sie fest, ist dies die ARM-Id der Ressourcengruppe, die Sie für diesen virtuellen Computer und anderen Artefakten erstellen möchten.</span><span class="sxs-lookup"><span data-stu-id="18ad9-140">Gets or sets this is the ARM Id of the resource group that you want to create for this Virtual machine and other artifacts.</span></span>
            <span data-ttu-id="18ad9-141">Für z. B./Subscriptions / {SubId} / ResourceGroups / {Rg}</span><span class="sxs-lookup"><span data-stu-id="18ad9-141">For e.g. /subscriptions/{subId}/resourcegroups/{rg}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetVirtualMachineId">
      <MemberSignature Language="C#" Value="public string TargetVirtualMachineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetVirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetVirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetVirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.TargetVirtualMachineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.TargetVirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetVirtualMachineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-142">Ruft ab oder legt ihn fest, ist dies die vollständige ARM-Id des virtuellen Computers, der erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-142">Gets or sets this is the complete ARM Id of the VM that will be created.</span></span>
            <span data-ttu-id="18ad9-143">Für z. B. /subscriptions/{subId}/resourcegroups/{rg}/provider/Microsoft.Compute/virtualmachines/{vm}</span><span class="sxs-lookup"><span data-stu-id="18ad9-143">For e.g. /subscriptions/{subId}/resourcegroups/{rg}/provider/Microsoft.Compute/virtualmachines/{vm}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkId">
      <MemberSignature Language="C#" Value="public string VirtualNetworkId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.VirtualNetworkId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaasVMRestoreRequest.VirtualNetworkId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualNetworkId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="18ad9-144">Ruft ab oder legt sie fest, ist dies das virtuelle Netzwerk-Id des vnets, die an den virtuellen Computer angefügt wird.</span><span class="sxs-lookup"><span data-stu-id="18ad9-144">Gets or sets this is the virtual network Id of the vnet that will be attached to the virtual machine.</span></span>
            <span data-ttu-id="18ad9-145">Benutzer werden Berechtigungen in der verknüpften Access Join überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="18ad9-145">User will be validated for join action permissions in the linked access.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>