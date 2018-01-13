<Type Name="AzureSqlProtectedItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem">
  <TypeSignature Language="C#" Value="public class AzureSqlProtectedItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureSqlProtectedItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureSqlProtectedItem&#xA;Inherits ProtectedItem" />
  <TypeSignature Language="F#" Value="type AzureSqlProtectedItem = class&#xA;    inherit ProtectedItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectedItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Sql/servers/databases")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Azure SQL-spezifische Sicherung Element.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectedItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureSqlProtectedItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureSqlProtectedItem (string backupManagementType = null, string workloadType = null, string containerName = null, string sourceResourceId = null, string policyId = null, Nullable&lt;DateTime&gt; lastRecoveryPoint = null, string protectedItemDataId = null, string protectionState = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string workloadType, string containerName, string sourceResourceId, string policyId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRecoveryPoint, string protectedItemDataId, string protectionState, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.String,System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional workloadType As String = null, Optional containerName As String = null, Optional sourceResourceId As String = null, Optional policyId As String = null, Optional lastRecoveryPoint As Nullable(Of DateTime) = null, Optional protectedItemDataId As String = null, Optional protectionState As String = null, Optional extendedInfo As AzureSqlProtectedItemExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem : string * string * string * string * string * Nullable&lt;DateTime&gt; * string * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem (backupManagementType, workloadType, containerName, sourceResourceId, policyId, lastRecoveryPoint, protectedItemDataId, protectionState, extendedInfo)" />
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
        <Parameter Name="protectedItemDataId" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="backupManagementType">Typ der Sicherung Managemenent für das Element gesichert werden. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="workloadType">Typ der arbeitsauslastung, die dieses Element darstellt.
            Folgende Werte sind möglich: "Ungültig", "VM", "FileFolder", "AzureSqlDb", "SQLDB", "Exchange", "Sharepoint", "VMwareVM", "SystemState", "Client", "GenericDataSource"</param>
        <param name="containerName">Eindeutiger Name des Containers</param>
        <param name="sourceResourceId">ARM-ID der Ressource, die gesichert werden sollen.</param>
        <param name="policyId">ID der Sicherungsrichtlinie mit der dieses Element werden gesichert.</param>
        <param name="lastRecoveryPoint">Zeitstempel der letzten (aktuelle) Sicherungskopie für dieses Element für die Sicherung erstellt wurde.</param>
        <param name="protectedItemDataId">Interne ID für ein Sichern des Elements.
            Zum vom Modul für Azure SQL-Sicherung Recovery Services hergestellt wird.</param>
        <param name="protectionState">Sicherungsstatus des gesicherten Elements.
            Folgende Werte sind möglich: "Ungültig", 'IRPending', 'Protected', 'ProtectionError', "ProtectionStopped", "ProtectionPaused"</param>
        <param name="extendedInfo">Zusätzliche Informationen für dieses Element für die Sicherung.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureSqlProtectedItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As AzureSqlProtectedItemExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItemExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt zusätzliche Informationen für dieses Element für die Sicherung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemDataId">
      <MemberSignature Language="C#" Value="public string ProtectedItemDataId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectedItemDataId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectedItemDataId" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemDataId As String" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemDataId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectedItemDataId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="protectedItemDataId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder interne ID des ein Sichern des Elements definiert. Zum vom Modul für Azure SQL-Sicherung Recovery Services hergestellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionState">
      <MemberSignature Language="C#" Value="public string ProtectionState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectionState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionState As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionState : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureSqlProtectedItem.ProtectionState" />
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
            Ruft ab, oder legt ihn fest Sicherungsstatus des gesicherten Elements. Folgende Werte sind möglich: "Ungültig", 'IRPending', 'Protected', 'ProtectionError', "ProtectionStopped", "ProtectionPaused"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>