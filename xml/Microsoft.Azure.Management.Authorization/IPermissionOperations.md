<Type Name="IPermissionOperations" FullName="Microsoft.Azure.Management.Authorization.IPermissionOperations">
  <TypeSignature Language="C#" Value="public interface IPermissionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPermissionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IPermissionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPermissionOperations" />
  <TypeSignature Language="F#" Value="type IPermissionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b0bb2-101">Rufen Sie oder Ressource Gruppenberechtigungen (http://TBD für Weitere Informationen siehe ab)</span><span class="sxs-lookup"><span data-stu-id="b0bb2-101">Get resource or resource group permissions  (see http://TBD for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync (string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceAsync(string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IPermissionOperations.ListForResourceAsync(System.String,Microsoft.Azure.ResourceIdentity,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceAsync : string * Microsoft.Azure.ResourceIdentity * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="iPermissionOperations.ListForResourceAsync (resourceGroupName, identity, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0bb2-102">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-102">The name of the resource group.</span></span> <span data-ttu-id="b0bb2-103">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-103">The name is case insensitive.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="b0bb2-104">Ressource</span><span class="sxs-lookup"><span data-stu-id="b0bb2-104">Resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0bb2-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0bb2-106">Ruft eine Ressource Berechtigungen ab.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-106">Gets a resource permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b0bb2-107">Berechtigungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-107">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync (string resourceGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt; ListForResourceGroupAsync(string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IPermissionOperations.ListForResourceGroupAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;" Usage="iPermissionOperations.ListForResourceGroupAsync (resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.PermissionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="b0bb2-108">Der Name der Ressourcengruppe, um die Berechtigungen für zu erhalten. Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-108">Name of the resource group to get the permissions for.The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="b0bb2-109">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-109">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b0bb2-110">Ruft eine Ressource Gruppenberechtigungen ab.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-110">Gets a resource group permissions.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b0bb2-111">Berechtigungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="b0bb2-111">Permissions information.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>