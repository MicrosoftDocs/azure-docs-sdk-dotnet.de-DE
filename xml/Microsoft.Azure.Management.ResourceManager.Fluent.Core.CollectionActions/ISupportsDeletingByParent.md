<Type Name="ISupportsDeletingByParent" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent">
  <TypeSignature Language="C#" Value="public interface ISupportsDeletingByParent" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsDeletingByParent" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsDeletingByParent" />
  <TypeSignature Language="F#" Value="type ISupportsDeletingByParent = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ce70a-101">Bietet Zugriff auf das Abrufen einer bestimmten Azure-Ressource, die basierend auf seinem Ressourcengruppe und übergeordneten.</span><span class="sxs-lookup"><span data-stu-id="ce70a-101">Provides access to getting a specific Azure resource based on its resource group and parent.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteByParent">
      <MemberSignature Language="C#" Value="public void DeleteByParent (string groupName, string parentName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteByParent(string groupName, string parentName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent.DeleteByParent(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteByParent (groupName As String, parentName As String, name As String)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByParent : string * string * string -&gt; unit" Usage="iSupportsDeletingByParent.DeleteByParent (groupName, parentName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="groupName"><span data-ttu-id="ce70a-102">Die Gruppe der Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="ce70a-102">The group the resource is part of.</span></span></param>
        <param name="parentName"><span data-ttu-id="ce70a-103">der Name der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="ce70a-103">The name of parent resource.</span></span></param>
        <param name="name"><span data-ttu-id="ce70a-104">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ce70a-104">The name of the resource.</span></span></param>
        <summary>
            <span data-ttu-id="ce70a-105">Löscht eine Ressource von Azure, die durch den Namen und die Ressourcengruppe identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="ce70a-105">Deletes a resource from Azure, identifying it by its name and its resource group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteByParentAsync (string groupName, string parentName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteByParentAsync(string groupName, string parentName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByParent.DeleteByParentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByParentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSupportsDeletingByParent.DeleteByParentAsync (groupName, parentName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="groupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="groupName"><span data-ttu-id="ce70a-106">Die Gruppe der Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="ce70a-106">The group the resource is part of.</span></span></param>
        <param name="parentName"><span data-ttu-id="ce70a-107">der Name der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="ce70a-107">The name of parent resource.</span></span></param>
        <param name="name"><span data-ttu-id="ce70a-108">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ce70a-108">The name of the resource.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="ce70a-109">Löschen Sie eine Ressource asynchron von Azure, die durch den Namen und die Ressourcengruppe identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="ce70a-109">Asynchronously delete a resource from Azure, identifying it by its name and its resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ce70a-110">Observable-Objekt für die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="ce70a-110">An observable to the request.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>