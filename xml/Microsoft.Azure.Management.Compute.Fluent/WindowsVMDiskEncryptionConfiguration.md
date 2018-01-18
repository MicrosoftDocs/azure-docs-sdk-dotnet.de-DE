<Type Name="WindowsVMDiskEncryptionConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration">
  <TypeSignature Language="C#" Value="public sealed class WindowsVMDiskEncryptionConfiguration : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit WindowsVMDiskEncryptionConfiguration extends Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1&lt;class Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class WindowsVMDiskEncryptionConfiguration&#xA;Inherits VirtualMachineEncryptionConfiguration(Of WindowsVMDiskEncryptionConfiguration)" />
  <TypeSignature Language="F#" Value="type WindowsVMDiskEncryptionConfiguration = class&#xA;    inherit VirtualMachineEncryptionConfiguration&lt;WindowsVMDiskEncryptionConfiguration&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="264a9-101">Geben Sie die Darstellung Verschlüsselungskonfiguration auf einem virtuellen Windows-Computer angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="264a9-101">Type representing encryption configuration to be applied to a Windows virtual machine.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WindowsVMDiskEncryptionConfiguration (string keyVaultId, string aadClientId, string aadSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyVaultId, string aadClientId, string aadSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyVaultId As String, aadClientId As String, aadSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration (keyVaultId, aadClientId, aadSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="aadClientId" Type="System.String" />
        <Parameter Name="aadSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyVaultId"><span data-ttu-id="264a9-102">Die Ressourcen-Id des schlüsseltresors auf den Datenträger-Verschlüsselungsschlüssel zu speichern.</span><span class="sxs-lookup"><span data-stu-id="264a9-102">The resource id of the key vault to store the disk encryption key.</span></span></param>
        <param name="aadClientId"><span data-ttu-id="264a9-103">Client-Id einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</span><span class="sxs-lookup"><span data-stu-id="264a9-103">Client id of an AAD application which has permission to the key vault.</span></span></param>
        <param name="aadSecret"><span data-ttu-id="264a9-104">Der geheime Clientschlüssel, der AadClientId entspricht.</span><span class="sxs-lookup"><span data-stu-id="264a9-104">Client secret corresponding to the aadClientId.</span></span></param>
        <summary>
             <span data-ttu-id="264a9-105">WindowsVMDiskEncryptionConfiguration wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="264a9-105">Creates WindowsVMDiskEncryptionConfiguration.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function OsType () As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="override this.OsType : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="windowsVMDiskEncryptionConfiguration.OsType " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>