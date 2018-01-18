<Type Name="ISupportsListingInResourceGroupByTag&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingInResourceGroupByTag&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsListingInResourceGroupByTag&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsListingInResourceGroupByTag`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingInResourceGroupByTag`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsListingInResourceGroupByTag(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsListingInResourceGroupByTag&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>
            <span data-ttu-id="38b6b-101">Bietet Zugriff auf Azure-Ressourcen eines bestimmten Typs auf Grundlage ihrer Tags auflisten.</span><span class="sxs-lookup"><span data-stu-id="38b6b-101">Provides access to listing Azure resources of a specific type based on their tag.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByTag">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByTag (string resourceGroupName, string tagName, string tagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByTag(string resourceGroupName, string tagName, string tagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingInResourceGroupByTag`1.ListByTag(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByTag (resourceGroupName As String, tagName As String, tagValue As String) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByTag : string * string * string -&gt; seq&lt;'T&gt;" Usage="iSupportsListingInResourceGroupByTag.ListByTag (resourceGroupName, tagName, tagValue)" />
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
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="38b6b-102">Der Name der Ressourcengruppe zum Auflisten der Ressourcen aus.</span><span class="sxs-lookup"><span data-stu-id="38b6b-102">The name of the resource group to list the resources from.</span></span></param>
        <param name="tagName"><span data-ttu-id="38b6b-103">Tagname als Schlüssel</span><span class="sxs-lookup"><span data-stu-id="38b6b-103">tag's name as the key</span></span></param>
        <param name="tagValue"><span data-ttu-id="38b6b-104">Tag Wert</span><span class="sxs-lookup"><span data-stu-id="38b6b-104">tag's value</span></span></param>
        <summary>
            <span data-ttu-id="38b6b-105">Listet alle Ressourcen mit dem angegebenen Tag.</span><span class="sxs-lookup"><span data-stu-id="38b6b-105">Lists all the resources with the specified tag.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="38b6b-106">Die Liste der Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="38b6b-106">The list of resources.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByTagAsync (string resourceGroupName, string tagName, string tagValue, bool loadAllPages = true, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByTagAsync(string resourceGroupName, string tagName, string tagValue, bool loadAllPages, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingInResourceGroupByTag`1.ListByTagAsync(System.String,System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTagAsync : string * string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="iSupportsListingInResourceGroupByTag.ListByTagAsync (resourceGroupName, tagName, tagValue, loadAllPages, cancellationToken)" />
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
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
        <Parameter Name="loadAllPages" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="38b6b-107">Der Name der Ressourcengruppe zum Auflisten der Ressourcen aus.</span><span class="sxs-lookup"><span data-stu-id="38b6b-107">The name of the resource group to list the resources from.</span></span></param>
        <param name="tagName"><span data-ttu-id="38b6b-108">Tagname als Schlüssel</span><span class="sxs-lookup"><span data-stu-id="38b6b-108">tag's name as the key</span></span></param>
        <param name="tagValue"><span data-ttu-id="38b6b-109">Tag Wert</span><span class="sxs-lookup"><span data-stu-id="38b6b-109">tag's value</span></span></param>
        <param name="loadAllPages"><span data-ttu-id="38b6b-110">Geben Sie "true", um alle Seiten, die zum Abrufen von paginierten Ergebnis "false" zu laden.</span><span class="sxs-lookup"><span data-stu-id="38b6b-110">Specify true to load all pages, false to get paginated result</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="38b6b-111">das Abbruchtoken, das das cancellationToken</span><span class="sxs-lookup"><span data-stu-id="38b6b-111">cancellationToken the cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="38b6b-112">Listet alle Ressourcen mit dem angegebenen Tag.</span><span class="sxs-lookup"><span data-stu-id="38b6b-112">Lists all the resources with the specified tag.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="38b6b-113">Eine "await" können Aufgabe für asynchrone Vorgang, der PagedCollection Ressourcen verfügt.</span><span class="sxs-lookup"><span data-stu-id="38b6b-113">A await-able Task for asynchronous operation which will have PagedCollection of the resources.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>