<Type Name="IResourceGroups" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups">
  <TypeSignature Language="C#" Value="public interface IResourceGroups : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroup.Definition.IBlank&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IResourceGroups implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroup.Definition.IBlank&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag`1&lt;class Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups" />
  <TypeSignature Language="VB.NET" Value="Public Interface IResourceGroups&#xA;Implements ISupportsBatchCreation(Of IResourceGroup), ISupportsBeginDeletingByName, ISupportsCreating(Of IBlank), ISupportsDeletingByName, ISupportsGettingByName(Of IResourceGroup), ISupportsListing(Of IResourceGroup), ISupportsListingByTag(Of IResourceGroup)" />
  <TypeSignature Language="F#" Value="type IResourceGroups = interface&#xA;    interface ISupportsListing&lt;IResourceGroup&gt;&#xA;    interface ISupportsListingByTag&lt;IResourceGroup&gt;&#xA;    interface ISupportsGettingByName&lt;IResourceGroup&gt;&#xA;    interface ISupportsCreating&lt;IBlank&gt;&#xA;    interface ISupportsDeletingByName&#xA;    interface ISupportsBeginDeletingByName&#xA;    interface ISupportsBatchCreation&lt;IResourceGroup&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBatchCreation&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsCreating&lt;Microsoft.Azure.Management.ResourceManager.Fluent.ResourceGroup.Definition.IBlank&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByName</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByName&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListingByTag&lt;Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroup&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f5704-101">Einstiegspunkt für einen Resource-Group-Verwaltungs-API.</span><span class="sxs-lookup"><span data-stu-id="f5704-101">Entry point to resource group management API.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public bool CheckExistence (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CheckExistence(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups.CheckExistence(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckExistence (name As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member CheckExistence : string -&gt; bool" Usage="iResourceGroups.CheckExistence name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use Contain() instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f5704-102">Der Name der Ressourcengruppe, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f5704-102">name The name of the resource group to check.</span></span> <span data-ttu-id="f5704-103">Der Name ist Groß-/Kleinschreibung beachten</span><span class="sxs-lookup"><span data-stu-id="f5704-103">The name is case insensitive</span></span></param>
        <summary>
            <span data-ttu-id="f5704-104">Überprüft, ob eine Ressourcengruppe vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f5704-104">Checks whether resource group exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f5704-105">"true", wenn die Ressourcengruppe vorhanden ist; "false" andernfalls</span><span class="sxs-lookup"><span data-stu-id="f5704-105">true if the resource group exists; false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups.CheckExistenceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CheckExistenceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iResourceGroups.CheckExistenceAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("User ContainAsync() instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f5704-106">Der Name der Ressourcengruppe, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="f5704-106">name The name of the resource group to check.</span></span> <span data-ttu-id="f5704-107">Der Name ist Groß-/Kleinschreibung beachten</span><span class="sxs-lookup"><span data-stu-id="f5704-107">The name is case insensitive</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="f5704-108">Überprüft, ob eine Ressourcengruppe vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="f5704-108">Checks whether resource group exists.</span></span>
            </summary>
        <returns><span data-ttu-id="f5704-109">"true", wenn die Ressourcengruppe vorhanden ist; "false" andernfalls</span><span class="sxs-lookup"><span data-stu-id="f5704-109">true if the resource group exists; false otherwise</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Contain">
      <MemberSignature Language="C#" Value="public bool Contain (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Contain(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups.Contain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Contain (name As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member Contain : string -&gt; bool" Usage="iResourceGroups.Contain name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; ContainAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ContainAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.IResourceGroups.ContainAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContainAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iResourceGroups.ContainAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>