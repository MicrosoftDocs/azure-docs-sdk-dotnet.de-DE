<Type Name="AzureSqlContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer">
  <TypeSignature Language="C#" Value="public class AzureSqlContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type AzureSqlContainer = class&#xA;    inherit ProtectionContainer" />
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
            <span data-ttu-id="4f7b1-101">Azure Sql-spezifische-Container.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-101">Azure Sql workload-specific container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4f7b1-102">Initialisiert eine neue Instanz der AzureSqlContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-102">Initializes a new instance of the AzureSqlContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer : string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType)" />
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
        <param name="friendlyName"><span data-ttu-id="4f7b1-103">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-103">Friendly name of the container.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="4f7b1-104">Typ der Sicherung Managemenent für den Container.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-104">Type of backup managemenent for the container.</span></span> <span data-ttu-id="4f7b1-105">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="4f7b1-105">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="4f7b1-106">Status der Registrierung des Containers mit der Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-106">Status of registration of the container with the Recovery Services Vault.</span></span></param>
        <param name="healthStatus"><span data-ttu-id="4f7b1-107">Status der Integrität des Containers.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-107">Status of health of the container.</span></span></param>
        <param name="containerType"><span data-ttu-id="4f7b1-108">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-108">Type of the container.</span></span> <span data-ttu-id="4f7b1-109">Der Wert dieser Eigenschaft für: 1.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-109">The value of this property for: 1.</span></span> <span data-ttu-id="4f7b1-110">Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-110">Compute Azure VM is Microsoft.Compute/virtualMachines 2.</span></span> <span data-ttu-id="4f7b1-111">Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-111">Classic Compute Azure VM is Microsoft.ClassicCompute/virtualMachines 3.</span></span> <span data-ttu-id="4f7b1-112">Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-112">Windows machines (like MAB, DPM etc) is Windows 4.</span></span> <span data-ttu-id="4f7b1-113">Azure SQL-Instanz ist AzureSqlContainer.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-113">Azure SQL instance is AzureSqlContainer.</span></span> <span data-ttu-id="4f7b1-114">Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</span><span class="sxs-lookup"><span data-stu-id="4f7b1-114">Possible values include: 'Invalid', 'Unknown', 'IaasVMContainer', 'IaasVMServiceContainer', 'DPMContainer', 'AzureBackupServerContainer', 'MABContainer', 'Cluster', 'AzureSqlContainer', 'Windows', 'VCenter'</span></span></param>
        <summary>
            <span data-ttu-id="4f7b1-115">Initialisiert eine neue Instanz der AzureSqlContainer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4f7b1-115">Initializes a new instance of the AzureSqlContainer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>