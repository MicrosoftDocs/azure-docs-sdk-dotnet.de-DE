<Type Name="IRoleDefinitionOperations" FullName="Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations">
  <TypeSignature Language="C#" Value="public interface IRoleDefinitionOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRoleDefinitionOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRoleDefinitionOperations" />
  <TypeSignature Language="F#" Value="type IRoleDefinitionOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f7b62-101">TBD (http://TBD für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="f7b62-101">TBD  (see http://TBD for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync (Guid roleDefinitionId, string scope, Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt; CreateOrUpdateAsync(valuetype System.Guid roleDefinitionId, string scope, class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.CreateOrUpdateAsync(System.Guid,System.String,Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : Guid * string * Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;" Usage="iRoleDefinitionOperations.CreateOrUpdateAsync (roleDefinitionId, scope, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleDefinitionCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            <span data-ttu-id="f7b62-102">Rollendefinitions-Id.</span><span class="sxs-lookup"><span data-stu-id="f7b62-102">Role definition id.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="f7b62-103">Umfang</span><span class="sxs-lookup"><span data-stu-id="f7b62-103">Scope</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7b62-104">Rollendefinition.</span><span class="sxs-lookup"><span data-stu-id="f7b62-104">Role definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b62-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7b62-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b62-106">Erstellt oder aktualisiert eine Rollendefinition.</span><span class="sxs-lookup"><span data-stu-id="f7b62-106">Creates or updates a role definition.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7b62-107">Rollendefinition erstellen oder Aktualisieren von Ergebnis des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="f7b62-107">Role definition create or update operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync (Guid roleDefinitionId, string scope, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt; DeleteAsync(valuetype System.Guid roleDefinitionId, string scope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.DeleteAsync(System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;" Usage="iRoleDefinitionOperations.DeleteAsync (roleDefinitionId, scope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            <span data-ttu-id="f7b62-108">Rollendefinitions-Id.</span><span class="sxs-lookup"><span data-stu-id="f7b62-108">Role definition id.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="f7b62-109">Umfang</span><span class="sxs-lookup"><span data-stu-id="f7b62-109">Scope</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b62-110">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7b62-110">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b62-111">Löscht die Rollendefinition.</span><span class="sxs-lookup"><span data-stu-id="f7b62-111">Deletes the role definition.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7b62-112">Ergebnis des Vorgangs zum Löschen der Rollendefinition.</span><span class="sxs-lookup"><span data-stu-id="f7b62-112">Role definition delete operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync (Guid roleDefinitionId, string scope, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetAsync(valuetype System.Guid roleDefinitionId, string scope, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.GetAsync(System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="iRoleDefinitionOperations.GetAsync (roleDefinitionId, scope, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.Guid" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            <span data-ttu-id="f7b62-113">Rollendefinition Id</span><span class="sxs-lookup"><span data-stu-id="f7b62-113">Role definition Id</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="f7b62-114">Umfang</span><span class="sxs-lookup"><span data-stu-id="f7b62-114">Scope</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b62-115">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7b62-115">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b62-116">Abrufen von Rollendefinition anhand des Namens (GUID).</span><span class="sxs-lookup"><span data-stu-id="f7b62-116">Get role definition by name (GUID).</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7b62-117">Rollendefinition vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="f7b62-117">Role definition get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync (string roleDefinitionId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt; GetByIdAsync(string roleDefinitionId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;" Usage="iRoleDefinitionOperations.GetByIdAsync (roleDefinitionId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleDefinitionId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleDefinitionId">
            <span data-ttu-id="f7b62-118">Vollqualifizierte Rollendefinition Id</span><span class="sxs-lookup"><span data-stu-id="f7b62-118">Fully qualified role definition Id</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b62-119">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7b62-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b62-120">Abrufen von Rollendefinition anhand des Namens (GUID).</span><span class="sxs-lookup"><span data-stu-id="f7b62-120">Get role definition by name (GUID).</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7b62-121">Rollendefinition vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="f7b62-121">Role definition get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync (string scope, Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt; ListAsync(string scope, class Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleDefinitionOperations.ListAsync(System.String,Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;" Usage="iRoleDefinitionOperations.ListAsync (scope, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleDefinitionListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.ListDefinitionFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="f7b62-122">Umfang</span><span class="sxs-lookup"><span data-stu-id="f7b62-122">Scope</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f7b62-123">Rolle Definitionen filtert.</span><span class="sxs-lookup"><span data-stu-id="f7b62-123">List role definitions filters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f7b62-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f7b62-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f7b62-125">Rufen Sie aller Rollendefinitionen ab, die im Gültigkeitsbereich und höher verfügbar sind.</span><span class="sxs-lookup"><span data-stu-id="f7b62-125">Get all role definitions that are applicable at scope and above.</span></span>
            <span data-ttu-id="f7b62-126">Mit AtScopeAndBelow Filter können Sie die um unten angegebenen Bereich zu suchen.</span><span class="sxs-lookup"><span data-stu-id="f7b62-126">Use atScopeAndBelow filter to search below the given scope as well</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f7b62-127">Rolle "" Definition Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="f7b62-127">Role definition list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>