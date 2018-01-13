<Type Name="IWithDefaultAuthenticationProvider&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithDefaultAuthenticationProvider&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDefaultAuthenticationProvider&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDefaultAuthenticationProvider`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithDefaultAuthenticationProvider`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDefaultAuthenticationProvider(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDefaultAuthenticationProvider&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp des endgültigen Attachable.attach().</typeparam>
    <summary>
            Eine Web-app-Authentifizierung Definition ermöglicht den Standardanbieter für die Authentifizierung festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAnonymousAuthentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithAnonymousAuthentication ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithAnonymousAuthentication() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithDefaultAuthenticationProvider`1.WithAnonymousAuthentication" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAnonymousAuthentication () As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAnonymousAuthentication : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithDefaultAuthenticationProvider.WithAnonymousAuthentication " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Erfordert keine Anmeldung in der Standardeinstellung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithDefaultAuthenticationProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithDefaultAuthenticationProvider (Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithDefaultAuthenticationProvider(valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithDefaultAuthenticationProvider`1.WithDefaultAuthenticationProvider(Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDefaultAuthenticationProvider (provider As BuiltInAuthenticationProvider) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDefaultAuthenticationProvider : Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithDefaultAuthenticationProvider.WithDefaultAuthenticationProvider provider" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.Azure.Management.AppService.Fluent.Models.BuiltInAuthenticationProvider" />
      </Parameters>
      <Docs>
        <param name="provider">Der Standard-Authentifizierungsanbieter.</param>
        <summary>
            Gibt den Standardanbieter für die Authentifizierung an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>