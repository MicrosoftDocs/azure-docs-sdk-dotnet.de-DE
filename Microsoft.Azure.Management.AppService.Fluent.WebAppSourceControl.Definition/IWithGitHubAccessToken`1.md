<Type Name="IWithGitHubAccessToken&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubAccessToken&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithGitHubAccessToken&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithGitHubAccessToken`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubAccessToken`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithGitHubAccessToken(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithGitHubAccessToken&lt;'ParentT&gt; = interface" />
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
            Eine Web-app Quelle Steuerelementdefinition ermöglicht GitHub Zugriffstoken angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithGitHubAccessToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach&lt;ParentT&gt; WithGitHubAccessToken (string personalAccessToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach`1&lt;!ParentT&gt; WithGitHubAccessToken(string personalAccessToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IWithGitHubAccessToken`1.WithGitHubAccessToken(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithGitHubAccessToken (personalAccessToken As String) As IGitHubWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithGitHubAccessToken : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach&lt;'ParentT&gt;" Usage="iWithGitHubAccessToken.WithGitHubAccessToken personalAccessToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.Definition.IGitHubWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="personalAccessToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="personalAccessToken">Das persönliche Zugriffstoken von GitHub.</param>
        <summary>
            Gibt das persönliche Zugriffstoken GitHub an. Sie können einen aus https://github.com/settings/tokens erwerben.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>