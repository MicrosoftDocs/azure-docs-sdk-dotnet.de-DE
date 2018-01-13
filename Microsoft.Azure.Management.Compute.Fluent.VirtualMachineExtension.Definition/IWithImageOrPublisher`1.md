<Type Name="IWithImageOrPublisher&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithImageOrPublisher&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithImageOrPublisher&lt;ParentT&gt; : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithPublisher&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithImageOrPublisher`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithPublisher`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithImageOrPublisher`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithImageOrPublisher(Of ParentT)&#xA;Implements IWithPublisher(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithImageOrPublisher&lt;'ParentT&gt; = interface&#xA;    interface IWithPublisher&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithPublisher&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der Definition des VM-Erweiterung Erweiterung Bild angeben, oder geben Sie Namen des Verlegers der virtuellen Computer ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage image);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage image) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithImageOrPublisher`1.WithImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithImage (image As IVirtualMachineExtensionImage) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithImageOrPublisher.WithImage image" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImage" />
      </Parameters>
      <Docs>
        <param name="image">Das Bild.</param>
        <summary>
            Gibt an, das Image des virtuellen Computers Erweiterung verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>