<Type Name="LinuxVMDiskEncryptionConfiguration" FullName="Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration">
  <TypeSignature Language="C#" Value="public sealed class LinuxVMDiskEncryptionConfiguration : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit LinuxVMDiskEncryptionConfiguration extends Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration`1&lt;class Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LinuxVMDiskEncryptionConfiguration&#xA;Inherits VirtualMachineEncryptionConfiguration(Of LinuxVMDiskEncryptionConfiguration)" />
  <TypeSignature Language="F#" Value="type LinuxVMDiskEncryptionConfiguration = class&#xA;    inherit VirtualMachineEncryptionConfiguration&lt;LinuxVMDiskEncryptionConfiguration&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineEncryptionConfiguration&lt;Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             Geben Sie für Einstellungen für die Verschlüsselung auf einem virtuellen Linux-Computer angewendet werden soll.
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxVMDiskEncryptionConfiguration (string keyVaultId, string aadClientId, string aadSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyVaultId, string aadClientId, string aadSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyVaultId As String, aadClientId As String, aadSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" Usage="new Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration (keyVaultId, aadClientId, aadSecret)" />
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
        <param name="keyVaultId">Die Ressourcen-Id des schlüsseltresors auf den Datenträger-Verschlüsselungsschlüssel zu speichern.</param>
        <param name="aadClientId">Client-Id einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</param>
        <param name="aadSecret">Der geheime Clientschlüssel, der AadClientId entspricht.</param>
        <summary>
             LinuxVMDiskEncryptionSettings wird erstellt.
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public override Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OsType() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function OsType () As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="override this.OsType : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="linuxVMDiskEncryptionConfiguration.OsType " />
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
    <Member MemberName="WithPassPhrase">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration WithPassPhrase (string passPhrase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration WithPassPhrase(string passPhrase) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration.WithPassPhrase(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPassPhrase (passPhrase As String) As LinuxVMDiskEncryptionConfiguration" />
      <MemberSignature Language="F#" Value="member this.WithPassPhrase : string -&gt; Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" Usage="linuxVMDiskEncryptionConfiguration.WithPassPhrase passPhrase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="passPhrase" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="passPhrase">Die Passphrase.</param>
        <summary>
             Gibt die Passphrase zum Verschlüsseln von Linux-Betriebssystem oder Daten Datenträger an.
             </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>LinuxVMDiskEncryptionSettings.</return>
      </Docs>
    </Member>
  </Members>
</Type>