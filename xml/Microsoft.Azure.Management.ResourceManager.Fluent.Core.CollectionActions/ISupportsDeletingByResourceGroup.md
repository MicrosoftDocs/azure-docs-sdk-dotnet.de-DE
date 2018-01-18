<Type Name="ISupportsDeletingByResourceGroup" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByResourceGroup">
  <TypeSignature Language="C#" Value="public interface ISupportsDeletingByResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsDeletingByResourceGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByResourceGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsDeletingByResourceGroup" />
  <TypeSignature Language="F#" Value="type ISupportsDeletingByResourceGroup = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d7e11-101">Bietet Zugriff auf die beim Löschen einer Ressource von Azure, die durch den Namen und die Ressourcengruppe identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="d7e11-101">Provides access to deleting a resource from Azure, identifying it by its name and its resource group.</span></span>
            
            <span data-ttu-id="d7e11-102">(Hinweis: Diese Schnittstelle keine Implementierung durch Benutzercode vorgesehen ist)</span><span class="sxs-lookup"><span data-stu-id="d7e11-102">(Note: this interface is not intended to be implemented by user code)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteByResourceGroup">
      <MemberSignature Language="C#" Value="public void DeleteByResourceGroup (string resourceGroupName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void DeleteByResourceGroup(string resourceGroupName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByResourceGroup.DeleteByResourceGroup(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteByResourceGroup (resourceGroupName As String, name As String)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByResourceGroup : string * string -&gt; unit" Usage="iSupportsDeletingByResourceGroup.DeleteByResourceGroup (resourceGroupName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="d7e11-103">Die Gruppe der Ressource ist Teil des</span><span class="sxs-lookup"><span data-stu-id="d7e11-103">the group the resource is part of</span></span></param>
        <param name="name"><span data-ttu-id="d7e11-104">Der Name der Ressource</span><span class="sxs-lookup"><span data-stu-id="d7e11-104">the name of the resource</span></span></param>
        <summary>
            <span data-ttu-id="d7e11-105">Löscht eine Ressource von Azure, die durch den Namen und die Ressourcengruppe identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="d7e11-105">Deletes a resource from Azure, identifying it by its name and its resource group.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteByResourceGroupAsync (string resourceGroupName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteByResourceGroupAsync(string resourceGroupName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsDeletingByResourceGroup.DeleteByResourceGroupAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByResourceGroupAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSupportsDeletingByResourceGroup.DeleteByResourceGroupAsync (resourceGroupName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName"><span data-ttu-id="d7e11-106">Die Gruppe der Ressource ist Teil des</span><span class="sxs-lookup"><span data-stu-id="d7e11-106">the group the resource is part of</span></span></param>
        <param name="name"><span data-ttu-id="d7e11-107">Der Name der Ressource</span><span class="sxs-lookup"><span data-stu-id="d7e11-107">the name of the resource</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="d7e11-108">das Abbruchtoken, das das cancellationToken</span><span class="sxs-lookup"><span data-stu-id="d7e11-108">cancellationToken the cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="d7e11-109">Löscht eine Ressource von Azure, die durch den Namen und die Ressourcengruppe identifiziert wird.</span><span class="sxs-lookup"><span data-stu-id="d7e11-109">Deletes a resource from Azure, identifying it by its name and its resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>