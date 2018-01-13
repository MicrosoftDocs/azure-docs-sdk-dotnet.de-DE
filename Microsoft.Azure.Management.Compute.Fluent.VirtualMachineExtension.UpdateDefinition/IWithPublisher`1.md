<Type Name="IWithPublisher&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithPublisher&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPublisher&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPublisher`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithPublisher`1" />
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
    <typeparam name="ParentT">Die Phase des übergeordneten Updates wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der Definition des VM-Erweiterung an den Herausgeber der Erweiterung-Image des virtuellen Computers ermöglicht diese Erweiterung basiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPublisher">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithType&lt;ParentT&gt; WithPublisher (string extensionImagePublisherName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithType`1&lt;!ParentT&gt; WithPublisher(string extensionImagePublisherName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithPublisher`1.WithPublisher(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublisher (extensionImagePublisherName As String) As IWithType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPublisher : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithType&lt;'ParentT&gt;" Usage="iWithPublisher.WithPublisher extensionImagePublisherName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.UpdateDefinition.IWithType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImagePublisherName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImagePublisherName">Der Name des Verlegers.</param>
        <summary>
            Gibt den Namen des Verlegers Image der virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>