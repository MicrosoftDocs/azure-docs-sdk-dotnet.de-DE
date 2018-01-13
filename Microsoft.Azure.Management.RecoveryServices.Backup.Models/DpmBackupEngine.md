<Type Name="DpmBackupEngine" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine">
  <TypeSignature Language="C#" Value="public class DpmBackupEngine : Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DpmBackupEngine extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine" />
  <TypeSignature Language="VB.NET" Value="Public Class DpmBackupEngine&#xA;Inherits BackupEngineBase" />
  <TypeSignature Language="F#" Value="type DpmBackupEngine = class&#xA;    inherit BackupEngineBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Data Protection Manager (DPM) bestimmte Sicherungsmodul.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmBackupEngine ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DpmBackupEngine-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DpmBackupEngine (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string backupEngineState = null, string healthStatus = null, Nullable&lt;bool&gt; canReRegister = null, string backupEngineId = null, string dpmVersion = null, string azureBackupAgentVersion = null, Nullable&lt;bool&gt; isAzureBackupAgentUpgradeAvailable = null, Nullable&lt;bool&gt; isDPMUpgradeAvailable = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string backupEngineState, string healthStatus, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string backupEngineId, string dpmVersion, string azureBackupAgentVersion, valuetype System.Nullable`1&lt;bool&gt; isAzureBackupAgentUpgradeAvailable, valuetype System.Nullable`1&lt;bool&gt; isDPMUpgradeAvailable, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional backupEngineState As String = null, Optional healthStatus As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional backupEngineId As String = null, Optional dpmVersion As String = null, Optional azureBackupAgentVersion As String = null, Optional isAzureBackupAgentUpgradeAvailable As Nullable(Of Boolean) = null, Optional isDPMUpgradeAvailable As Nullable(Of Boolean) = null, Optional extendedInfo As BackupEngineExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine : string * string * string * string * string * Nullable&lt;bool&gt; * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.BackupEngineExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.DpmBackupEngine (friendlyName, backupManagementType, registrationStatus, backupEngineState, healthStatus, canReRegister, backupEngineId, dpmVersion, azureBackupAgentVersion, isAzureBackupAgentUpgradeAvailable, isDPMUpgradeAvailable, extendedInfo)" />
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
        <param name="friendlyName">Anzeigename des Sicherungsmodul.</param>
        <param name="backupManagementType">Typ der sicherungsverwaltung für das Sicherungsmodul. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="registrationStatus">Der Registrierungsstatus des Moduls mit dem Recovery Services-Tresor sichern.</param>
        <param name="backupEngineState">Status des Moduls mit dem Recovery Services-Tresor sichern. = {Aktiv/löschen/DeleteFailed}</param>
        <param name="healthStatus">Sicherungsstatus des Sicherungsmodul.</param>
        <param name="canReRegister">Ein Flag ab, ob das Sicherungsmodul registriert werden, einmal bereits registriert.</param>
        <param name="backupEngineId">ID des dem Sicherungsmodul.</param>
        <param name="dpmVersion">Backup-Modulversion</param>
        <param name="azureBackupAgentVersion">Backup-Agent-version</param>
        <param name="isAzureBackupAgentUpgradeAvailable">Zum Überprüfen, ob die backup-Agent verfügbar aktualisieren</param>
        <param name="isDPMUpgradeAvailable">Zum Überprüfen, ob Sicherungsmodul verfügbaren aktualisieren</param>
        <param name="extendedInfo">Erweiterte Informationen zu der der backupengine</param>
        <summary>
            Initialisiert eine neue Instanz der DpmBackupEngine-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>