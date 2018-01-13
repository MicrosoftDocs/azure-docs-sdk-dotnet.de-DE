<Type Name="AzureIaaSClassicComputeVMContainer" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer">
  <TypeSignature Language="C#" Value="public class AzureIaaSClassicComputeVMContainer : Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSClassicComputeVMContainer extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSClassicComputeVMContainer&#xA;Inherits IaaSVMContainer" />
  <TypeSignature Language="F#" Value="type AzureIaaSClassicComputeVMContainer = class&#xA;    inherit IaaSVMContainer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMContainer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.ClassicCompute/virtualMachines")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            IaaS-VM arbeitsauslastungsspezifischen Sichern des Elements, das einen klassischen virtuellen Computer darstellt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSClassicComputeVMContainer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSClassicComputeVMContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSClassicComputeVMContainer (string friendlyName = null, string backupManagementType = null, string registrationStatus = null, string healthStatus = null, string containerType = null, string virtualMachineId = null, string virtualMachineVersion = null, string resourceGroup = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string backupManagementType, string registrationStatus, string healthStatus, string containerType, string virtualMachineId, string virtualMachineVersion, string resourceGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional friendlyName As String = null, Optional backupManagementType As String = null, Optional registrationStatus As String = null, Optional healthStatus As String = null, Optional containerType As String = null, Optional virtualMachineId As String = null, Optional virtualMachineVersion As String = null, Optional resourceGroup As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer : string * string * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSClassicComputeVMContainer (friendlyName, backupManagementType, registrationStatus, healthStatus, containerType, virtualMachineId, virtualMachineVersion, resourceGroup)" />
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
        <Parameter Name="virtualMachineId" Type="System.String" />
        <Parameter Name="virtualMachineVersion" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="friendlyName">Anzeigename des Containers.</param>
        <param name="backupManagementType">Typ der Sicherung Managemenent für den Container. Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</param>
        <param name="registrationStatus">Status der Registrierung des Containers mit der Recovery Services-Tresor.</param>
        <param name="healthStatus">Status der Integrität des Containers.</param>
        <param name="containerType">Der Typ des Containers. Der Wert dieser Eigenschaft für: 1. Berechnen Sie, dass Azure-VM Microsoft.Compute/virtualMachines 2 ist. Klassisches Azure-VM zu berechnen ist Microsoft.ClassicCompute/virtualMachines 3. Windows-Computer (z. B. MAK, DPM usw.) ist Windows 4. Azure SQL-Instanz ist AzureSqlContainer. Folgende Werte sind möglich: "Ungültig", "Unbekannt", "IaasVMContainer", "IaasVMServiceContainer", "DPMContainer", "AzureBackupServerContainer", "MABContainer", "Cluster", 'AzureSqlContainer', 'Windows', "VCenter"</param>
        <param name="virtualMachineId">Vollständig qualifiziert ARM-Url des virtuellen Computers von diesem Container Azure IaaS-VM dargestellt.</param>
        <param name="virtualMachineVersion">Gibt an, ob der Container eine Classic oder einer Azure-Ressourcen-Manager-VM darstellt.</param>
        <param name="resourceGroup">Der Ressourcengruppenname der Recovery Services-Tresor.</param>
        <summary>
            Initialisiert eine neue Instanz der AzureIaaSClassicComputeVMContainer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>