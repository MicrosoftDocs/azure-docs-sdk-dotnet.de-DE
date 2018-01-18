<Type Name="IWithPublisher&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithPublisher&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPublisher&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPublisher`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithPublisher`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPublisher(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPublisher&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="02960-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="02960-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="02960-102">Die Phase der Definition des VM-Erweiterung an den Herausgeber der Erweiterung-Image des virtuellen Computers ermöglicht diese Erweiterung basiert.</span><span class="sxs-lookup"><span data-stu-id="02960-102">The stage of the virtual machine extension definition allowing to specify the publisher of the virtual machine extension image this extension is based on.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPublisher">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType&lt;ParentT&gt; WithPublisher (string extensionImagePublisherName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType`1&lt;!ParentT&gt; WithPublisher(string extensionImagePublisherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithPublisher`1.WithPublisher(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublisher (extensionImagePublisherName As String) As IWithType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublisher : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType&lt;'ParentT&gt;" Usage="iWithPublisher.WithPublisher extensionImagePublisherName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImagePublisherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImagePublisherName"><span data-ttu-id="02960-103">Der Name des Verlegers.</span><span class="sxs-lookup"><span data-stu-id="02960-103">The publisher name.</span></span></param>
        <summary>
            <span data-ttu-id="02960-104">Gibt den Namen des Verlegers Image der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="02960-104">Specifies the name of the virtual machine extension image publisher.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="02960-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="02960-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>