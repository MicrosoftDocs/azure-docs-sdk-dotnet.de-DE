<Type Name="IaaSVMProtectableItem" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem">
  <TypeSignature Language="C#" Value="public class IaaSVMProtectableItem : Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IaaSVMProtectableItem extends Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem" />
  <TypeSignature Language="VB.NET" Value="Public Class IaaSVMProtectableItem&#xA;Inherits WorkloadProtectableItem" />
  <TypeSignature Language="F#" Value="type IaaSVMProtectableItem = class&#xA;    inherit WorkloadProtectableItem" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.RecoveryServices.Backup.Models.WorkloadProtectableItem</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            IaaS-VM arbeitsauslastungsspezifischen Sichern des Elements.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaaSVMProtectableItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der IaaSVMProtectableItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IaaSVMProtectableItem (string backupManagementType = null, string friendlyName = null, string protectionState = null, string virtualMachineId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string backupManagementType, string friendlyName, string protectionState, string virtualMachineId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional backupManagementType As String = null, Optional friendlyName As String = null, Optional protectionState As String = null, Optional virtualMachineId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem : string * string * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem (backupManagementType, friendlyName, protectionState, virtualMachineId)" />
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
        <param name="backupManagementType">Typ der Sicherung Managemenent auf ein Element zu sichern.</param>
        <param name="friendlyName">Der Anzeigename für das Sichern des Elements.</param>
        <param name="protectionState">Status des Backup-Element. Folgende Werte sind möglich: "Ungültig", 'Nichtgeschützt', 'Schutz', 'Protected'</param>
        <param name="virtualMachineId">Vollqualifizierte ARM-ID des virtuellen Computers.</param>
        <summary>
            Initialisiert eine neue Instanz der IaaSVMProtectableItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineId">
      <MemberSignature Language="C#" Value="public string VirtualMachineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualMachineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem.VirtualMachineId" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineId As String" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.IaaSVMProtectableItem.VirtualMachineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="virtualMachineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest vollqualifizierte ARM-ID des virtuellen Computers.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>