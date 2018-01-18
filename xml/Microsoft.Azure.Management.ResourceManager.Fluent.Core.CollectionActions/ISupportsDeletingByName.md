<Type Name="ISupportsDeletingByName" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName">
  <TypeSignature Language="C#" Value="public interface ISupportsDeletingByName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsDeletingByName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsDeletingByName" />
  <TypeSignature Language="F#" Value="type ISupportsDeletingByName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteByName">
      <MemberSignature Language="C#" Value="public void DeleteByName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteByName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName.DeleteByName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteByName (name As String)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByName : string -&gt; unit" Usage="iSupportsDeletingByName.DeleteByName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="b44c4-101">der Name der Ressource löschen</span><span class="sxs-lookup"><span data-stu-id="b44c4-101">the name of the resource to delete</span></span></param>
        <summary>
            <span data-ttu-id="b44c4-102">Löscht eine Ressource von Azure, mit dem Ressourcennamen identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="b44c4-102">Deletes a resource from Azure, identifying it by its resource name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteByNameAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteByNameAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName.DeleteByNameAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByNameAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSupportsDeletingByName.DeleteByNameAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="b44c4-103">der Name der Ressource löschen</span><span class="sxs-lookup"><span data-stu-id="b44c4-103">the name of the resource to delete</span></span></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="b44c4-104">Löscht eine Ressource asynchron von Azure, mit dem Ressourcennamen identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="b44c4-104">Deletes a resource asynchronously from Azure, identifying it by its resource name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>