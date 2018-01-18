<Type Name="ManagementLocksOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ManagementLocksOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ManagementLocksOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ManagementLocksOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ManagementLocksOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bacf5-101">Erweiterungsmethoden für ManagementLocksOperations.</span><span class="sxs-lookup"><span data-stu-id="bacf5-101">Extension methods for ManagementLocksOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevel (operations, resourceGroupName, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-103">Der Name der Ressourcengruppe, zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-103">The name of the resource group to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-104">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-104">The lock name.</span></span> <span data-ttu-id="bacf5-105">Name für die Sperre kann maximal 260 Zeichen sein.</span><span class="sxs-lookup"><span data-stu-id="bacf5-105">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="bacf5-106">Darf keine &lt;, &gt; %, &amp;,:, \, ?, /, oder alle Steuerzeichen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-106">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-107">Die Parameter für den Management-Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-107">The management lock parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-108">Erstellt oder aktualisiert eine verwaltungssperre auf Gruppenebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-108">Creates or updates a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-109">Wenn Sie eine Sperre in einem übergeordneten Bereich anwenden, erben alle untergeordneten Ressourcen diese Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-109">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="bacf5-110">Um verwaltungssperren zu erstellen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-110">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-111">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-111">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtResourceGroupLevelAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-113">Der Name der Ressourcengruppe, zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-113">The name of the resource group to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-114">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-114">The lock name.</span></span> <span data-ttu-id="bacf5-115">Name für die Sperre kann maximal 260 Zeichen sein.</span><span class="sxs-lookup"><span data-stu-id="bacf5-115">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="bacf5-116">Darf keine &lt;, &gt; %, &amp;,:, \, ?, /, oder alle Steuerzeichen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-116">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-117">Die Parameter für den Management-Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-117">The management lock parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-119">Erstellt oder aktualisiert eine verwaltungssperre auf Gruppenebene Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-119">Creates or updates a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-120">Wenn Sie eine Sperre in einem übergeordneten Bereich anwenden, erben alle untergeordneten Ressourcen diese Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-120">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="bacf5-121">Um verwaltungssperren zu erstellen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-121">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-122">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-122">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-124">Der Name der Ressourcengruppe, die die Ressource enthält, zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-124">The name of the resource group containing the resource to lock.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-125">Der Namespace des Ressourcenanbieters der Ressource zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-125">The resource provider namespace of the resource to lock.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-126">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-126">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-127">Der Ressourcentyp der Ressource zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-127">The resource type of the resource to lock.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-128">Der Name der Ressource zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-128">The name of the resource to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-129">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-129">The name of lock.</span></span> <span data-ttu-id="bacf5-130">Name für die Sperre kann maximal 260 Zeichen sein.</span><span class="sxs-lookup"><span data-stu-id="bacf5-130">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="bacf5-131">Darf keine &lt;, &gt; %, &amp;,:, \, ?, /, oder alle Steuerzeichen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-131">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-132">Parameter zum Erstellen oder Aktualisieren einer verwaltungssperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-132">Parameters for creating or updating a  management lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-133">Erstellt oder aktualisiert eine verwaltungssperre auf Ressourcen oder einer beliebigen Ebene unterhalb der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-133">Creates or updates a management lock at the resource level or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-134">Wenn Sie eine Sperre in einem übergeordneten Bereich anwenden, erben alle untergeordneten Ressourcen diese Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-134">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="bacf5-135">Um verwaltungssperren zu erstellen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-135">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-136">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-136">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtResourceLevelAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-138">Der Name der Ressourcengruppe, die die Ressource enthält, zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-138">The name of the resource group containing the resource to lock.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-139">Der Namespace des Ressourcenanbieters der Ressource zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-139">The resource provider namespace of the resource to lock.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-140">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-140">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-141">Der Ressourcentyp der Ressource zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-141">The resource type of the resource to lock.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-142">Der Name der Ressource zu sperren.</span><span class="sxs-lookup"><span data-stu-id="bacf5-142">The name of the resource to lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-143">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-143">The name of lock.</span></span> <span data-ttu-id="bacf5-144">Name für die Sperre kann maximal 260 Zeichen sein.</span><span class="sxs-lookup"><span data-stu-id="bacf5-144">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="bacf5-145">Darf keine &lt;, &gt; %, &amp;,:, \, ?, /, oder alle Steuerzeichen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-145">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-146">Parameter zum Erstellen oder Aktualisieren einer verwaltungssperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-146">Parameters for creating or updating a  management lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-148">Erstellt oder aktualisiert eine verwaltungssperre auf Ressourcen oder einer beliebigen Ebene unterhalb der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-148">Creates or updates a management lock at the resource level or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-149">Wenn Sie eine Sperre in einem übergeordneten Bereich anwenden, erben alle untergeordneten Ressourcen diese Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-149">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="bacf5-150">Um verwaltungssperren zu erstellen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-150">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-151">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-151">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevel (operations, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-152">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-153">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-153">The name of lock.</span></span> <span data-ttu-id="bacf5-154">Name für die Sperre kann maximal 260 Zeichen sein.</span><span class="sxs-lookup"><span data-stu-id="bacf5-154">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="bacf5-155">Darf keine &lt;, &gt; %, &amp;,:, \, ?, /, oder alle Steuerzeichen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-155">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-156">Die Parameter für den Management-Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-156">The management lock parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-157">Erstellt oder aktualisiert eine verwaltungssperre auf Abonnementebene.</span><span class="sxs-lookup"><span data-stu-id="bacf5-157">Creates or updates a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-158">Wenn Sie eine Sperre in einem übergeordneten Bereich anwenden, erben alle untergeordneten Ressourcen diese Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-158">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="bacf5-159">Um verwaltungssperren zu erstellen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-159">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-160">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-160">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateAtSubscriptionLevelAsync (operations, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateAtSubscriptionLevelAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-161">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-162">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-162">The name of lock.</span></span> <span data-ttu-id="bacf5-163">Name für die Sperre kann maximal 260 Zeichen sein.</span><span class="sxs-lookup"><span data-stu-id="bacf5-163">The lock name can be a maximum of 260 characters.</span></span> <span data-ttu-id="bacf5-164">Darf keine &lt;, &gt; %, &amp;,:, \, ?, /, oder alle Steuerzeichen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-164">It cannot contain &lt;, &gt; %, &amp;, :, \, ?, /, or any control characters.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-165">Die Parameter für den Management-Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-165">The management lock parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-167">Erstellt oder aktualisiert eine verwaltungssperre auf Abonnementebene.</span><span class="sxs-lookup"><span data-stu-id="bacf5-167">Creates or updates a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-168">Wenn Sie eine Sperre in einem übergeordneten Bereich anwenden, erben alle untergeordneten Ressourcen diese Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-168">When you apply a lock at a parent scope, all child resources inherit the same lock.</span></span> <span data-ttu-id="bacf5-169">Um verwaltungssperren zu erstellen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-169">To create management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-170">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-170">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject CreateOrUpdateByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateByScope (operations As IManagementLocksOperations, scope As String, lockName As String, parameters As ManagementLockObject) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScope (operations, scope, lockName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-171">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="bacf5-172">Der Bereich für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-172">The scope for the lock.</span></span> <span data-ttu-id="bacf5-173">Bei der Angabe eines Bereichs für die Zuweisung "/ Subscriptions / {SubscriptionId}" für Abonnements verwendet werden, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für Ressourcengruppen, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} /providers/ {ResourceProviderNamespace} / {ParentResourcePathIfPresent} / {ResourceType} / {ResourceName}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-173">When providing a scope for the assignment, use '/subscriptions/{subscriptionId}' for subscriptions, '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}' for resource groups, and '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourceType}/{resourceName}' for resources.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-174">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-174">The name of lock.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-175">Erstellen Sie oder aktualisieren Sie Management-Sperre-Parameter.</span><span class="sxs-lookup"><span data-stu-id="bacf5-175">Create or update management lock parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-176">Erstellen oder Aktualisieren einer verwaltungssperre durch den Bereich.</span><span class="sxs-lookup"><span data-stu-id="bacf5-176">Create or update a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; CreateOrUpdateByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.CreateOrUpdateByScopeAsync (operations, scope, lockName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;CreateOrUpdateByScopeAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-177">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="bacf5-178">Der Bereich für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-178">The scope for the lock.</span></span> <span data-ttu-id="bacf5-179">Bei der Angabe eines Bereichs für die Zuweisung "/ Subscriptions / {SubscriptionId}" für Abonnements verwendet werden, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für Ressourcengruppen, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} /providers/ {ResourceProviderNamespace} / {ParentResourcePathIfPresent} / {ResourceType} / {ResourceName}" für Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-179">When providing a scope for the assignment, use '/subscriptions/{subscriptionId}' for subscriptions, '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}' for resource groups, and '/subscriptions/{subscriptionId}/resourcegroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{parentResourcePathIfPresent}/{resourceType}/{resourceName}' for resources.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-180">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-180">The name of lock.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bacf5-181">Erstellen Sie oder aktualisieren Sie Management-Sperre-Parameter.</span><span class="sxs-lookup"><span data-stu-id="bacf5-181">Create or update management lock parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-183">Erstellen oder Aktualisieren einer verwaltungssperre durch den Bereich.</span><span class="sxs-lookup"><span data-stu-id="bacf5-183">Create or update a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevel (operations, resourceGroupName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-185">Der Name der Ressourcengruppe, die die Sperre enthält.</span><span class="sxs-lookup"><span data-stu-id="bacf5-185">The name of the resource group containing the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-186">Der Name der Sperre zu löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-186">The name of lock to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-187">Löscht eine verwaltungssperre auf Gruppenebene Ressource an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-187">Deletes a management lock at the resource group level.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="bacf5-188">Um verwaltungssperren zu löschen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-188">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-189">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-189">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtResourceGroupLevelAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-191">Der Name der Ressourcengruppe, die die Sperre enthält.</span><span class="sxs-lookup"><span data-stu-id="bacf5-191">The name of the resource group containing the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-192">Der Name der Sperre zu löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-192">The name of lock to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-194">Löscht eine verwaltungssperre auf Gruppenebene Ressource an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-194">Deletes a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-195">Um verwaltungssperren zu löschen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-195">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-196">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-196">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-197">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-197">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-198">Der Name der Ressourcengruppe mit der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-198">The name of the resource group containing the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-199">Der Namespace des Ressourcenanbieters der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-199">The resource provider namespace of the resource with the lock to delete.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-200">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-200">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-201">Der Ressourcentyp der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-201">The resource type of the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-202">Der Name der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-202">The name of the resource with the lock to delete.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-203">Der Name der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-203">The name of the lock to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-204">Löscht die Management-Sperre für eine Ressource oder eine Ebene unter der Ressource an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-204">Deletes the management lock of a resource or any level below the resource.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="bacf5-205">Um verwaltungssperren zu löschen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-205">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-206">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-206">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtResourceLevelAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-208">Der Name der Ressourcengruppe mit der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-208">The name of the resource group containing the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-209">Der Namespace des Ressourcenanbieters der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-209">The resource provider namespace of the resource with the lock to delete.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-210">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-210">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-211">Der Ressourcentyp der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-211">The resource type of the resource with the lock to delete.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-212">Der Name der Ressource mit der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-212">The name of the resource with the lock to delete.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-213">Der Name der Sperre löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-213">The name of the lock to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-214">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-215">Löscht die Management-Sperre für eine Ressource oder eine Ebene unter der Ressource an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-215">Deletes the management lock of a resource or any level below the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-216">Um verwaltungssperren zu löschen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-216">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-217">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-217">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static void DeleteAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevel (operations, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-218">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-219">Der Name der Sperre zu löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-219">The name of lock to delete.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-220">Löscht die verwaltungssperre auf Abonnementebene.</span><span class="sxs-lookup"><span data-stu-id="bacf5-220">Deletes the management lock at the subscription level.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="bacf5-221">Um verwaltungssperren zu löschen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-221">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-222">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-222">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteAtSubscriptionLevelAsync (operations, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteAtSubscriptionLevelAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-223">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-224">Der Name der Sperre zu löschen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-224">The name of lock to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-226">Löscht die verwaltungssperre auf Abonnementebene.</span><span class="sxs-lookup"><span data-stu-id="bacf5-226">Deletes the management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="bacf5-227">Um verwaltungssperren zu löschen, benötigen Sie Zugriff auf Microsoft.Authorization/* oder Microsoft.Authorization/locks/* Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-227">To delete management locks, you must have access to Microsoft.Authorization/* or Microsoft.Authorization/locks/* actions.</span></span> <span data-ttu-id="bacf5-228">Unter den integrierten Rollen verfügen nur „Besitzer“ und „Benutzerzugriffsadministrator“ über diese Aktionen.</span><span class="sxs-lookup"><span data-stu-id="bacf5-228">Of the built-in roles, only Owner and User Access Administrator are granted those actions.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScope">
      <MemberSignature Language="C#" Value="public static void DeleteByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteByScope (operations As IManagementLocksOperations, scope As String, lockName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScope (operations, scope, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-229">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="bacf5-230">Der Bereich für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-230">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-231">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-231">The name of lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-232">Löschen einer verwaltungssperre durch den Bereich an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-232">Delete a management lock by scope.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.DeleteByScopeAsync (operations, scope, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;DeleteByScopeAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-233">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="bacf5-234">Der Bereich für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-234">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-235">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-235">The name of lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-236">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-237">Löschen einer verwaltungssperre durch den Bereich an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-237">Delete a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevel (operations, resourceGroupName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-238">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-239">Der Name der Ressourcengruppe gesperrt.</span><span class="sxs-lookup"><span data-stu-id="bacf5-239">The name of the locked resource group.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-240">Der Name der abzurufenden Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-240">The name of the lock to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-241">Ruft eine verwaltungssperre auf Gruppenebene Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-241">Gets a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceGroupLevelAsync (operations, resourceGroupName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtResourceGroupLevelAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-243">Der Name der Ressourcengruppe gesperrt.</span><span class="sxs-lookup"><span data-stu-id="bacf5-243">The name of the locked resource group.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-244">Der Name der abzurufenden Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-244">The name of the lock to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-245">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-245">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-246">Ruft eine verwaltungssperre auf Gruppenebene Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-246">Gets a management lock at the resource group level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-247">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-248">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bacf5-248">The name of the resource group.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-249">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="bacf5-249">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-250">Eine zusätzliche Path-Parameter, die in einigen Diensten, wie SQL-Datenbanken erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="bacf5-250">An extra path parameter needed in some services, like SQL Databases.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-251">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-251">The type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-252">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-252">The name of the resource.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-253">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-253">The name of lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-254">Abrufen der verwaltungssperre eine Ressource oder einer beliebigen Ebene unter der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-254">Get the management lock of a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtResourceLevelAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-255">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-256">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bacf5-256">The name of the resource group.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-257">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="bacf5-257">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-258">Eine zusätzliche Path-Parameter, die in einigen Diensten, wie SQL-Datenbanken erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="bacf5-258">An extra path parameter needed in some services, like SQL Databases.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-259">Der Typ der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-259">The type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-260">Der Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-260">The name of the resource.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-261">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-261">The name of lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-262">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-263">Abrufen der verwaltungssperre eine Ressource oder einer beliebigen Ebene unter der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-263">Get the management lock of a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAtSubscriptionLevel (operations As IManagementLocksOperations, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevel (operations, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-264">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-264">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-265">Der Name der abzurufenden Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-265">The name of the lock to get.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-266">Ruft eine verwaltungssperre auf Abonnementebene ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-266">Gets a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetAtSubscriptionLevelAsync (operations, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetAtSubscriptionLevelAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-267">The operations group for this extension method.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-268">Der Name der abzurufenden Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-268">The name of the lock to get.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-269">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-270">Ruft eine verwaltungssperre auf Abonnementebene ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-270">Gets a management lock at the subscription level.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScope">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetByScope (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject GetByScope(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScope(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetByScope (operations As IManagementLocksOperations, scope As String, lockName As String) As ManagementLockObject" />
      <MemberSignature Language="F#" Value="static member GetByScope : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScope (operations, scope, lockName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-271">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-271">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="bacf5-272">Der Bereich für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-272">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-273">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-273">The name of lock.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-274">Abrufen einer verwaltungssperre durch den Bereich an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-274">Get a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByScopeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetByScopeAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; GetByScopeAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string scope, string lockName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScopeAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByScopeAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.GetByScopeAsync (operations, scope, lockName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;GetByScopeAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="lockName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-275">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-275">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="bacf5-276">Der Bereich für die Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-276">The scope for the lock.</span></span>
            </param>
        <param name="lockName">
            <span data-ttu-id="bacf5-277">Der Name der Sperre.</span><span class="sxs-lookup"><span data-stu-id="bacf5-277">The name of lock.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-278">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-278">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-279">Abrufen einer verwaltungssperre durch den Bereich an.</span><span class="sxs-lookup"><span data-stu-id="bacf5-279">Get a management lock by scope.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceGroupLevel (operations As IManagementLocksOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevel (operations, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-280">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-280">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-281">Der Name der Ressourcengruppe, enthält die Sperren zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="bacf5-281">The name of the resource group containing the locks to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bacf5-282">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-282">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-283">Ruft alle verwaltungssperren für eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bacf5-283">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceGroupLevelAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-284">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-284">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-285">Der Name der Ressourcengruppe, enthält die Sperren zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="bacf5-285">The name of the resource group containing the locks to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bacf5-286">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-286">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-287">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-287">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-288">Ruft alle verwaltungssperren für eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bacf5-288">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceGroupLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceGroupLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-289">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-289">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bacf5-290">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bacf5-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-291">Ruft alle verwaltungssperren für eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bacf5-291">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceGroupLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceGroupLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceGroupLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceGroupLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceGroupLevelNextAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-292">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-292">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bacf5-293">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bacf5-293">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-294">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-294">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-295">Ruft alle verwaltungssperren für eine Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bacf5-295">Gets all the management locks for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceLevel (operations As IManagementLocksOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevel (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-296">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-297">Der Name der Ressourcengruppe, die gesperrte Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="bacf5-297">The name of the resource group containing the locked resource.</span></span> <span data-ttu-id="bacf5-298">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-298">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-299">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="bacf5-299">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-300">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-300">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-301">Der Ressourcentyp der gesperrten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-301">The resource type of the locked resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-302">Der Name der gesperrten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-302">The name of the locked resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bacf5-303">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-303">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-304">Ruft alle verwaltungssperren für eine Ressource oder einer beliebigen Ebene unter der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-304">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * string * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceLevelAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-305">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-305">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bacf5-306">Der Name der Ressourcengruppe, die gesperrte Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="bacf5-306">The name of the resource group containing the locked resource.</span></span> <span data-ttu-id="bacf5-307">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-307">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="bacf5-308">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="bacf5-308">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="bacf5-309">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-309">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="bacf5-310">Der Ressourcentyp der gesperrten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-310">The resource type of the locked resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="bacf5-311">Der Name der gesperrten Ressource.</span><span class="sxs-lookup"><span data-stu-id="bacf5-311">The name of the locked resource.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bacf5-312">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-312">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-313">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-314">Ruft alle verwaltungssperren für eine Ressource oder einer beliebigen Ebene unter der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-314">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtResourceLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtResourceLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-315">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-315">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bacf5-316">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bacf5-316">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-317">Ruft alle verwaltungssperren für eine Ressource oder einer beliebigen Ebene unter der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-317">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtResourceLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtResourceLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtResourceLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtResourceLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtResourceLevelNextAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-318">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-318">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bacf5-319">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bacf5-319">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-320">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-320">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-321">Ruft alle verwaltungssperren für eine Ressource oder einer beliebigen Ebene unter der Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-321">Gets all the management locks for a resource or any level below resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevel">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevel (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevel(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevel(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionLevel (operations As IManagementLocksOperations, Optional odataQuery As ODataQuery(Of ManagementLockObject) = null) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevel : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevel (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-322">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-322">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bacf5-323">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-323">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-324">Ruft alle verwaltungssperren für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-324">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtSubscriptionLevelAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-325">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-325">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="bacf5-326">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="bacf5-326">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-327">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-327">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-328">Ruft alle verwaltungssperren für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-328">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevelNext (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt; ListAtSubscriptionLevelNext(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNext(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAtSubscriptionLevelNext (operations As IManagementLocksOperations, nextPageLink As String) As IPage(Of ManagementLockObject)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelNext : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-329">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-329">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bacf5-330">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bacf5-330">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-331">Ruft alle verwaltungssperren für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-331">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAtSubscriptionLevelNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelNextAsync (this Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt; ListAtSubscriptionLevelNextAsync(class Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNextAsync(Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAtSubscriptionLevelNextAsync : Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions.ListAtSubscriptionLevelNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ManagementLocksOperationsExtensions/&lt;ListAtSubscriptionLevelNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.ManagementLockObject&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IManagementLocksOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bacf5-332">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bacf5-332">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bacf5-333">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bacf5-333">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bacf5-334">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bacf5-334">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bacf5-335">Ruft alle verwaltungssperren für ein Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="bacf5-335">Gets all the management locks for a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>