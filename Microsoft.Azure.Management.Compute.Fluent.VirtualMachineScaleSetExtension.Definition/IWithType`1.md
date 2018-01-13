<Type Name="IWithType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithType&lt;'ParentT&gt; = interface" />
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
            Die Phase der VM-Skalierungsgruppe festgelegt Erweiterung Definition ermöglicht, zur Angabe des Image des virtuellen Computers Scale Set-Erweiterung, die diese Erweiterung basiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithVersion&lt;ParentT&gt; WithType (string extensionImageTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithVersion`1&lt;!ParentT&gt; WithType(string extensionImageTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithType`1.WithType(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithType (extensionImageTypeName As String) As IWithVersion(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithType : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithVersion&lt;'ParentT&gt;" Usage="iWithType.WithType extensionImageTypeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.Definition.IWithVersion&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImageTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImageTypeName">Der Name des Bilds.</param>
        <summary>
            Gibt den Typ des Image des virtuellen Computers Scale Set-Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>