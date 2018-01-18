<Type Name="AzureIaaSComputeVMProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem">
  <TypeSignature Language="C#" Value="public class AzureIaaSComputeVMProtectedItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSComputeVMProtectedItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSComputeVMProtectedItem&#xA;Inherits AzureIaaSVMProtectedItem" />
  <TypeSignature Language="F#" Value="type AzureIaaSComputeVMProtectedItem = class&#xA;    inherit AzureIaaSVMProtectedItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Compute/virtualMachines")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f8727-101">IaaS-VM arbeitsauslastungsspezifischen Sichern des Elements, das die Azure-Ressourcen-Manager-VM darstellt.</span><span class="sxs-lookup"><span data-stu-id="f8727-101">IaaS VM workload-specific backup item representing the Azure Resource Manager VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f8727-102">Initialisiert eine neue Instanz der AzureIaaSComputeVMProtectedItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f8727-102">Initializes a new instance of the AzureIaaSComputeVMProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null, string friendlyName = null, string virtualMachineId = null, string protectionStatus = null, string protectionState = null, string healthStatus = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; healthDetails = null, string lastBackupStatus = null, Nullable&lt;DateTime&gt; lastBackupTime = null, string protectedItemDataId = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint, string friendlyName, string virtualMachineId, string protectionStatus, string protectionState, string healthStatus, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; healthDetails, string lastBackupStatus, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastBackupTime, string protectedItemDataId, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails},System.String,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null, Optional friendlyName As String = null, Optional virtualMachineId As String = null, Optional protectionStatus As String = null, Optional protectionState As String = null, Optional healthStatus As String = null, Optional healthDetails As IList(Of AzureIaaSVMHealthDetails) = null, Optional lastBackupStatus As String = null, Optional lastBackupTime As Nullable(Of DateTime) = null, Optional protectedItemDataId As String = null, Optional extendedInfo As AzureIaaSVMProtectedItemExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt; * string * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint, friendlyName, virtualMachineId, protectionStatus, protectionState, healthStatus, healthDetails, lastBackupStatus, lastBackupTime, protectedItemDataId, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="workloadType" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="sourceResourceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="lastRecoveryPoint" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="protectionStatus" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="healthDetails" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMHealthDetails&gt;" />
        <Parameter Name="lastBackupStatus" Type="System.String" />
        <Parameter Name="lastBackupTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="protectedItemDataId" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSVMProtectedItemExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="f8727-103">Typ der Sicherung Managemenent für das Element gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="f8727-103">Type of backup managemenent for the backed up item.</span></span> <span data-ttu-id="f8727-104">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="f8727-104">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="workloadType"><span data-ttu-id="f8727-105">Typ der arbeitsauslastung, die dieses Element darstellt.</span><span class="sxs-lookup"><span data-stu-id="f8727-105">Type of workload this item represents.</span></span>
            <span data-ttu-id="f8727-106">Folgende Werte sind möglich: "Ungültig", "VM", "FileFolder", "AzureSqlDb", "SQLDB", "Exchange", "Sharepoint", "VMwareVM", "SystemState", "Client", "GenericDataSource"</span><span class="sxs-lookup"><span data-stu-id="f8727-106">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span></param>
        <param name="containerName"><span data-ttu-id="f8727-107">Eindeutiger Name des Containers</span><span class="sxs-lookup"><span data-stu-id="f8727-107">Unique name of container</span></span></param>
        <param name="sourceResourceId"><span data-ttu-id="f8727-108">ARM-ID der Ressource, die gesichert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="f8727-108">ARM ID of the resource to be backed up.</span></span></param>
        <param name="policyId"><span data-ttu-id="f8727-109">ID der Sicherungsrichtlinie mit der dieses Element werden gesichert.</span><span class="sxs-lookup"><span data-stu-id="f8727-109">ID of the backup policy with which this item is backed up.</span></span></param>
        <param name="lastRecoveryPoint"><span data-ttu-id="f8727-110">Zeitstempel der letzten (aktuelle) Sicherungskopie für dieses Element für die Sicherung erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="f8727-110">Timestamp when the last (latest) backup copy was created for this backup item.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="f8727-111">Anzeigename des virtuellen Computers durch diese Sichern des Elements dargestellt.</span><span class="sxs-lookup"><span data-stu-id="f8727-111">Friendly name of the VM represented by this backup item.</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="f8727-112">Vollqualifizierte ARM-ID des virtuellen Computers von diesem Element dargestellt.</span><span class="sxs-lookup"><span data-stu-id="f8727-112">Fully qualified ARM ID of the virtual machine represented by this item.</span></span></param>
        <param name="protectionStatus"><span data-ttu-id="f8727-113">Sicherungsstatus des diesem Element für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f8727-113">Backup status of this backup item.</span></span></param>
        <param name="protectionState"><span data-ttu-id="f8727-114">Sicherungsstatus von diesem Element für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f8727-114">Backup state of this backup item.</span></span>
            <span data-ttu-id="f8727-115">Folgende Werte sind möglich: "Ungültig", 'IRPending', 'Protected', 'ProtectionError', "ProtectionStopped", "ProtectionPaused"</span><span class="sxs-lookup"><span data-stu-id="f8727-115">Possible values include: 'Invalid', 'IRPending', 'Protected', 'ProtectionError', 'ProtectionStopped', 'ProtectionPaused'</span></span></param>
        <param name="healthStatus"><span data-ttu-id="f8727-116">Der Integritätsstatus des geschützten Elements.</span><span class="sxs-lookup"><span data-stu-id="f8727-116">Health status of protected item.</span></span>
            <span data-ttu-id="f8727-117">Folgende Werte sind möglich: "Übergebene", "Aktion", "ActionSuggested", "Ungültig"</span><span class="sxs-lookup"><span data-stu-id="f8727-117">Possible values include: 'Passed', 'ActionRequired', 'ActionSuggested', 'Invalid'</span></span></param>
        <param name="healthDetails"><span data-ttu-id="f8727-118">Zustandsdetails auf dieses Element für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f8727-118">Health details on this backup item.</span></span></param>
        <param name="lastBackupStatus"><span data-ttu-id="f8727-119">Status des letzten Sicherungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="f8727-119">Last backup operation status.</span></span>
            <span data-ttu-id="f8727-120">Mögliche Werte: fehlerfrei, fehlerhaft.</span><span class="sxs-lookup"><span data-stu-id="f8727-120">Possible values: Healthy, Unhealthy.</span></span></param>
        <param name="lastBackupTime"><span data-ttu-id="f8727-121">Der Zeitstempel des letzten Sicherungsvorgangs auf dieses Element für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f8727-121">Timestamp of the last backup operation on this backup item.</span></span></param>
        <param name="protectedItemDataId"><span data-ttu-id="f8727-122">Daten-ID des geschützten Elements.</span><span class="sxs-lookup"><span data-stu-id="f8727-122">Data ID of the protected item.</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="f8727-123">Zusätzliche Informationen für dieses Element für die Sicherung.</span><span class="sxs-lookup"><span data-stu-id="f8727-123">Additional information for this backup item.</span></span></param>
        <summary>
            <span data-ttu-id="f8727-124">Initialisiert eine neue Instanz der AzureIaaSComputeVMProtectedItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f8727-124">Initializes a new instance of the AzureIaaSComputeVMProtectedItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>