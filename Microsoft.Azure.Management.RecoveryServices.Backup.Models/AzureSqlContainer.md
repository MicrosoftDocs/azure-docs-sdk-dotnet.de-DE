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
            Azure Sql-spezifische-Container.
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
            Initialisiert eine neue Instanz der AzureSqlContainer-Klasse.
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
        <param name="friendlyName">Anzeigename des Containers.</param>
        <param name="backupManagementType">Typ der Sicherung Managemenent für den Container. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="registrationStatus">Status der Registrierung des Containers mit der Recovery Services-Tresor.</param>
        <param name="healthStatus">Status der Integrität des Containers.</param>
        <param name="containerType">Der Typ des Containers. Der Wert dieser Eigenschaft für: 1. Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist. Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3. Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4. Azure SQL-Instanz ist AzureSqlContainer. Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</param>
        <summary>
            Initialisiert eine neue Instanz der AzureSqlContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>