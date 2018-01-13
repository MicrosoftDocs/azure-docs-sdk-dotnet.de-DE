<Type Name="IWithDiskSource&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithDiskSource&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDiskSource&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskSource`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithDiskSource`1" />
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
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der nicht verwalteten Daten auf den Datenträger Definition ermöglicht die Quelle auswählen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt; FromImage (int imageLun);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithFromImageDiskSettings`1&lt;!ParentT&gt; FromImage(int32 imageLun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithDiskSource`1.FromImage(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (imageLun As Integer) As IWithFromImageDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromImage : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;'ParentT&gt;" Usage="iWithDiskSource.FromImage imageLun" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithFromImageDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageLun" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="imageLun">Die LUN.</param>
        <summary>
            Gibt den Bezeichner des Bildes LUN des Datenträgerimages Quelle an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Definition von nicht verwalteten Daten-Datenträger.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt; WithNewVhd (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings`1&lt;!ParentT&gt; WithNewVhd(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithDiskSource`1.WithNewVhd(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewVhd (sizeInGB As Integer) As IWithNewVhdDiskSettings(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewVhd : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;'ParentT&gt;" Usage="iWithDiskSource.WithNewVhd sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetUnmanagedDataDisk.Definition.IWithNewVhdDiskSettings&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB">Die anfängliche Festplattengröße in GB.</param>
        <summary>
            Gibt an, nicht verwalteten Datenträger muss erstellt werden, eine neue virtuelle Festplatte eines angegebenen Größe.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Definition von nicht verwalteten Daten-Datenträger.</return>
      </Docs>
    </Member>
  </Members>
</Type>