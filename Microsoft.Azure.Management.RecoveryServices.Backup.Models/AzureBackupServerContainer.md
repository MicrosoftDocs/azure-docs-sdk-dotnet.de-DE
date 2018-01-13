<Type Name="AzureBackupServerContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer">
  <TypeSignature Language="C#" Value="public class AzureBackupServerContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureBackupServerContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureBackupServerContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type AzureBackupServerContainer = class&#xA;    inherit ProtectionContainer" />
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
            AzureBackupServer (DPMVenus) arbeitsauslastungsspezifischen schutzcontainer.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBackupServerContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureBackupServerContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureBackupServerContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, Nullable&lt;bool&gt; canReRegister = null, string containerId = null, Nullable&lt;long&gt; protectedItemCount = null, string dpmAgentVersion = null, System.Collections.Generic.IList&lt;string&gt; dPMServers = null, Nullable&lt;bool&gt; upgradeAvailable = null, string protectionStatus = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, valuetype System.Nullable`1&lt;bool&gt; canReRegister, string containerId, valuetype System.Nullable`1&lt;int64&gt; protectedItemCount, string dpmAgentVersion, class System.Collections.Generic.IList`1&lt;string&gt; dPMServers, valuetype System.Nullable`1&lt;bool&gt; upgradeAvailable, string protectionStatus, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Nullable{System.Int64},System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional containerId As String = null, Optional protectedItemCount As Nullable(Of Long) = null, Optional dpmAgentVersion As String = null, Optional dPMServers As IList(Of String) = null, Optional upgradeAvailable As Nullable(Of Boolean) = null, Optional protectionStatus As String = null, Optional extendedInfo As DPMContainerExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer : string * string * string * string * string * Nullable&lt;bool&gt; * string * Nullable&lt;int64&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, canReRegister, containerId, protectedItemCount, dpmAgentVersion, dPMServers, upgradeAvailable, protectionStatus, extendedInfo)" />
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
        <param name="friendlyName">Anzeigename des Containers.</param>
        <param name="backupManagementType">Typ der Sicherung Managemenent für den Container. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="registrationStatus">Status der Registrierung des Containers mit der Recovery Services-Tresor.</param>
        <param name="healthStatus">Status der Integrität des Containers.</param>
        <param name="containerType">Der Typ des Containers. Der Wert dieser Eigenschaft für: 1. Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist. Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3. Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4. Azure SQL-Instanz ist AzureSqlContainer. Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</param>
        <param name="canReRegister">Gibt an, ob der Container neu registrierbaren ist.</param>
        <param name="containerId">Die ID des Containers.</param>
        <param name="protectedItemCount">Anzahl geschützter Elemente in der BackupEngine</param>
        <param name="dpmAgentVersion">Backup-Agent-Modulversion</param>
        <param name="dPMServers">Liste der BackupEngines schützen den container</param>
        <param name="upgradeAvailable">Beim Upgrade überprüfen verfügbar</param>
        <param name="protectionStatus">Der Schutzstatus des Containers.</param>
        <param name="extendedInfo">Erweiterte Informationen des Containers.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureBackupServerContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReRegister">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CanReRegister { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CanReRegister" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.CanReRegister" />
      <MemberSignature Language="VB.NET" Value="Public Property CanReRegister As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CanReRegister : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.CanReRegister" />
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
            Ruft ab oder legt gibt an, ob der Container neu registrierbaren ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public string ContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerId As String" />
      <MemberSignature Language="F#" Value="member this.ContainerId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ContainerId" />
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
            Ruft ab oder legt die ID des Containers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DpmAgentVersion">
      <MemberSignature Language="C#" Value="public string DpmAgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DpmAgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.DpmAgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property DpmAgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.DpmAgentVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.DpmAgentVersion" />
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
            Ruft ab oder legt ihn fest Sicherungsmodul Agentversion
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DPMServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DPMServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DPMServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.DPMServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DPMServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DPMServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.DPMServers" />
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
            Ruft ab oder legt die Liste der BackupEngines schützen den container
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As DPMContainerExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.DPMContainerExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ExtendedInfo" />
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
            Abrufen oder Festlegen der erweiterten Informationen des Containers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProtectedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProtectedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ProtectedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ProtectedItemCount" />
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
            Ruft ab oder legt die Anzahl der geschützten Elemente in der BackupEngine fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectionStatus">
      <MemberSignature Language="C#" Value="public string ProtectionStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProtectionStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ProtectionStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectionStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProtectionStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.ProtectionStatus" />
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
            Ruft ab, oder legt ihn fest Schutzstatus des Containers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeAvailable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UpgradeAvailable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UpgradeAvailable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.UpgradeAvailable" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradeAvailable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UpgradeAvailable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureBackupServerContainer.UpgradeAvailable" />
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
            Ruft ab oder legt ihn fest, beim Überprüfen upgrade verfügbar
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>