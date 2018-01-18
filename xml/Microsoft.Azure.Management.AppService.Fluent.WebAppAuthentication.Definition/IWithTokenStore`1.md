<Type Name="IWithTokenStore&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithTokenStore&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTokenStore`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTokenStore(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithTokenStore&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="48dc7-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="48dc7-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="48dc7-102">Eine Web-app-Authentifizierung Definition ermöglicht Tokenspeichers angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="48dc7-102">A web app authentication definition allowing token store to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTokenStore">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt; WithTokenStore (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach`1&lt;!ParentT&gt; WithTokenStore(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithTokenStore`1.WithTokenStore(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTokenStore (enabled As Boolean) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithTokenStore : bool -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithTokenStore.WithTokenStore enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppAuthentication.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="48dc7-103">"True", wenn Tokenspeichers aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="48dc7-103">True if token store should be enabled.</span></span></param>
        <summary>
            <span data-ttu-id="48dc7-104">Gibt an, ob Tokenspeichers aktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="48dc7-104">Specifies if token store should be enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="48dc7-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="48dc7-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>