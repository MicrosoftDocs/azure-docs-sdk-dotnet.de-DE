<Type Name="IWithVersion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithVersion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithVersion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithVersion(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithVersion&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="9ed97-101">Die Phase des übergeordneten Updates wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="9ed97-101">The stage of the parent update to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9ed97-102">Die Phase der VM-Skalierungsgruppe festgelegt Erweiterung Definition ermöglicht, den Typ der virtuellen Maschine Skalierung Satz Erweiterungsversion angeben, die diese Erweiterung basiert.</span><span class="sxs-lookup"><span data-stu-id="9ed97-102">The stage of a virtual machine scale set extension definition allowing to specify the type of the virtual machine scale set extension version this extension is based on.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithVersion (string extensionImageVersionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithVersion(string extensionImageVersionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithVersion`1.WithVersion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVersion (extensionImageVersionName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithVersion : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithVersion.WithVersion extensionImageVersionName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetExtension.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImageVersionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImageVersionName"><span data-ttu-id="9ed97-103">Der Versionsname einer.</span><span class="sxs-lookup"><span data-stu-id="9ed97-103">A version name.</span></span></param>
        <summary>
            <span data-ttu-id="9ed97-104">Gibt die Version der Erweiterung des virtuellen Computers Scale Set-Image.</span><span class="sxs-lookup"><span data-stu-id="9ed97-104">Specifies the version of the virtual machine scale set image extension.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9ed97-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9ed97-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>