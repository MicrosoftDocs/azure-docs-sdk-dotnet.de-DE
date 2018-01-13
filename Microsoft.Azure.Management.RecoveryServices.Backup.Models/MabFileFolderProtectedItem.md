<Type Name="MabFileFolderProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem">
  <TypeSignature Language="C#" Value="public class MabFileFolderProtectedItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabFileFolderProtectedItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class MabFileFolderProtectedItem&#xA;Inherits ProtectedItem" />
  <TypeSignature Language="F#" Value="type MabFileFolderProtectedItem = class&#xA;    inherit ProtectedItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            MAB arbeitsauslastungsspezifischen Sichern des Elements.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabFileFolderProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MabFileFolderProtectedItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabFileFolderProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null, string friendlyName = null, string computerName = null, string lastBackupStatus = null, string protectionState = null, Nullable&lt;bool&gt; isScheduledForDeferredDelete = null, Nullable&lt;long&gt; deferredDeleteSyncTimeInUTC = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint, string friendlyName, string computerName, string lastBackupStatus, string protectionState, valuetype System.Nullable`1&lt;bool&gt; isScheduledForDeferredDelete, valuetype System.Nullable`1&lt;int64&gt; deferredDeleteSyncTimeInUTC, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int64},Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null, Optional friendlyName As String = null, Optional computerName As String = null, Optional lastBackupStatus As String = null, Optional protectionState As String = null, Optional isScheduledForDeferredDelete As Nullable(Of Boolean) = null, Optional deferredDeleteSyncTimeInUTC As Nullable(Of Long) = null, Optional extendedInfo As MabFileFolderProtectedItemExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint, friendlyName, computerName, lastBackupStatus, protectionState, isScheduledForDeferredDelete, deferredDeleteSyncTimeInUTC, extendedInfo)" />
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
        <Parameter Name="computerName" Type="System.String" />
        <Parameter Name="lastBackupStatus" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="isScheduledForDeferredDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="deferredDeleteSyncTimeInUTC" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="backupManagementType">Typ der Sicherung Managemenent für das Element gesichert werden. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="workloadType">Typ der arbeitsauslastung, die dieses Element darstellt.
            Folgende Werte sind möglich: "Ungültig", "VM", "FileFolder", "AzureSqlDb", "SQLDB", "Exchange", "Sharepoint", "VMwareVM", "SystemState", "Client", "GenericDataSource"</param>
        <param name="containerName">Eindeutiger Name des Containers</param>
        <param name="sourceResourceId">ARM-ID der Ressource, die gesichert werden sollen.</param>
        <param name="policyId">ID der Sicherungsrichtlinie mit der dieses Element werden gesichert.</param>
        <param name="lastRecoveryPoint">Zeitstempel der letzten (aktuelle) Sicherungskopie für dieses Element für die Sicherung erstellt wurde.</param>
        <param name="friendlyName">Anzeigename des diesem Element für die Sicherung.</param>
        <param name="computerName">Name des Computers diese Sichern des Elements zugeordnet.</param>
        <param name="lastBackupStatus">Status des letzten Sicherungsvorgang.</param>
        <param name="protectionState">Geschützte, ProtectionStopped, IRPending oder ProtectionError</param>
        <param name="isScheduledForDeferredDelete">Gibt an, ob das Element für das verzögerte löschen geplant ist.</param>
        <param name="deferredDeleteSyncTimeInUTC">Zeitpunkt der Synchronisierung für das verzögerte löschen.</param>
        <param name="extendedInfo">Zusätzliche Informationen mit diesem Element für die Sicherung.</param>
        <summary>
            Initialisiert eine neue Instanz der MabFileFolderProtectedItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ComputerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="computerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Computers verknüpft sind mit diesem Element für die Sicherung fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferredDeleteSyncTimeInUTC">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; DeferredDeleteSyncTimeInUTC { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; DeferredDeleteSyncTimeInUTC" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.DeferredDeleteSyncTimeInUTC" />
      <MemberSignature Language="VB.NET" Value="Public Property DeferredDeleteSyncTimeInUTC As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.DeferredDeleteSyncTimeInUTC : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.DeferredDeleteSyncTimeInUTC" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deferredDeleteSyncTimeInUTC")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Synchronisierungszeit für das verzögerte löschen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As MabFileFolderProtectedItemExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItemExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt Sie zusätzliche Informationen mit diesem Element für die Sicherung fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.FriendlyName" />
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
            Ruft ab, oder legt ihn fest angezeigte Name der diesem Element für die Sicherung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsScheduledForDeferredDelete">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsScheduledForDeferredDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsScheduledForDeferredDelete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.IsScheduledForDeferredDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property IsScheduledForDeferredDelete As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsScheduledForDeferredDelete : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.IsScheduledForDeferredDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isScheduledForDeferredDelete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, ob das Element für das verzögerte löschen geplant ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupStatus">
      <MemberSignature Language="C#" Value="public string LastBackupStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastBackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.LastBackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupStatus As String" />
      <MemberSignature Language="F#" Value="member this.LastBackupStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.LastBackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBackupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Status der letzten Sicherungsvorgang.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabFileFolderProtectedItem.ProtectionState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectionState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt geschützt, ProtectionStopped, IRPending oder ProtectionError
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>