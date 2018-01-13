<Type Name="IWithBranch&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBranch&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBranch`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBranch(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBranch&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Eine Web-app Quelle Steuerelementdefinition ermöglicht Verzweigung angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBranch">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithAttach&lt;ParentT&gt; WithBranch (string branch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithAttach`1&lt;!ParentT&gt; WithBranch(string branch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithBranch`1.WithBranch(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBranch (branch As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithBranch : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithBranch.WithBranch branch" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="branch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="branch">Die Verzweigung verwenden.</param>
        <summary>
            Gibt an, die Verzweigung im Repository zu verwenden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>