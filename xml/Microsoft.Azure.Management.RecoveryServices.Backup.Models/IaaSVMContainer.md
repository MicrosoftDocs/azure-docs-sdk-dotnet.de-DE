<Type Name="IaaSVMContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer">
  <TypeSignature Language="C#" Value="public class IaaSVMContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaaSVMContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class IaaSVMContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type IaaSVMContainer = class&#xA;    inherit ProtectionContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="82770-101">IaaS-VM-spezifische-Container.</span><span class="sxs-lookup"><span data-stu-id="82770-101">IaaS VM workload-specific container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaaSVMContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="82770-102">Initialisiert eine neue Instanz der IaaSVMContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="82770-102">Initializes a new instance of the IaaSVMContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaaSVMContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, string virtualMachineId = null, string virtualMachineVersion = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, string virtualMachineId, string virtualMachineVersion, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional virtualMachineId As String = null, Optional virtualMachineVersion As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, virtualMachineId, virtualMachineVersion, resourceGroup)" />
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
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="virtualMachineVersion" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="82770-103">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="82770-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="82770-104">Typ der Sicherung Managemenent für den Container.</span><span class="sxs-lookup"><span data-stu-id="82770-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="82770-105">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="82770-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="82770-106">Status der Registrierung des Containers mit der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="82770-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="82770-107">Status der Integrität des Containers.</span><span class="sxs-lookup"><span data-stu-id="82770-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="82770-108">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="82770-108">Type of the container.</span></span> <span data-ttu-id="82770-109">Der Wert dieser Eigenschaft für: 1.</span><span class="sxs-lookup"><span data-stu-id="82770-109">The value of this property for: 1.</span></span> <span data-ttu-id="82770-110">Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist.</span><span class="sxs-lookup"><span data-stu-id="82770-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="82770-111">Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3.</span><span class="sxs-lookup"><span data-stu-id="82770-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="82770-112">Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4.</span><span class="sxs-lookup"><span data-stu-id="82770-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="82770-113">Azure SQL-Instanz ist AzureSqlContainer.</span><span class="sxs-lookup"><span data-stu-id="82770-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="82770-114">Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</span><span class="sxs-lookup"><span data-stu-id="82770-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="82770-115">Vollständig qualifiziert ARM-Url des virtuellen Computers von diesem Container Azure IaaS-VM dargestellt.</span><span class="sxs-lookup"><span data-stu-id="82770-115">Fully qualified ARM url of the virtual machine represented by this Azure IaaS VM container.</span></span></param>
        <param name="virtualMachineVersion"><span data-ttu-id="82770-116">Gibt an, ob der Container eine Classic oder einer Azure-Ressourcen-Manager-VM darstellt.</span><span class="sxs-lookup"><span data-stu-id="82770-116">Specifies whether the container represents a Classic or an Azure Resource Manager VM.</span></span></param>
        <param name="resourceGroup"><span data-ttu-id="82770-117">Der Ressourcengruppenname der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="82770-117">Resource group name of Recovery Services Vault.</span></span></param>
        <summary>
            <span data-ttu-id="82770-118">Initialisiert eine neue Instanz der IaaSVMContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="82770-118">Initializes a new instance of the IaaSVMContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82770-119">Ruft ab, oder legt ihn fest Ressourcengruppennamen Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="82770-119">Gets or sets resource group name of Recovery Services Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineId">
      <MemberSignature Language="C#" Value="public string VirtualMachineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.VirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.VirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82770-120">Ruft ab, oder legt ihn fest vollqualifizierte ARM-Url des virtuellen Computers von diesem Container Azure IaaS-VM dargestellt.</span><span class="sxs-lookup"><span data-stu-id="82770-120">Gets or sets fully qualified ARM url of the virtual machine represented by this Azure IaaS VM container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineVersion">
      <MemberSignature Language="C#" Value="public string VirtualMachineVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.VirtualMachineVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineVersion As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer.VirtualMachineVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="82770-121">Ruft ab oder legt gibt an, ob der Container eine Classic oder einer Azure-Ressourcen-Manager-VM darstellt.</span><span class="sxs-lookup"><span data-stu-id="82770-121">Gets or sets specifies whether the container represents a Classic or an Azure Resource Manager VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>