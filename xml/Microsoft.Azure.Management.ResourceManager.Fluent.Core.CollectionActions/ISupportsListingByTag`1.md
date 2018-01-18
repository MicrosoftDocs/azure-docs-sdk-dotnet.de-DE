<Type Name="ISupportsListingByTag&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsListingByTag&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsListingByTag`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsListingByTag(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsListingByTag&lt;'T&gt; = interface" />
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
            <span data-ttu-id="ba910-101">Bietet Zugriff auf Azure-Ressourcen eines bestimmten Typs auf Grundlage ihrer Tags auflisten.</span><span class="sxs-lookup"><span data-stu-id="ba910-101">Provides access to listing Azure resources of a specific type based on their tag.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByTag">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;T&gt; ListByTag (string tagName, string tagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!T&gt; ListByTag(string tagName, string tagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag`1.ListByTag(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByTag (tagName As String, tagValue As String) As IEnumerable(Of T)" />
      <MemberSignature Language="F#" Value="abstract member ListByTag : string * string -&gt; seq&lt;'T&gt;" Usage="iSupportsListingByTag.ListByTag (tagName, tagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tagName"><span data-ttu-id="ba910-102">Tagname als Schlüssel</span><span class="sxs-lookup"><span data-stu-id="ba910-102">tag's name as the key</span></span></param>
        <param name="tagValue"><span data-ttu-id="ba910-103">Tag Wert</span><span class="sxs-lookup"><span data-stu-id="ba910-103">tag's value</span></span></param>
        <summary>
            <span data-ttu-id="ba910-104">Listet alle Ressourcen mit dem angegebenen Tag.</span><span class="sxs-lookup"><span data-stu-id="ba910-104">Lists all the resources with the specified tag.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ba910-105">Die Liste der Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="ba910-105">The list of resources.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListByTagAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt; ListByTagAsync (string tagName, string tagValue, bool loadAllPages = true, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection`1&lt;!T&gt;&gt; ListByTagAsync(string tagName, string tagValue, bool loadAllPages, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag`1.ListByTagAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByTagAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;'T&gt;&gt;" Usage="iSupportsListingByTag.ListByTagAsync (tagName, tagValue, loadAllPages, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Fluent.Core.IPagedCollection&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tagName" Type="System.String" />
        <Parameter Name="tagValue" Type="System.String" />
        <Parameter Name="loadAllPages" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="tagName"><span data-ttu-id="ba910-106">Tagname als Schlüssel</span><span class="sxs-lookup"><span data-stu-id="ba910-106">tag's name as the key</span></span></param>
        <param name="tagValue"><span data-ttu-id="ba910-107">Tag Wert</span><span class="sxs-lookup"><span data-stu-id="ba910-107">tag's value</span></span></param>
        <param name="loadAllPages">To be added.</param>
        <param name="cancellationToken"><span data-ttu-id="ba910-108">das Abbruchtoken, das das cancellationToken</span><span class="sxs-lookup"><span data-stu-id="ba910-108">cancellationToken the cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="ba910-109">Listet alle Ressourcen mit dem angegebenen Tag.</span><span class="sxs-lookup"><span data-stu-id="ba910-109">Lists all the resources with the specified tag.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ba910-110">Eine "await" können Aufgabe für asynchrone Vorgang, der PagedCollection Ressourcen verfügt.</span><span class="sxs-lookup"><span data-stu-id="ba910-110">A await-able Task for asynchronous operation which will have PagedCollection of the resources.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>