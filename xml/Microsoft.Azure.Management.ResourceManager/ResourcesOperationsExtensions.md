<Type Name="ResourcesOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ResourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ResourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ResourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ResourcesOperationsExtensions = class" />
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
            <span data-ttu-id="6c1bc-101">Erweiterungsmethoden für ResourcesOperations.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-101">Extension methods for ResourcesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-103">Der Name der Ressourcengruppe für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-103">The name of the resource group for the resource.</span></span> <span data-ttu-id="6c1bc-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-104">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-105">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-105">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-106">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-106">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-107">Der Ressourcentyp der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-107">The resource type of the resource to create.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-108">Der Name der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-108">The name of the resource to create.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-109">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-109">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-110">Parameter zum Erstellen oder Aktualisieren der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-110">Parameters for creating or updating the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-111">Erstellt eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-111">Creates a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-112">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-113">Der Name der Ressourcengruppe für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-113">The name of the resource group for the resource.</span></span> <span data-ttu-id="6c1bc-114">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-114">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-115">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-115">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-116">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-116">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-117">Der Ressourcentyp der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-117">The resource type of the resource to create.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-118">Der Name der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-118">The name of the resource to create.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-119">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-119">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-120">Parameter zum Erstellen oder Aktualisieren der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-120">Parameters for creating or updating the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-122">Erstellt eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-122">Creates a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdateById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource BeginCreateOrUpdateById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateById (operations As IResourcesOperations, resourceId As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateById (operations, resourceId, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-124">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-124">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-125">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-125">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-126">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-126">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-127">Erstellen oder Aktualisieren von Ressourcenparametern.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-127">Create or update resource parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-128">Erstellen Sie eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-128">Create a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; BeginCreateOrUpdateByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginCreateOrUpdateByIdAsync (operations, resourceId, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginCreateOrUpdateByIdAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-130">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-130">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-131">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-131">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-132">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-132">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-133">Erstellen oder Aktualisieren von Ressourcenparametern.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-133">Create or update resource parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-135">Erstellen Sie eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-135">Create a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDelete (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-137">Der Name der Ressourcengruppe, die die zu löschende Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-137">The name of the resource group that contains the resource to delete.</span></span> <span data-ttu-id="6c1bc-138">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-138">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-139">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-139">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-140">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-140">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-141">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-141">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-142">Der Name der Ressource löschen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-142">The name of the resource to delete.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-143">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-143">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-144">Löscht eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-144">Deletes a resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-146">Der Name der Ressourcengruppe, die die zu löschende Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-146">The name of the resource group that contains the resource to delete.</span></span> <span data-ttu-id="6c1bc-147">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-147">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-148">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-148">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-149">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-149">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-150">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-150">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-151">Der Name der Ressource löschen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-151">The name of the resource to delete.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-152">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-152">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-154">Löscht eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-154">Deletes a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteById">
      <MemberSignature Language="C#" Value="public static void BeginDeleteById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDeleteById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDeleteById (operations As IResourcesOperations, resourceId As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-156">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-156">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-157">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-157">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-158">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-158">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-159">Löscht eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-159">Deletes a resource by ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginDeleteByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginDeleteByIdAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-161">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-161">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-162">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-162">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-163">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-163">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-165">Löscht eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-165">Deletes a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginMoveResources">
      <MemberSignature Language="C#" Value="public static void BeginMoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginMoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginMoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member BeginMoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-166">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-167">Der Name der Ressourcengruppe, die die Ressourcen enthält, verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-167">The name of the resource group containing the resources to move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-168">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-168">Parameters for moving resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-169">Verschiebt Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-169">Moves resources from one resource group to another resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="6c1bc-170">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-170">The resources to move must be in the same source resource group.</span></span> <span data-ttu-id="6c1bc-171">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-171">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-172">Beim Verschieben von Ressourcen sind die Source-Gruppe und die Zielgruppe für die Dauer des Vorgangs gesperrt.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-172">When moving resources, both the source group and the target group are locked for the duration of the operation.</span></span> <span data-ttu-id="6c1bc-173">Schreib- und Löschvorgänge in den Gruppen werden bis zum Abschluss der Verschiebung blockiert.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-173">Write and delete operations are blocked on the groups until the move completes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginMoveResourcesAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-174">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-175">Der Name der Ressourcengruppe, die die Ressourcen enthält, verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-175">The name of the resource group containing the resources to move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-176">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-176">Parameters for moving resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-178">Verschiebt Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-178">Moves resources from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6c1bc-179">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-179">The resources to move must be in the same source resource group.</span></span> <span data-ttu-id="6c1bc-180">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-180">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-181">Beim Verschieben von Ressourcen sind die Source-Gruppe und die Zielgruppe für die Dauer des Vorgangs gesperrt.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-181">When moving resources, both the source group and the target group are locked for the duration of the operation.</span></span> <span data-ttu-id="6c1bc-182">Schreib- und Löschvorgänge in den Gruppen werden bis zum Abschluss der Verschiebung blockiert.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-182">Write and delete operations are blocked on the groups until the move completes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginValidateMoveResources">
      <MemberSignature Language="C#" Value="public static void BeginValidateMoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginValidateMoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginValidateMoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member BeginValidateMoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-183">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-184">Der Name der Ressourcengruppe, die die Ressourcen enthalten, zur Überprüfung für verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-184">The name of the resource group containing the resources to validate for move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-185">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-185">Parameters for moving resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-186">Überprüft, ob Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-186">Validates whether resources can be moved from one resource group to another resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="6c1bc-187">Dieser Vorgang wird überprüft, ob die angegebenen Ressourcen zum Ziel verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-187">This operation checks whether the specified resources can be moved to the target.</span></span> <span data-ttu-id="6c1bc-188">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-188">The resources to move must be in the same source resource group.</span></span>
            <span data-ttu-id="6c1bc-189">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-189">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-190">Wenn die Überprüfung erfolgreich ist, wird der HTTP-Antwortcode 204 (kein Inhalt) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-190">If validation succeeds, it returns HTTP response code 204 (no content).</span></span> <span data-ttu-id="6c1bc-191">Wenn die Validierung fehlschlägt, wird der HTTP-Antwortcode 409 (Konflikt) mit einer Fehlermeldung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-191">If validation fails, it returns HTTP response code 409 (Conflict) with an error message.</span></span>
            <span data-ttu-id="6c1bc-192">Rufen Sie die URL im Location-Header-Wert, um das Ergebnis des Vorgangs langer überprüft.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-192">Retrieve the URL in the Location header value to check the result of the long-running operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginValidateMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginValidateMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginValidateMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginValidateMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.BeginValidateMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;BeginValidateMoveResourcesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-193">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-194">Der Name der Ressourcengruppe, die die Ressourcen enthalten, zur Überprüfung für verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-194">The name of the resource group containing the resources to validate for move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-195">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-195">Parameters for moving resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-197">Überprüft, ob Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-197">Validates whether resources can be moved from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6c1bc-198">Dieser Vorgang wird überprüft, ob die angegebenen Ressourcen zum Ziel verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-198">This operation checks whether the specified resources can be moved to the target.</span></span> <span data-ttu-id="6c1bc-199">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-199">The resources to move must be in the same source resource group.</span></span>
            <span data-ttu-id="6c1bc-200">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-200">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-201">Wenn die Überprüfung erfolgreich ist, wird der HTTP-Antwortcode 204 (kein Inhalt) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-201">If validation succeeds, it returns HTTP response code 204 (no content).</span></span> <span data-ttu-id="6c1bc-202">Wenn die Validierung fehlschlägt, wird der HTTP-Antwortcode 409 (Konflikt) mit einer Fehlermeldung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-202">If validation fails, it returns HTTP response code 409 (Conflict) with an error message.</span></span>
            <span data-ttu-id="6c1bc-203">Rufen Sie die URL im Location-Header-Wert, um das Ergebnis des Vorgangs langer überprüft.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-203">Retrieve the URL in the Location header value to check the result of the long-running operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistence">
      <MemberSignature Language="C#" Value="public static bool CheckExistence (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistence(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistence(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistence (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistence : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistence (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-205">Der Name der Ressourcengruppe, die die Ressource enthält, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-205">The name of the resource group containing the resource to check.</span></span> <span data-ttu-id="6c1bc-206">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-206">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-207">Der Ressourcenanbieter der Ressource zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-207">The resource provider of the resource to check.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-208">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-208">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-209">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-209">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-210">Der Name der Ressource zu überprüfen, ob es vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-210">The name of the resource to check whether it exists.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-211">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-211">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-212">Überprüft, ob eine Ressource vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-212">Checks whether a resource exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CheckExistenceAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-214">Der Name der Ressourcengruppe, die die Ressource enthält, um zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-214">The name of the resource group containing the resource to check.</span></span> <span data-ttu-id="6c1bc-215">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-215">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-216">Der Ressourcenanbieter der Ressource zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-216">The resource provider of the resource to check.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-217">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-217">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-218">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-218">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-219">Der Name der Ressource zu überprüfen, ob es vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-219">The name of the resource to check whether it exists.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-220">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-220">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-221">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-221">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-222">Überprüft, ob eine Ressource vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-222">Checks whether a resource exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceById">
      <MemberSignature Language="C#" Value="public static bool CheckExistenceById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool CheckExistenceById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CheckExistenceById (operations As IResourcesOperations, resourceId As String, apiVersion As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member CheckExistenceById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; bool" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-224">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-224">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-225">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-225">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-226">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-226">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-227">Überprüft nach ID, ob eine Ressource vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-227">Checks by ID whether a resource exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckExistenceByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; CheckExistenceByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; CheckExistenceByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckExistenceByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CheckExistenceByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CheckExistenceByIdAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-229">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-229">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-230">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-230">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-231">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-231">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-232">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-232">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-233">Überprüft nach ID, ob eine Ressource vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-233">Checks by ID whether a resource exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdate (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdate(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-235">Der Name der Ressourcengruppe für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-235">The name of the resource group for the resource.</span></span> <span data-ttu-id="6c1bc-236">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-236">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-237">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-237">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-238">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-238">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-239">Der Ressourcentyp der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-239">The resource type of the resource to create.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-240">Der Name der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-240">The name of the resource to create.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-241">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-241">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-242">Parameter zum Erstellen oder Aktualisieren der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-242">Parameters for creating or updating the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-243">Erstellt eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-243">Creates a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-244">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-244">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-245">Der Name der Ressourcengruppe für die Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-245">The name of the resource group for the resource.</span></span> <span data-ttu-id="6c1bc-246">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-246">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-247">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-247">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-248">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-248">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-249">Der Ressourcentyp der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-249">The resource type of the resource to create.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-250">Der Name der Ressource zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-250">The name of the resource to create.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-251">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-251">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-252">Parameter zum Erstellen oder Aktualisieren der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-252">Parameters for creating or updating the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-254">Erstellt eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-254">Creates a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdateById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource CreateOrUpdateById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateById (operations As IResourcesOperations, resourceId As String, apiVersion As String, parameters As GenericResource) As GenericResource" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateById (operations, resourceId, apiVersion, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-255">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-256">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-256">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-257">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-257">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-258">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-258">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-259">Erstellen oder Aktualisieren von Ressourcenparametern.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-259">Create or update resource parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-260">Erstellen Sie eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-260">Create a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; CreateOrUpdateByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, class Microsoft.Azure.Management.ResourceManager.Models.GenericResource parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,Microsoft.Azure.Management.ResourceManager.Models.GenericResource,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * Microsoft.Azure.Management.ResourceManager.Models.GenericResource * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.CreateOrUpdateByIdAsync (operations, resourceId, apiVersion, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;CreateOrUpdateByIdAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.GenericResource" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-261">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-262">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-262">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-263">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-263">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-264">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-264">The API version to use for the operation.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-265">Erstellen oder Aktualisieren von Ressourcenparametern.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-265">Create or update resource parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-266">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-266">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-267">Erstellen Sie eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-267">Create a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Delete(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Delete (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-268">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-268">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-269">Der Name der Ressourcengruppe, die die zu löschende Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-269">The name of the resource group that contains the resource to delete.</span></span> <span data-ttu-id="6c1bc-270">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-270">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-271">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-271">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-272">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-272">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-273">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-273">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-274">Der Name der Ressource löschen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-274">The name of the resource to delete.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-275">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-275">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-276">Löscht eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-276">Deletes a resource.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-277">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-278">Der Name der Ressourcengruppe, die die zu löschende Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-278">The name of the resource group that contains the resource to delete.</span></span> <span data-ttu-id="6c1bc-279">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-279">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-280">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-280">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-281">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-281">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-282">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-282">The resource type.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-283">Der Name der Ressource löschen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-283">The name of the resource to delete.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-284">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-284">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-285">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-286">Löscht eine Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-286">Deletes a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteById">
      <MemberSignature Language="C#" Value="public static void DeleteById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteById (operations As IResourcesOperations, resourceId As String, apiVersion As String)" />
      <MemberSignature Language="F#" Value="static member DeleteById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-287">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-287">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-288">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-288">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-289">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-289">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-290">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-290">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-291">Löscht eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-291">Deletes a resource by ID.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.DeleteByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;DeleteByIdAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-292">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-292">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-293">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-293">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-294">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-294">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-295">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-295">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-296">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-296">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-297">Löscht eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-297">Deletes a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource Get (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource Get(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IResourcesOperations, resourceGroupName As String, resourceProviderNamespace As String, parentResourcePath As String, resourceType As String, resourceName As String, apiVersion As String) As GenericResource" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.Get (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-298">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-298">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-299">Der Name der Ressourcengruppe, die die Ressource enthält, abgerufen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-299">The name of the resource group containing the resource to get.</span></span> <span data-ttu-id="6c1bc-300">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-300">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-301">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-301">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-302">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-302">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-303">Der Ressourcentyp der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-303">The resource type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-304">Der Name der abzurufenden Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-304">The name of the resource to get.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-305">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-305">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-306">Ruft eine Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-306">Gets a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, string resourceProviderNamespace, string parentResourcePath, string resourceType, string resourceName, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetAsync (operations, resourceGroupName, resourceProviderNamespace, parentResourcePath, resourceType, resourceName, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;GetAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="parentResourcePath" Type="System.String" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-307">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-307">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-308">Der Name der Ressourcengruppe, die die Ressource enthält, abgerufen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-308">The name of the resource group containing the resource to get.</span></span> <span data-ttu-id="6c1bc-309">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-309">The name is case insensitive.</span></span>
            </param>
        <param name="resourceProviderNamespace">
            <span data-ttu-id="6c1bc-310">Der Namespace des Ressourcenanbieters.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-310">The namespace of the resource provider.</span></span>
            </param>
        <param name="parentResourcePath">
            <span data-ttu-id="6c1bc-311">Die Identität der übergeordneten Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-311">The parent resource identity.</span></span>
            </param>
        <param name="resourceType">
            <span data-ttu-id="6c1bc-312">Der Ressourcentyp der Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-312">The resource type of the resource.</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="6c1bc-313">Der Name der abzurufenden Ressource.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-313">The name of the resource to get.</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-314">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-314">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-315">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-315">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-316">Ruft eine Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-316">Gets a resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.GenericResource GetById (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.GenericResource GetById(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetById(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetById (operations As IResourcesOperations, resourceId As String, apiVersion As String) As GenericResource" />
      <MemberSignature Language="F#" Value="static member GetById : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.GenericResource" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetById (operations, resourceId, apiVersion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.GenericResource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-317">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-317">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-318">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-318">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-319">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-319">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-320">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-320">The API version to use for the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-321">Ruft eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-321">Gets a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetByIdAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; GetByIdAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceId, string apiVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetByIdAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByIdAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.GetByIdAsync (operations, resourceId, apiVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;GetByIdAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="apiVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-322">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-322">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="6c1bc-323">Die vollqualifizierte ID der Ressource, einschließlich Ressourcenname und Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-323">The fully qualified ID of the resource, including the resource name and resource type.</span></span> <span data-ttu-id="6c1bc-324">Verwenden Sie das Format/subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span><span class="sxs-lookup"><span data-stu-id="6c1bc-324">Use the format, /subscriptions/{guid}/resourceGroups/{resource-group-name}/{resource-provider-namespace}/{resource-type}/{resource-name}</span></span>
            </param>
        <param name="apiVersion">
            <span data-ttu-id="6c1bc-325">Die API-Version, für den Vorgang verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-325">The API version to use for the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-326">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-327">Ruft eine Ressource anhand der ID.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-327">Gets a resource by ID.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; List (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; List(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IResourcesOperations, Optional odataQuery As ODataQuery(Of GenericResourceFilter) = null) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.List (operations, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-328">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-328">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6c1bc-329">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-329">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-330">Abgerufen Sie alle Ressourcen in einem Abonnement werden.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-330">Get all the resources in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListAsync (operations, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-331">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-331">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6c1bc-332">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-332">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-333">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-333">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-334">Abgerufen Sie alle Ressourcen in einem Abonnement werden.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-334">Get all the resources in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroup (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroup(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IResourcesOperations, resourceGroupName As String, Optional odataQuery As ODataQuery(Of GenericResourceFilter) = null) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-335">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-335">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-336">Die Ressourcengruppe mit den Ressourcen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-336">The resource group with the resources to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6c1bc-337">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-337">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-338">Rufen Sie alle Ressourcen für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-338">Get all the resources for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string resourceGroupName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResourceFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-339">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-339">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="6c1bc-340">Die Ressourcengruppe mit den Ressourcen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-340">The resource group with the resources to get.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="6c1bc-341">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-341">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-342">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-342">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-343">Rufen Sie alle Ressourcen für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-343">Get all the resources for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IResourcesOperations, nextPageLink As String) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-344">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-344">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6c1bc-345">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-345">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-346">Rufen Sie alle Ressourcen für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-346">Get all the resources for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-347">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-347">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6c1bc-348">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-348">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-349">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-349">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-350">Rufen Sie alle Ressourcen für eine Ressourcengruppe ein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-350">Get all the resources for a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IResourcesOperations, nextPageLink As String) As IPage(Of GenericResource)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-351">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-351">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6c1bc-352">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-352">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-353">Abgerufen Sie alle Ressourcen in einem Abonnement werden.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-353">Get all the resources in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ListNextAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.GenericResource&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-354">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-354">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="6c1bc-355">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-355">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-356">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-356">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-357">Abgerufen Sie alle Ressourcen in einem Abonnement werden.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-357">Get all the resources in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveResources">
      <MemberSignature Language="C#" Value="public static void MoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void MoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub MoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member MoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-358">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-358">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-359">Der Name der Ressourcengruppe, die die Ressourcen enthält, verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-359">The name of the resource group containing the resources to move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-360">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-360">Parameters for moving resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-361">Verschiebt Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-361">Moves resources from one resource group to another resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="6c1bc-362">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-362">The resources to move must be in the same source resource group.</span></span> <span data-ttu-id="6c1bc-363">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-363">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-364">Beim Verschieben von Ressourcen sind die Source-Gruppe und die Zielgruppe für die Dauer des Vorgangs gesperrt.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-364">When moving resources, both the source group and the target group are locked for the duration of the operation.</span></span> <span data-ttu-id="6c1bc-365">Schreib- und Löschvorgänge in den Gruppen werden bis zum Abschluss der Verschiebung blockiert.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-365">Write and delete operations are blocked on the groups until the move completes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task MoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task MoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.MoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;MoveResourcesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-366">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-366">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-367">Der Name der Ressourcengruppe, die die Ressourcen enthält, verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-367">The name of the resource group containing the resources to move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-368">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-368">Parameters for moving resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-369">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-369">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-370">Verschiebt Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-370">Moves resources from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6c1bc-371">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-371">The resources to move must be in the same source resource group.</span></span> <span data-ttu-id="6c1bc-372">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-372">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-373">Beim Verschieben von Ressourcen sind die Source-Gruppe und die Zielgruppe für die Dauer des Vorgangs gesperrt.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-373">When moving resources, both the source group and the target group are locked for the duration of the operation.</span></span> <span data-ttu-id="6c1bc-374">Schreib- und Löschvorgänge in den Gruppen werden bis zum Abschluss der Verschiebung blockiert.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-374">Write and delete operations are blocked on the groups until the move completes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveResources">
      <MemberSignature Language="C#" Value="public static void ValidateMoveResources (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void ValidateMoveResources(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResources(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub ValidateMoveResources (operations As IResourcesOperations, sourceResourceGroupName As String, parameters As ResourcesMoveInfo)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveResources : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo -&gt; unit" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResources (operations, sourceResourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-375">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-375">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-376">Der Name der Ressourcengruppe, die die Ressourcen enthalten, zur Überprüfung für verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-376">The name of the resource group containing the resources to validate for move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-377">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-377">Parameters for moving resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-378">Überprüft, ob Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-378">Validates whether resources can be moved from one resource group to another resource group.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="6c1bc-379">Dieser Vorgang wird überprüft, ob die angegebenen Ressourcen zum Ziel verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-379">This operation checks whether the specified resources can be moved to the target.</span></span> <span data-ttu-id="6c1bc-380">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-380">The resources to move must be in the same source resource group.</span></span>
            <span data-ttu-id="6c1bc-381">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-381">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-382">Wenn die Überprüfung erfolgreich ist, wird der HTTP-Antwortcode 204 (kein Inhalt) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-382">If validation succeeds, it returns HTTP response code 204 (no content).</span></span> <span data-ttu-id="6c1bc-383">Wenn die Validierung fehlschlägt, wird der HTTP-Antwortcode 409 (Konflikt) mit einer Fehlermeldung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-383">If validation fails, it returns HTTP response code 409 (Conflict) with an error message.</span></span>
            <span data-ttu-id="6c1bc-384">Rufen Sie die URL im Location-Header-Wert, um das Ergebnis des Vorgangs langer überprüft.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-384">Retrieve the URL in the Location header value to check the result of the long-running operation.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateMoveResourcesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ValidateMoveResourcesAsync (this Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ValidateMoveResourcesAsync(class Microsoft.Azure.Management.ResourceManager.IResourcesOperations operations, string sourceResourceGroupName, class Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResourcesAsync(Microsoft.Azure.Management.ResourceManager.IResourcesOperations,System.String,Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ValidateMoveResourcesAsync : Microsoft.Azure.Management.ResourceManager.IResourcesOperations * string * Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions.ValidateMoveResourcesAsync (operations, sourceResourceGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ResourcesOperationsExtensions/&lt;ValidateMoveResourcesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IResourcesOperations" RefType="this" />
        <Parameter Name="sourceResourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ResourceManager.Models.ResourcesMoveInfo" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="6c1bc-385">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-385">The operations group for this extension method.</span></span>
            </param>
        <param name="sourceResourceGroupName">
            <span data-ttu-id="6c1bc-386">Der Name der Ressourcengruppe, die die Ressourcen enthalten, zur Überprüfung für verschieben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-386">The name of the resource group containing the resources to validate for move.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6c1bc-387">Parameter für das Verschieben von Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-387">Parameters for moving resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6c1bc-388">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-388">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6c1bc-389">Überprüft, ob Ressourcen aus einer Ressourcengruppe in eine andere Ressourcengruppe verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-389">Validates whether resources can be moved from one resource group to another resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="6c1bc-390">Dieser Vorgang wird überprüft, ob die angegebenen Ressourcen zum Ziel verschoben werden können.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-390">This operation checks whether the specified resources can be moved to the target.</span></span> <span data-ttu-id="6c1bc-391">Der zu verschiebenden Ressourcen müssen in der gleichen Ressourcengruppe für die Quelle sein.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-391">The resources to move must be in the same source resource group.</span></span>
            <span data-ttu-id="6c1bc-392">Die Zielressourcengruppe möglicherweise ein anderes Abonnement.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-392">The target resource group may be in a different subscription.</span></span> <span data-ttu-id="6c1bc-393">Wenn die Überprüfung erfolgreich ist, wird der HTTP-Antwortcode 204 (kein Inhalt) zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-393">If validation succeeds, it returns HTTP response code 204 (no content).</span></span> <span data-ttu-id="6c1bc-394">Wenn die Validierung fehlschlägt, wird der HTTP-Antwortcode 409 (Konflikt) mit einer Fehlermeldung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-394">If validation fails, it returns HTTP response code 409 (Conflict) with an error message.</span></span>
            <span data-ttu-id="6c1bc-395">Rufen Sie die URL im Location-Header-Wert, um das Ergebnis des Vorgangs langer überprüft.</span><span class="sxs-lookup"><span data-stu-id="6c1bc-395">Retrieve the URL in the Location header value to check the result of the long-running operation.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>