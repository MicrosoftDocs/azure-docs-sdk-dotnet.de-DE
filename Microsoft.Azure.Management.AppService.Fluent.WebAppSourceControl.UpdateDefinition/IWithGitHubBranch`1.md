<Type Name="IWithGitHubBranch&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithGitHubBranch&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithGitHubBranch`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithGitHubBranch(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithGitHubBranch&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="33817-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="33817-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="33817-102">Eine Web-app Quelle Steuerelementdefinition ermöglicht Verzweigung angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="33817-102">A web app source control definition allowing branch to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBranch">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach&lt;ParentT&gt; WithBranch (string branch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach`1&lt;!ParentT&gt; WithBranch(string branch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IWithGitHubBranch`1.WithBranch(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBranch (branch As String) As IGitHubWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithBranch : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach&lt;'ParentT&gt;" Usage="iWithGitHubBranch.WithBranch branch" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebAppSourceControl.UpdateDefinition.IGitHubWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="branch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="branch"><span data-ttu-id="33817-103">Die Verzweigung verwenden.</span><span class="sxs-lookup"><span data-stu-id="33817-103">The branch to use.</span></span></param>
        <summary>
            <span data-ttu-id="33817-104">Gibt an, die Verzweigung im Repository zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="33817-104">Specifies the branch in the repository to use.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="33817-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="33817-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>