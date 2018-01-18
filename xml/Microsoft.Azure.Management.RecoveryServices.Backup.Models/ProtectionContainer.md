<Type Name="ProtectionContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer">
  <TypeSignature Language="C#" Value="public class ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProtectionContainer extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class ProtectionContainer" />
  <TypeSignature Language="F#" Value="type ProtectionContainer = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e3049-101">Die Basisklasse für Container und Elemente für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="e3049-101">Base class for container with backup items.</span></span> <span data-ttu-id="e3049-102">Container mit bestimmten arbeitsauslastungen werden von dieser Klasse abgeleitet.</span><span class="sxs-lookup"><span data-stu-id="e3049-102">Containers with specific workloads are derived from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e3049-103">Initialisiert eine neue Instanz der ProtectionContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3049-103">Initializes a new instance of the ProtectionContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProtectionContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType)" />
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
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="e3049-104">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="e3049-104">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="e3049-105">Typ der Sicherung Managemenent für den Container.</span><span class="sxs-lookup"><span data-stu-id="e3049-105">Type of backup managemenent for the container.</span></span> <span data-ttu-id="e3049-106">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="e3049-106">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="e3049-107">Status der Registrierung des Containers mit der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e3049-107">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="e3049-108">Status der Integrität des Containers.</span><span class="sxs-lookup"><span data-stu-id="e3049-108">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="e3049-109">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="e3049-109">Type of the container.</span></span> <span data-ttu-id="e3049-110">Der Wert dieser Eigenschaft für: 1.</span><span class="sxs-lookup"><span data-stu-id="e3049-110">The value of this property for: 1.</span></span> <span data-ttu-id="e3049-111">Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist.</span><span class="sxs-lookup"><span data-stu-id="e3049-111">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="e3049-112">Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3.</span><span class="sxs-lookup"><span data-stu-id="e3049-112">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="e3049-113">Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4.</span><span class="sxs-lookup"><span data-stu-id="e3049-113">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="e3049-114">Azure SQL-Instanz ist AzureSqlContainer.</span><span class="sxs-lookup"><span data-stu-id="e3049-114">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="e3049-115">Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</span><span class="sxs-lookup"><span data-stu-id="e3049-115">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <summary>
            <span data-ttu-id="e3049-116">Initialisiert eine neue Instanz der ProtectionContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3049-116">Initializes a new instance of the ProtectionContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.BackupManagementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupManagementType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3049-117">Ruft ab oder legt ihn fest backup Managemenent für den Container.</span><span class="sxs-lookup"><span data-stu-id="e3049-117">Gets or sets type of backup managemenent for the container.</span></span>
            <span data-ttu-id="e3049-118">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="e3049-118">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerType">
      <MemberSignature Language="C#" Value="public string ContainerType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.ContainerType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerType As String" />
      <MemberSignature Language="F#" Value="member this.ContainerType : string" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.ContainerType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3049-119">Ruft den Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="e3049-119">Gets type of the container.</span></span> <span data-ttu-id="e3049-120">Der Wert dieser Eigenschaft für: 1.</span><span class="sxs-lookup"><span data-stu-id="e3049-120">The value of this property for: 1.</span></span>
            <span data-ttu-id="e3049-121">Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist.</span><span class="sxs-lookup"><span data-stu-id="e3049-121">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="e3049-122">Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3.</span><span class="sxs-lookup"><span data-stu-id="e3049-122">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span>
            <span data-ttu-id="e3049-123">Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4.</span><span class="sxs-lookup"><span data-stu-id="e3049-123">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="e3049-124">Azure SQL-Instanz ist AzureSqlContainer.</span><span class="sxs-lookup"><span data-stu-id="e3049-124">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="e3049-125">Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</span><span class="sxs-lookup"><span data-stu-id="e3049-125">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3049-126">Ruft ab oder legt angezeigten Namen des Containers.</span><span class="sxs-lookup"><span data-stu-id="e3049-126">Gets or sets friendly name of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatus">
      <MemberSignature Language="C#" Value="public string HealthStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.HealthStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatus As String" />
      <MemberSignature Language="F#" Value="member this.HealthStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.HealthStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="healthStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3049-127">Abrufen oder Festlegen des Status der Integrität des Containers.</span><span class="sxs-lookup"><span data-stu-id="e3049-127">Gets or sets status of health of the container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public string RegistrationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationStatus As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registrationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e3049-128">Abrufen oder Festlegen des Status der Registrierung des Containers mit der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="e3049-128">Gets or sets status of registration of the container with the Recovery Services Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>