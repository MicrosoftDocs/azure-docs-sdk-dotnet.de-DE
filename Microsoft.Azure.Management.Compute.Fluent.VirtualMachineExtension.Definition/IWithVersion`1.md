<Type Name="IWithVersion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithVersion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithVersion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion`1" />
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
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der Definition des VM-Erweiterung zur Angabe von der Version der Erweiterung für virtuellen Computer ermöglicht diese Erweiterung basiert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt; WithVersion (string extensionImageVersionName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach`1&lt;!ParentT&gt; WithVersion(string extensionImageVersionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithVersion`1.WithVersion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithVersion (extensionImageVersionName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithVersion : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithVersion.WithVersion extensionImageVersionName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineExtension.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="extensionImageVersionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extensionImageVersionName">Der Name der.</param>
        <summary>
            Gibt die Version der Erweiterung des virtuellen Computers-Image.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>