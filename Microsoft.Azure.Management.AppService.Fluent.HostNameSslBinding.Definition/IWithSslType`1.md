<Type Name="IWithSslType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSslType&lt;'ParentT&gt; = interface" />
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
            Die Phase der Hostname SSL-Bindungsdefinition zulassen von SSL-Typ angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIpBasedSsl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach&lt;ParentT&gt; WithIpBasedSsl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach`1&lt;!ParentT&gt; WithIpBasedSsl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1.WithIpBasedSsl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIpBasedSsl () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIpBasedSsl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSslType.WithIpBasedSsl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Verwendet IP-basiertes SSL. Kann nur ein Hostname gebundene IP-basiertes SSL.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithSniBasedSsl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach&lt;ParentT&gt; WithSniBasedSsl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach`1&lt;!ParentT&gt; WithSniBasedSsl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1.WithSniBasedSsl" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSniBasedSsl () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithSniBasedSsl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSslType.WithSniBasedSsl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Verwendet Servernamensanzeige (SNI)-basiertes SSL.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>