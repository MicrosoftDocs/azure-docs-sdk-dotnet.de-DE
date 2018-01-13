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
            IaaS-VM arbeitsauslastungsspezifischen Sichern des Elements, das die Azure-Ressourcen-Manager-VM darstellt.
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
            Initialisiert eine neue Instanz der AzureIaaSComputeVMProtectedItem-Klasse.
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
        <param name="backupManagementType">Typ der Sicherung Managemenent für das Element gesichert werden. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="workloadType">Typ der arbeitsauslastung, die dieses Element darstellt.
            Folgende Werte sind möglich: "Ungültig", "VM", "FileFolder", "AzureSqlDb", "SQLDB", "Exchange", "Sharepoint", "VMwareVM", "SystemState", "Client", "GenericDataSource"</param>
        <param name="containerName">Eindeutiger Name des Containers</param>
        <param name="sourceResourceId">ARM-ID der Ressource, die gesichert werden sollen.</param>
        <param name="policyId">ID der Sicherungsrichtlinie mit der dieses Element werden gesichert.</param>
        <param name="lastRecoveryPoint">Zeitstempel der letzten (aktuelle) Sicherungskopie für dieses Element für die Sicherung erstellt wurde.</param>
        <param name="friendlyName">Anzeigename des virtuellen Computers durch diese Sichern des Elements dargestellt.</param>
        <param name="virtualMachineId">Vollqualifizierte ARM-ID des virtuellen Computers von diesem Element dargestellt.</param>
        <param name="protectionStatus">Sicherungsstatus des diesem Element für die Sicherung.</param>
        <param name="protectionState">Sicherungsstatus von diesem Element für die Sicherung.
            Folgende Werte sind möglich: "Ungültig", 'IRPending', 'Protected', 'ProtectionError', "ProtectionStopped", "ProtectionPaused"</param>
        <param name="healthStatus">Der Integritätsstatus des geschützten Elements.
            Folgende Werte sind möglich: "Übergebene", "Aktion", "ActionSuggested", "Ungültig"</param>
        <param name="healthDetails">Zustandsdetails auf dieses Element für die Sicherung.</param>
        <param name="lastBackupStatus">Status des letzten Sicherungsvorgang.
            Mögliche Werte: fehlerfrei, fehlerhaft.</param>
        <param name="lastBackupTime">Der Zeitstempel des letzten Sicherungsvorgangs auf dieses Element für die Sicherung.</param>
        <param name="protectedItemDataId">Daten-ID des geschützten Elements.</param>
        <param name="extendedInfo">Zusätzliche Informationen für dieses Element für die Sicherung.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSComputeVMProtectedItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>