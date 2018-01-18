<Type Name="IWithType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithType`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="a9a5e-101">Die Phase des übergeordneten Updates wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="a9a5e-101">The stage of the parent update to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a9a5e-102">Die Phase der VM-Skalierungsgruppe festgelegt Erweiterung Definition ermöglicht, zur Angabe des Image des virtuellen Computers Scale Set-Erweiterung, die diese Erweiterung basiert.</span><span class="sxs-lookup"><span data-stu-id="a9a5e-102">The stage of a virtual machine scale set extension definition allowing to specify the type of the virtual machine scale set extension image this extension is based on.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion&lt;ParentT&gt; WithType (string extensionImageTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion`1&lt;!ParentT&gt; WithType(string extensionImageTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithType`1.WithType(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithType (extensionImageTypeName As String) As IWithVersion(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithType : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion&lt;'ParentT&gt;" Usage="iWithType.WithType extensionImageTypeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImageTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImageTypeName"><span data-ttu-id="a9a5e-103">Ein Image-Typname.</span><span class="sxs-lookup"><span data-stu-id="a9a5e-103">An image type name.</span></span></param>
        <summary>
            <span data-ttu-id="a9a5e-104">Gibt den Typ des Image des virtuellen Computers Scale Set-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="a9a5e-104">Specifies the type of the virtual machine scale set extension image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a9a5e-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a9a5e-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>