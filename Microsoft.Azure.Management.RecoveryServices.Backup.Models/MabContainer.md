<Type Name="MabContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer">
  <TypeSignature Language="C#" Value="public class MabContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class MabContainer&#xA;Inherits ProtectionContainer" />
  <TypeSignature Language="F#" Value="type MabContainer = class&#xA;    inherit ProtectionContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.ProtectionContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("MABWindowsContainer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Container mit Elementen mit gesichert MAB Sicherungsmodul.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MabContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, Nullable&lt;bool&gt; canReRegister = null, Nullable&lt;long&gt; containerId = null, Nullable&lt;long&gt; protectedItemCount = null, string agentVersion = null, Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo extendedInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, valuetype System.Nullable`1&lt;bool&gt; canReRegister, valuetype System.Nullable`1&lt;int64&gt; containerId, valuetype System.Nullable`1&lt;int64&gt; protectedItemCount, string agentVersion, class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo extendedInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Int64},System.Nullable{System.Int64},System.String,Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional canReRegister As Nullable(Of Boolean) = null, Optional containerId As Nullable(Of Long) = null, Optional protectedItemCount As Nullable(Of Long) = null, Optional agentVersion As String = null, Optional extendedInfo As MabContainerExtendedInfo = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer : string * string * string * string * string * Nullable&lt;bool&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * string * Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, canReRegister, containerId, protectedItemCount, agentVersion, extendedInfo)" />
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
        <Parameter Name="containerId" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="protectedItemCount" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="agentVersion" Type="System.String" />
        <Parameter Name="extendedInfo" Type="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo" />
      </Parameters>
      <Docs>
        <param name="friendlyName">Anzeigename des Containers.</param>
        <param name="backupManagementType">Typ der Sicherung Managemenent für den Container. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="registrationStatus">Status der Registrierung des Containers mit der Recovery Services-Tresor.</param>
        <param name="healthStatus">Status der Integrität des Containers.</param>
        <param name="containerType">Der Typ des Containers. Der Wert dieser Eigenschaft für: 1. Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist. Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3. Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4. Azure SQL-Instanz ist AzureSqlContainer. Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</param>
        <param name="canReRegister">Der Container kann ein weiteres Mal registriert werden.</param>
        <param name="containerId">Die Container darstellt den Container.</param>
        <param name="protectedItemCount">Anzahl der Elemente in diesem Container gesichert.</param>
        <param name="agentVersion">Agent-Version dieses Containers.</param>
        <param name="extendedInfo">Zusätzliche Informationen für diesen container</param>
        <summary>
            Initialisiert eine neue Instanz der MabContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentVersion">
      <MemberSignature Language="C#" Value="public string AgentVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AgentVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.AgentVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property AgentVersion As String" />
      <MemberSignature Language="F#" Value="member this.AgentVersion : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.AgentVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="agentVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Agent-Version dieses Containers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CanReRegister">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; CanReRegister { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; CanReRegister" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.CanReRegister" />
      <MemberSignature Language="VB.NET" Value="Public Property CanReRegister As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.CanReRegister : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.CanReRegister" />
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
            Ruft ab oder legt der Container registriert werden kann noch einmal.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerId">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.ContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerId As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContainerId : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.ContainerId" />
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
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Container stellt den Container fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo ExtendedInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo ExtendedInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.ExtendedInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedInfo As MabContainerExtendedInfo" />
      <MemberSignature Language="F#" Value="member this.ExtendedInfo : Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.ExtendedInfo" />
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
        <ReturnType>Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt zusätzliche Informationen für diesen container
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProtectedItemCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProtectedItemCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProtectedItemCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.ProtectedItemCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ProtectedItemCount As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProtectedItemCount : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainer.ProtectedItemCount" />
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
            Ruft ab oder legt die Anzahl der Elemente, die in diesem Container gesichert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>