<Type Name="BackupEngineBase" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase">
  <TypeSignature Language="C#" Value="public class BackupEngineBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupEngineBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupEngineBase" />
  <TypeSignature Language="F#" Value="type BackupEngineBase = class" />
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
            <span data-ttu-id="ec8ad-101">Die Basis Sicherungsmodul-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-101">The base backup engine class.</span></span> <span data-ttu-id="ec8ad-102">Alle arbeitsauslastung bestimmte Sicherung Module, die von dieser Klasse abgeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-102">All workload specific backup engines derive from this class.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-103">Initialisiert eine neue Instanz der BackupEngineBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-103">Initializes a new instance of the BackupEngineBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupEngineBase (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string backupEngineState = null, string healthStatus = null, Nullable&lt;bool&gt; canReRegister = null, string backupEngineId = null, string dpmVersion = null, string azureBackupAgentVersion = null, Nullable&lt;bool&gt; isAzureBackupAgentUpgradeAvailable = null, Nullable&lt;bool&gt; isDPMUpgradeAvailable = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string backupEngineState, string healthStatus, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string backupEngineId, string dpmVersion, string azureBackupAgentVersion, valuetype System.Nullable`1&lt;bool&gt; isAzureBackupAgentUpgradeAvailable, valuetype System.Nullable`1&lt;bool&gt; isDPMUpgradeAvailable, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional backupEngineState As String = null, Optional healthStatus As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional backupEngineId As String = null, Optional dpmVersion As String = null, Optional azureBackupAgentVersion As String = null, Optional isAzureBackupAgentUpgradeAvailable As Nullable(Of Boolean) = null, Optional isDPMUpgradeAvailable As Nullable(Of Boolean) = null, Optional extendedInfo As BackupEngineExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase : string * string * string * string * string * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase (friendlyName, backupManagementType, registrationStatus, backupEngineState, healthStatus, canReRegister, backupEngineId, dpmVersion, azureBackupAgentVersion, isAzureBackupAgentUpgradeAvailable, isDPMUpgradeAvailable, extendedInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="registrationStatus" Type="System.String" />
        <Parameter Name="backupEngineState" Type="System.String" />
        <Parameter Name="healthStatus" Type="System.String" />
        <Parameter Name="canReRegister" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="backupEngineId" Type="System.String" />
        <Parameter Name="dpmVersion" Type="System.String" />
        <Parameter Name="azureBackupAgentVersion" Type="System.String" />
        <Parameter Name="isAzureBackupAgentUpgradeAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="isDPMUpgradeAvailable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="ec8ad-104">Anzeigename des Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-104">Friendly name of the backup engine.</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="ec8ad-105">Typ der sicherungsverwaltung für das Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-105">Type of backup management for the backup engine.</span></span> <span data-ttu-id="ec8ad-106">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="ec8ad-106">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="registrationStatus"><span data-ttu-id="ec8ad-107">Der Registrierungsstatus des Moduls mit dem Recovery Services-Tresor sichern.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-107">Registration status of the backup engine with the Recovery Services Vault.</span></span></param>
        <param name="backupEngineState"><span data-ttu-id="ec8ad-108">Status des Moduls mit dem Recovery Services-Tresor sichern.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-108">Status of the backup engine with the Recovery Services Vault.</span></span> <span data-ttu-id="ec8ad-109">= {Aktiv/löschen/DeleteFailed}</span><span class="sxs-lookup"><span data-stu-id="ec8ad-109">= {Active/Deleting/DeleteFailed}</span></span></param>
        <param name="healthStatus"><span data-ttu-id="ec8ad-110">Sicherungsstatus des Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-110">Backup status of the backup engine.</span></span></param>
        <param name="canReRegister"><span data-ttu-id="ec8ad-111">Ein Flag ab, ob das Sicherungsmodul registriert werden, einmal bereits registriert.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-111">Flag indicating if the backup engine be registered, once already registered.</span></span></param>
        <param name="backupEngineId"><span data-ttu-id="ec8ad-112">ID des dem Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-112">ID of the backup engine.</span></span></param>
        <param name="dpmVersion"><span data-ttu-id="ec8ad-113">Backup-Modulversion</span><span class="sxs-lookup"><span data-stu-id="ec8ad-113">Backup engine version</span></span></param>
        <param name="azureBackupAgentVersion"><span data-ttu-id="ec8ad-114">Backup-Agent-version</span><span class="sxs-lookup"><span data-stu-id="ec8ad-114">Backup agent version</span></span></param>
        <param name="isAzureBackupAgentUpgradeAvailable"><span data-ttu-id="ec8ad-115">Zum Überprüfen, ob die backup-Agent verfügbar aktualisieren</span><span class="sxs-lookup"><span data-stu-id="ec8ad-115">To check if backup agent upgrade available</span></span></param>
        <param name="isDPMUpgradeAvailable"><span data-ttu-id="ec8ad-116">Zum Überprüfen, ob Sicherungsmodul verfügbaren aktualisieren</span><span class="sxs-lookup"><span data-stu-id="ec8ad-116">To check if backup engine upgrade available</span></span></param>
        <param name="extendedInfo"><span data-ttu-id="ec8ad-117">Erweiterte Informationen zu der der backupengine</span><span class="sxs-lookup"><span data-stu-id="ec8ad-117">Extended info of the backupengine</span></span></param>
        <summary>
            <span data-ttu-id="ec8ad-118">Initialisiert eine neue Instanz der BackupEngineBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-118">Initializes a new instance of the BackupEngineBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureBackupAgentVersion">
      <MemberSignature Language="C#" Value="public string AzureBackupAgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureBackupAgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.AzureBackupAgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureBackupAgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.AzureBackupAgentVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.AzureBackupAgentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="azureBackupAgentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-119">Ruft ab oder legt ihn fest-sicherungs-Agent-version</span><span class="sxs-lookup"><span data-stu-id="ec8ad-119">Gets or sets backup agent version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineId">
      <MemberSignature Language="C#" Value="public string BackupEngineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineId As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-120">Ruft ab, oder legt ihn fest-ID des dem Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-120">Gets or sets ID of the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupEngineState">
      <MemberSignature Language="C#" Value="public string BackupEngineState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupEngineState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineState" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupEngineState As String" />
      <MemberSignature Language="F#" Value="member this.BackupEngineState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupEngineState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupEngineState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-121">Abrufen oder Festlegen des Status der Sicherungsmodul mit Recovery Services-Tresor.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-121">Gets or sets status of the backup engine with the Recovery Services Vault.</span></span> <span data-ttu-id="ec8ad-122">= {Aktiv/löschen/DeleteFailed}</span><span class="sxs-lookup"><span data-stu-id="ec8ad-122">= {Active/Deleting/DeleteFailed}</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.BackupManagementType" />
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
            <span data-ttu-id="ec8ad-123">Ruft ab oder legt ihn fest sicherungsverwaltung für das Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-123">Gets or sets type of backup management for the backup engine.</span></span>
            <span data-ttu-id="ec8ad-124">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="ec8ad-124">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReRegister">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CanReRegister { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CanReRegister" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.CanReRegister" />
      <MemberSignature Language="VB.NET" Value="Public Property CanReRegister As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CanReRegister : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.CanReRegister" />
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
            <span data-ttu-id="ec8ad-125">Ruft ab, oder legt sie fest, Flag angibt, ob das Sicherungsmodul registriert werden, einmal bereits registriert.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-125">Gets or sets flag indicating if the backup engine be registered, once already registered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DpmVersion">
      <MemberSignature Language="C#" Value="public string DpmVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DpmVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.DpmVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DpmVersion As String" />
      <MemberSignature Language="F#" Value="member this.DpmVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.DpmVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dpmVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-126">Ruft ab oder legt ihn fest Sicherungsmodul-version</span><span class="sxs-lookup"><span data-stu-id="ec8ad-126">Gets or sets backup engine version</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As BackupEngineExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-127">Ruft ab oder legt ihn fest erweiterte Informationen zu der der backupengine</span><span class="sxs-lookup"><span data-stu-id="ec8ad-127">Gets or sets extended info of the backupengine</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.FriendlyName" />
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
            <span data-ttu-id="ec8ad-128">Ruft ab, oder legt ihn fest angezeigte Name des dem Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-128">Gets or sets friendly name of the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatus">
      <MemberSignature Language="C#" Value="public string HealthStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HealthStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.HealthStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatus As String" />
      <MemberSignature Language="F#" Value="member this.HealthStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.HealthStatus" />
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
            <span data-ttu-id="ec8ad-129">Ruft ab, oder legt ihn fest Sicherungsstatus des Sicherungsmodul.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-129">Gets or sets backup status of the backup engine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsAzureBackupAgentUpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAzureBackupAgentUpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAzureBackupAgentUpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsAzureBackupAgentUpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAzureBackupAgentUpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAzureBackupAgentUpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsAzureBackupAgentUpgradeAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAzureBackupAgentUpgradeAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-130">Ruft ab oder legt zum Überprüfen, ob die backup-Agent verfügbar aktualisieren</span><span class="sxs-lookup"><span data-stu-id="ec8ad-130">Gets or sets to check if backup agent upgrade available</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDPMUpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDPMUpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDPMUpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsDPMUpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDPMUpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDPMUpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.IsDPMUpgradeAvailable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDPMUpgradeAvailable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ec8ad-131">Ruft ab oder legt zum Überprüfen, ob Sicherungsmodul verfügbaren aktualisieren</span><span class="sxs-lookup"><span data-stu-id="ec8ad-131">Gets or sets to check if backup engine upgrade available</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public string RegistrationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property RegistrationStatus As String" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase.RegistrationStatus" />
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
            <span data-ttu-id="ec8ad-132">Ruft ab, oder legt ihn fest Registrierungsstatus des Moduls mit dem Recovery Services-Tresor sichern.</span><span class="sxs-lookup"><span data-stu-id="ec8ad-132">Gets or sets registration status of the backup engine with the Recovery Services Vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>