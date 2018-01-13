<Type Name="AzureIaaSComputeVMProtectableItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem">
  <TypeSignature Language="C#" Value="public class AzureIaaSComputeVMProtectableItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AzureIaaSComputeVMProtectableItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem" />
  <TypeSignature Language="VB.NET" Value="Public Class AzureIaaSComputeVMProtectableItem&#xA;Inherits IaaSVMProtectableItem" />
  <TypeSignature Language="F#" Value="type AzureIaaSComputeVMProtectableItem = class&#xA;    inherit IaaSVMProtectableItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Compute/virtualMachines")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="f3790-101">IaaS-VM arbeitsauslastungsspezifischen Sichern des Elements, das die Azure-Ressourcen-Manager-VM darstellt.</span><span class="sxs-lookup"><span data-stu-id="f3790-101">IaaS VM workload-specific backup item representing the Azure Resource Manager VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMProtectableItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f3790-102">Initialisiert eine neue Instanz der AzureIaaSComputeVMProtectableItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3790-102">Initializes a new instance of the AzureIaaSComputeVMProtectableItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AzureIaaSComputeVMProtectableItem (string backupManagementType = null, string friendlyName = null, string protectionState = null, string virtualMachineId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string friendlyName, string protectionState, string virtualMachineId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional friendlyName As String = null, Optional protectionState As String = null, Optional virtualMachineId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem : string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.AzureIaaSComputeVMProtectableItem (backupManagementType, friendlyName, protectionState, virtualMachineId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="protectionState" Type="System.String" />
        <Parameter Name="virtualMachineId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupManagementType"><span data-ttu-id="f3790-103">Typ der Sicherung Managemenent auf ein Element zu sichern.</span><span class="sxs-lookup"><span data-stu-id="f3790-103">Type of backup managemenent to backup an item.</span></span></param>
        <param name="friendlyName"><span data-ttu-id="f3790-104">Der Anzeigename für das Sichern des Elements.</span><span class="sxs-lookup"><span data-stu-id="f3790-104">Friendly name of the backup item.</span></span></param>
        <param name="protectionState"><span data-ttu-id="f3790-105">Status des Backup-Element.</span><span class="sxs-lookup"><span data-stu-id="f3790-105">State of the back up item.</span></span> <span data-ttu-id="f3790-106">Folgende Werte sind möglich: "Ungültig", 'Nichtgeschützt', 'Schutz', 'Protected'</span><span class="sxs-lookup"><span data-stu-id="f3790-106">Possible values include: 'Invalid', 'NotProtected', 'Protecting', 'Protected'</span></span></param>
        <param name="virtualMachineId"><span data-ttu-id="f3790-107">Vollqualifizierte ARM-ID des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="f3790-107">Fully qualified ARM ID of the virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="f3790-108">Initialisiert eine neue Instanz der AzureIaaSComputeVMProtectableItem-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f3790-108">Initializes a new instance of the AzureIaaSComputeVMProtectableItem class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>