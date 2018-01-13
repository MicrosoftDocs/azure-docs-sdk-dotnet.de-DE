<Type Name="IWithDiskSource&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDiskSource&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskSource`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskSource(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDiskSource&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase des übergeordneten Updates wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase von den Daten Datenträger Definition ermöglicht die Quelle auswählen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings&lt;ParentT&gt; WithExistingVhd (string storageAccountName, string containerName, string vhdName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings`1&lt;!ParentT&gt; WithExistingVhd(string storageAccountName, string containerName, string vhdName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource`1.WithExistingVhd(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingVhd (storageAccountName As String, containerName As String, vhdName As String) As IWithVhdAttachedDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingVhd : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings&lt;'ParentT&gt;" Usage="iWithDiskSource.WithExistingVhd (storageAccountName, containerName, vhdName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithVhdAttachedDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="vhdName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccountName">Der Name des Speicherkontos.</param>
        <param name="containerName">Der Name des Containers an, VHD-Datei enthalten.</param>
        <param name="vhdName">Der Name der VHD-Datei angefügt werden soll.</param>
        <summary>
            Gibt die vorhandene Quelle VHD des Datenträgers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Datendefinition der Datenträger.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithNewVhd (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithNewVhd(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithDiskSource`1.WithNewVhd(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewVhd (sizeInGB As Integer) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewVhd : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithDiskSource.WithNewVhd sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineUnmanagedDataDisk.UpdateDefinition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die anfängliche Festplattengröße in GB.</param>
        <summary>
            Gibt an, diesen Datenträger muss erstellt werden, eine neue virtuelle Festplatte eines angegebenen Größe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Datendefinition der Datenträger.</return>
      </Docs>
    </Member>
  </Members>
</Type>