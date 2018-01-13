<Type Name="IRoleAssignmentOperations" FullName="Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations">
  <TypeSignature Language="C#" Value="public interface IRoleAssignmentOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRoleAssignmentOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRoleAssignmentOperations" />
  <TypeSignature Language="F#" Value="type IRoleAssignmentOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3dbbc-101">TBD (http://TBD für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="3dbbc-101">TBD  (see http://TBD for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateAsync (string scope, Guid roleAssignmentName, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateAsync(string scope, valuetype System.Guid roleAssignmentName, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.CreateAsync(System.String,System.Guid,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * Guid * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;" Usage="iRoleAssignmentOperations.CreateAsync (scope, roleAssignmentName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="3dbbc-102">Bereich.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-102">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="3dbbc-103">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-103">Role assignment name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3dbbc-104">Rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-104">Role assignment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-106">Rollenzuweisung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-106">Create role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-107">Zuweisungen Erstellung-rollenergebnissen</span><span class="sxs-lookup"><span data-stu-id="3dbbc-107">Role assignments creation results</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateByIdAsync (string roleAssignmentId, Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt; CreateByIdAsync(string roleAssignmentId, class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.CreateByIdAsync(System.String,Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateByIdAsync : string * Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;" Usage="iRoleAssignmentOperations.CreateByIdAsync (roleAssignmentId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.Models.RoleAssignmentCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleAssignmentId">
            <span data-ttu-id="3dbbc-108">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="3dbbc-108">Role assignment Id</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3dbbc-109">Rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-109">Role assignment.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-110">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-110">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-111">Erstellen Sie die rollenzuweisung nach ID auf.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-111">Create role assignment by Id.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-112">Zuweisungen Erstellung-rollenergebnissen</span><span class="sxs-lookup"><span data-stu-id="3dbbc-112">Role assignments creation results</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteAsync (string scope, Guid roleAssignmentName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteAsync(string scope, valuetype System.Guid roleAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.DeleteAsync(System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;" Usage="iRoleAssignmentOperations.DeleteAsync (scope, roleAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="3dbbc-113">Bereich.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-113">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="3dbbc-114">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-114">Role assignment name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-115">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-115">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-116">Löschen Sie rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-116">Delete role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-117">Löschen von rollenzuweisungen Ergebnis</span><span class="sxs-lookup"><span data-stu-id="3dbbc-117">Role assignments delete result</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteByIdAsync (string roleAssignmentId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt; DeleteByIdAsync(string roleAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.DeleteByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;" Usage="iRoleAssignmentOperations.DeleteByIdAsync (roleAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentDeleteResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleAssignmentId">
            <span data-ttu-id="3dbbc-118">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="3dbbc-118">Role assignment Id</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-119">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-120">Löschen Sie rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-120">Delete role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-121">Löschen von rollenzuweisungen Ergebnis</span><span class="sxs-lookup"><span data-stu-id="3dbbc-121">Role assignments delete result</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetAsync (string scope, Guid roleAssignmentName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetAsync(string scope, valuetype System.Guid roleAssignmentName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.GetAsync(System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;" Usage="iRoleAssignmentOperations.GetAsync (scope, roleAssignmentName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="roleAssignmentName" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="3dbbc-122">Bereich.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-122">Scope.</span></span>
            </param>
        <param name="roleAssignmentName">
            <span data-ttu-id="3dbbc-123">Name der Rolle Zuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-123">Role assignment name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-125">Rufen Sie einzelne rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-125">Get single role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-126">Rollenzuweisung vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-126">Role assignment get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetByIdAsync (string roleAssignmentId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt; GetByIdAsync(string roleAssignmentId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;" Usage="iRoleAssignmentOperations.GetByIdAsync (roleAssignmentId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentGetResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="roleAssignmentId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="roleAssignmentId">
            <span data-ttu-id="3dbbc-127">Rollenzuweisung Id</span><span class="sxs-lookup"><span data-stu-id="3dbbc-127">Role assignment Id</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-128">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-128">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-129">Rufen Sie einzelne rollenzuweisung.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-129">Get single role assignment.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-130">Rollenzuweisung vorgangsergebnis zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-130">Role assignment get operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListAsync (Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListAsync(class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListAsync(Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="3dbbc-131">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-131">List operation filters.</span></span> <span data-ttu-id="3dbbc-132">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-132">If null will return all role assignments at, above or below the subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-133">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-133">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-134">Ruft die rollenzuweisungen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-134">Gets role assignments of the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-135">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-135">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceAsync (string resourceGroupName, Microsoft.Azure.ResourceIdentity identity, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceAsync(string resourceGroupName, class Microsoft.Azure.ResourceIdentity identity, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceAsync(System.String,Microsoft.Azure.ResourceIdentity,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceAsync : string * Microsoft.Azure.ResourceIdentity * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceAsync (resourceGroupName, identity, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="identity" Type="Microsoft.Azure.ResourceIdentity" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3dbbc-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-136">The name of the resource group.</span></span>
            </param>
        <param name="identity">
            <span data-ttu-id="3dbbc-137">Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-137">Resource identity.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3dbbc-138">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-138">List operation filters.</span></span> <span data-ttu-id="3dbbc-139">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressource zurück.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-139">If null will return all role assignments at, above or below the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-140">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-141">Ruft die rollenzuweisungen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-141">Gets role assignments of the resource.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-142">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-142">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupAsync (string resourceGroupName, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupAsync(string resourceGroupName, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceGroupAsync(System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupAsync : string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceGroupAsync (resourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3dbbc-143">Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-143">Resource group name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3dbbc-144">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-144">List operation filters.</span></span> <span data-ttu-id="3dbbc-145">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb der Ressourcengruppe zurück.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-145">If null will return all role assignments at, above or below the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-146">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-147">Ruft die rollenzuweisungen der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-147">Gets role assignments of the resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-148">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-148">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceGroupNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceGroupNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceGroupNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceGroupNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="3dbbc-149">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-149">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-150">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-150">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-151">Ruft die rollenzuweisungen der Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-151">Gets role assignments of the resource group.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-152">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-152">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForResourceNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForResourceNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForResourceNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForResourceNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForResourceNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="3dbbc-153">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-153">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-154">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-154">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-155">Ruft die rollenzuweisungen der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-155">Gets role assignments of the resource.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-156">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-156">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeAsync (string scope, Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeAsync(string scope, class Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForScopeAsync(System.String,Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForScopeAsync : string * Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForScopeAsync (scope, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Authorization.ListAssignmentsFilterParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="scope">
            <span data-ttu-id="3dbbc-157">Bereich.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-157">Scope.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3dbbc-158">Vorgang filtert.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-158">List operation filters.</span></span> <span data-ttu-id="3dbbc-159">Wenn der Wert null gibt alle rollenzuweisungen oberhalb oder unterhalb des Abonnements zurück.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-159">If null will return all role assignments at, above or below the subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-160">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-160">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-161">Ruft die rollenzuweisungen des Bereichs ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-161">Gets role assignments of the scope.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-162">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-162">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListForScopeNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListForScopeNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListForScopeNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListForScopeNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListForScopeNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="3dbbc-163">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-163">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-164">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-164">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-165">Ruft die rollenzuweisungen des Bereichs ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-165">Gets role assignments of the scope.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-166">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-166">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Authorization.IRoleAssignmentOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;" Usage="iRoleAssignmentOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Authorization</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Authorization.Models.RoleAssignmentListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="3dbbc-167">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-167">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3dbbc-168">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-168">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3dbbc-169">Ruft die rollenzuweisungen des Abonnements ab.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-169">Gets role assignments of the subscription.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3dbbc-170">Rolle Zuweisung Liste vorgangsergebnis.</span><span class="sxs-lookup"><span data-stu-id="3dbbc-170">Role assignment list operation result.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>