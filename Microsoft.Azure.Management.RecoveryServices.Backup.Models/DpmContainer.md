<Type Name="DpmContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer">
  <TypeSignature Language="C#" Value="public class DpmContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type DpmContainer = class&#xA;    inherit ProtectionContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("DPMContainer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bdc50-101">DPM-Schutz arbeitsauslastungsspezifischen-Container.</span><span class="sxs-lookup"><span data-stu-id="bdc50-101">DPM workload-specific protection container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-102">Initialisiert eine neue Instanz der DpmContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bdc50-102">Initializes a new instance of the DpmContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, Nullable&lt;bool&gt; canReRegister = null, string containerId = null, Nullable&lt;long&gt; protectedItemCount = null, string dpmAgentVersion = null, System.Collections.Generic.IList&lt;string&gt; dPMServers = null, Nullable&lt;bool&gt; upgradeAvailable = null, string protectionStatus = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string containerId, valuetype System.Nullable`1&lt;int64&gt; protectedItemCount, string dpmAgentVersion, class System.Collections.Generic.IList`1&lt;string&gt; dPMServers, valuetype System.Nullable`1&lt;bool&gt; upgradeAvailable, string protectionStatus, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.Int64},System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional containerId As String = null, Optional protectedItemCount As Nullable(Of Long) = null, Optional dpmAgentVersion As String = null, Optional dPMServers As IList(Of String) = null, Optional upgradeAvailable As Nullable(Of Boolean) = null, Optional protectionStatus As String = null, Optional extendedInfo As DPMContainerExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer : string * string * string * string * string * Nullable&lt;bool&gt; * string * Nullable&lt;int64&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, canReRegister, containerId, protectedItemCount, dpmAgentVersion, dPMServers, upgradeAvailable, protectionStatus, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="registrationStatus" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="containerType" Type="System.String" />
        <Parameter Name="canReRegister" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="protectedItemCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="dpmAgentVersion" Type="System.String" />
        <Parameter Name="dPMServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="upgradeAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="protectionStatus" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="bdc50-103">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="bdc50-104">Typ der Sicherung Managemenent für den Container.</span><span class="sxs-lookup"><span data-stu-id="bdc50-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="bdc50-105">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="bdc50-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="bdc50-106">Status der Registrierung des Containers mit der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="bdc50-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="bdc50-107">Status der Integrität des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="bdc50-108">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-108">Type of the container.</span></span> <span data-ttu-id="bdc50-109">Der Wert dieser Eigenschaft für: 1.</span><span class="sxs-lookup"><span data-stu-id="bdc50-109">The value of this property for: 1.</span></span> <span data-ttu-id="bdc50-110">Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist.</span><span class="sxs-lookup"><span data-stu-id="bdc50-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="bdc50-111">Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3.</span><span class="sxs-lookup"><span data-stu-id="bdc50-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="bdc50-112">Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4.</span><span class="sxs-lookup"><span data-stu-id="bdc50-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="bdc50-113">Azure SQL-Instanz ist AzureSqlContainer.</span><span class="sxs-lookup"><span data-stu-id="bdc50-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="bdc50-114">Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</span><span class="sxs-lookup"><span data-stu-id="bdc50-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <param name="canReRegister"><span data-ttu-id="bdc50-115">Gibt an, ob der Container neu registrierbaren ist.</span><span class="sxs-lookup"><span data-stu-id="bdc50-115">Specifies whether the container is re-registrable.</span></span></param>
        <param name="containerId"><span data-ttu-id="bdc50-116">Die ID des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-116">ID of container.</span></span></param>
        <param name="protectedItemCount"><span data-ttu-id="bdc50-117">Anzahl geschützter Elemente in der BackupEngine</span><span class="sxs-lookup"><span data-stu-id="bdc50-117">Number of protected items in the BackupEngine</span></span></param>
        <param name="dpmAgentVersion"><span data-ttu-id="bdc50-118">Backup-Agent-Modulversion</span><span class="sxs-lookup"><span data-stu-id="bdc50-118">Backup engine Agent version</span></span></param>
        <param name="dPMServers"><span data-ttu-id="bdc50-119">Liste der BackupEngines schützen den container</span><span class="sxs-lookup"><span data-stu-id="bdc50-119">List of BackupEngines protecting the container</span></span></param>
        <param name="upgradeAvailable"><span data-ttu-id="bdc50-120">Beim Upgrade überprüfen verfügbar</span><span class="sxs-lookup"><span data-stu-id="bdc50-120">To check if upgrade available</span></span></param>
        <param name="protectionStatus"><span data-ttu-id="bdc50-121">Der Schutzstatus des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-121">Protection status of the container.</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="bdc50-122">Erweiterte Informationen des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-122">Extended Info of the container.</span></span></param>
        <summary>
            <span data-ttu-id="bdc50-123">Initialisiert eine neue Instanz der DpmContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bdc50-123">Initializes a new instance of the DpmContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReRegister">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CanReRegister { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CanReRegister" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.CanReRegister" />
      <MemberSignature Language="VB.NET" Value="Public Property CanReRegister As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CanReRegister : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.CanReRegister" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="canReRegister")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-124">Ruft ab oder legt gibt an, ob der Container neu registrierbaren ist.</span><span class="sxs-lookup"><span data-stu-id="bdc50-124">Gets or sets specifies whether the container is re-registrable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-125">Ruft ab oder legt die ID des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-125">Gets or sets ID of container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DpmAgentVersion">
      <MemberSignature Language="C#" Value="public string DpmAgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DpmAgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DpmAgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DpmAgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.DpmAgentVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DpmAgentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dpmAgentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-126">Ruft ab oder legt ihn fest Sicherungsmodul Agentversion</span><span class="sxs-lookup"><span data-stu-id="bdc50-126">Gets or sets backup engine Agent version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DPMServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DPMServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DPMServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DPMServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DPMServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DPMServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.DPMServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="DPMServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-127">Ruft ab oder legt die Liste der BackupEngines schützen den container</span><span class="sxs-lookup"><span data-stu-id="bdc50-127">Gets or sets list of BackupEngines protecting the container</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As DPMContainerExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ExtendedInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extendedInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-128">Abrufen oder Festlegen der erweiterten Informationen des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-128">Gets or sets extended Info of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProtectedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProtectedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectedItemCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-129">Ruft ab oder legt die Anzahl der geschützten Elemente in der BackupEngine fest</span><span class="sxs-lookup"><span data-stu-id="bdc50-129">Gets or sets number of protected items in the BackupEngine</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionStatus">
      <MemberSignature Language="C#" Value="public string ProtectionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.ProtectionStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectionStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-130">Ruft ab, oder legt ihn fest Schutzstatus des Containers.</span><span class="sxs-lookup"><span data-stu-id="bdc50-130">Gets or sets protection status of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.UpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmContainer.UpgradeAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="UpgradeAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bdc50-131">Ruft ab oder legt ihn fest, beim Überprüfen upgrade verfügbar</span><span class="sxs-lookup"><span data-stu-id="bdc50-131">Gets or sets to check if upgrade available</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>