<Type Name="ISupportsGettingByResourceGroup&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsGettingByResourceGroup&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsGettingByResourceGroup`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsGettingByResourceGroup(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsGettingByResourceGroup&lt;'T&gt; = interface" />
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
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetByResourceGroup">
      <MemberSignature Language="C#" Value="public T GetByResourceGroup (string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByResourceGroup(string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup`1.GetByResourceGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByResourceGroup (resourceGroupName As String, name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByResourceGroup : string * string -&gt; 'T" Usage="iSupportsGettingByResourceGroup.GetByResourceGroup (resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="ac821-101">der Name der Ressourcengruppe der Ressource wird</span><span class="sxs-lookup"><span data-stu-id="ac821-101">the name of the resource group the resource is in</span></span></param>
        <param name="name"><span data-ttu-id="ac821-102">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ac821-102">the name of the resource.</span></span> <span data-ttu-id="ac821-103">(Beachten Sie, dass dies nicht die ID ist)</span><span class="sxs-lookup"><span data-stu-id="ac821-103">(Note, this is not the ID)</span></span></param>
        <summary>
            <span data-ttu-id="ac821-104">Ruft die Informationen zu einer Ressource von Azure basierend auf den Namen der Ressource und der Name der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ac821-104">Gets the information about a resource from Azure based on the resource name and the name of its resource group.</span></span>
            </summary>
        <returns><span data-ttu-id="ac821-105">eine unveränderliche Darstellung der Ressource</span><span class="sxs-lookup"><span data-stu-id="ac821-105">an immutable representation of the resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByResourceGroupAsync (string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByResourceGroupAsync(string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByResourceGroup`1.GetByResourceGroupAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByResourceGroupAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iSupportsGettingByResourceGroup.GetByResourceGroupAsync (resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="ac821-106">der Name der Ressourcengruppe der Ressource wird</span><span class="sxs-lookup"><span data-stu-id="ac821-106">the name of the resource group the resource is in</span></span></param>
        <param name="name"><span data-ttu-id="ac821-107">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ac821-107">the name of the resource.</span></span> <span data-ttu-id="ac821-108">(Beachten Sie, dass dies nicht die ID ist)</span><span class="sxs-lookup"><span data-stu-id="ac821-108">(Note, this is not the ID)</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ac821-109">das Abbruchtoken, das</span><span class="sxs-lookup"><span data-stu-id="ac821-109">the cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="ac821-110">Ruft die Informationen zu einer Ressource von Azure basierend auf den Namen der Ressource und der Name der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="ac821-110">Gets the information about a resource from Azure based on the resource name and the name of its resource group.</span></span>
            </summary>
        <returns><span data-ttu-id="ac821-111">eine unveränderliche Darstellung der Ressource</span><span class="sxs-lookup"><span data-stu-id="ac821-111">an immutable representation of the resource</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>