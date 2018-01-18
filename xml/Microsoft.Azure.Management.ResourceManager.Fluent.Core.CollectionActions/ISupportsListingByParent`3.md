<Type Name="ISupportsListingByParent&lt;T,ParentT,ManagerT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent&lt;T,ParentT,ManagerT&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsListingByParent&lt;T,ParentT,ManagerT&gt; where ParentT : IResource, IHasResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsListingByParent`3&lt;T, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup) ParentT, ManagerT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsListingByParent(Of T, ParentT, ManagerT)" />
  <TypeSignature Language="F#" Value="type ISupportsListingByParent&lt;'T, 'ParentT, 'ManagerT (requires 'ParentT :&gt; IResource and 'ParentT :&gt; IHasResourceGroup)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
    <TypeParameter Name="ParentT">
      <Constraints>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="ManagerT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <typeparam name="ParentT">To be added.</typeparam>
    <typeparam name="ManagerT">To be added.</typeparam>
    <summary>
            <span data-ttu-id="ae1cc-101">Bietet Zugriff auf Azure-Ressourcen eines bestimmten Typs in einer bestimmten übergeordneten Ressource auflisten.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-101">Provides access to listing Azure resources of a specific type in a specific parent resource.</span></span>
            
            <span data-ttu-id="ae1cc-102">(Hinweis: Diese Schnittstelle ist keine Implementierung durch Benutzercode vorgesehen).</span><span class="sxs-lookup"><span data-stu-id="ae1cc-102">(Note: this interface is not intended to be implemented by user code).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByParent">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByParent (ParentT parentResource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByParent(!ParentT parentResource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParent(`1)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByParent (parentResource As ParentT) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByParent : 'ParentT -&gt; seq&lt;'T&gt;" Usage="iSupportsListingByParent.ListByParent parentResource" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
      </Parameters>
      <Docs>
        <param name="parentResource"><span data-ttu-id="ae1cc-103">die Instanz des übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-103">The instance of parent resource.</span></span></param>
        <summary>
            <span data-ttu-id="ae1cc-104">Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-104">Gets the information about a resource from Azure based on the resource id.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ae1cc-105">Eine unveränderliche Darstellung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-105">An immutable representation of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListByParent">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByParent (string resourceGroupName, string parentName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByParent(string resourceGroupName, string parentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParent(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByParent (resourceGroupName As String, parentName As String) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByParent : string * string -&gt; seq&lt;'T&gt;" Usage="iSupportsListingByParent.ListByParent (resourceGroupName, parentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="ae1cc-106">Der Name der Ressourcengruppe zum Auflisten der Ressourcen aus.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-106">The name of the resource group to list the resources from.</span></span></param>
        <param name="parentName"><span data-ttu-id="ae1cc-107">der Name der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-107">The name of parent resource.</span></span></param>
        <summary>
            <span data-ttu-id="ae1cc-108">Listet die Ressourcen des angegebenen Typs in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-108">Lists resources of the specified type in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ae1cc-109">Die Liste der Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-109">The list of resources.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByParentAsync (ParentT parentResource, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByParentAsync(!ParentT parentResource, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParentAsync(`1,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByParentAsync : 'ParentT * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="iSupportsListingByParent.ListByParentAsync (parentResource, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentResource"><span data-ttu-id="ae1cc-110">die Instanz des übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-110">The instance of parent resource.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="ae1cc-111">Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-111">Gets the information about a resource from Azure based on the resource id.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ae1cc-112">Eine unveränderliche Darstellung der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-112">An immutable representation of the resource.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByParentAsync (string resourceGroupName, string parentName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByParentAsync(string resourceGroupName, string parentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByParent`3.ListByParentAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByParentAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="iSupportsListingByParent.ListByParentAsync (resourceGroupName, parentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="ae1cc-113">Der Name der Ressourcengruppe zum Auflisten der Ressourcen aus.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-113">The name of the resource group to list the resources from.</span></span></param>
        <param name="parentName"><span data-ttu-id="ae1cc-114">der Name der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-114">The name of parent resource.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="ae1cc-115">Listet die Ressourcen des angegebenen Typs in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-115">Lists resources of the specified type in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ae1cc-116">Die Liste der Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="ae1cc-116">The list of resources.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>