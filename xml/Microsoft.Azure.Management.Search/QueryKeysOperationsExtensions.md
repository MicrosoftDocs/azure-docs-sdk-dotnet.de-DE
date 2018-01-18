<Type Name="QueryKeysOperationsExtensions" FullName="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class QueryKeysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueryKeysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module QueryKeysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type QueryKeysOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="417fc-101">Erweiterungsmethoden für QueryKeysOperations.</span><span class="sxs-lookup"><span data-stu-id="417fc-101">Extension methods for QueryKeysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.QueryKey Create (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.QueryKey Create(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Create(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.QueryKey" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Create (operations, resourceGroupName, searchServiceName, name, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.QueryKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="417fc-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="417fc-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="417fc-103">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="417fc-103">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="417fc-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="417fc-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="417fc-105">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="417fc-105">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="417fc-106">Der Name der neuen Abfrage-API-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="417fc-106">The name of the new query API key.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="417fc-107">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="417fc-107">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="417fc-108">Generiert einen neuen Abfrageschlüssel für den angegebenen Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="417fc-108">Generates a new query key for the specified Search service.</span></span> <span data-ttu-id="417fc-109">Pro Dienst können Sie bis zu 50 Abfrageschlüssel erstellen.</span><span class="sxs-lookup"><span data-stu-id="417fc-109">You can create up to 50 query keys per service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt; CreateAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt; CreateAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.CreateAsync (operations, resourceGroupName, searchServiceName, name, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="417fc-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="417fc-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="417fc-111">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="417fc-111">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="417fc-112">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="417fc-112">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="417fc-113">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="417fc-113">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="417fc-114">Der Name der neuen Abfrage-API-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="417fc-114">The name of the new query API key.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="417fc-115">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="417fc-115">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="417fc-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="417fc-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="417fc-117">Generiert einen neuen Abfrageschlüssel für den angegebenen Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="417fc-117">Generates a new query key for the specified Search service.</span></span> <span data-ttu-id="417fc-118">Pro Dienst können Sie bis zu 50 Abfrageschlüssel erstellen.</span><span class="sxs-lookup"><span data-stu-id="417fc-118">You can create up to 50 query keys per service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Delete(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; unit" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.Delete (operations, resourceGroupName, searchServiceName, key, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="417fc-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="417fc-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="417fc-120">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="417fc-120">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="417fc-121">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="417fc-121">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="417fc-122">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="417fc-122">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="417fc-123">Der Abfrageschlüssel gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="417fc-123">The query key to be deleted.</span></span> <span data-ttu-id="417fc-124">Abfrageschlüssel werden anhand des Werts nicht anhand des Namens identifiziert.</span><span class="sxs-lookup"><span data-stu-id="417fc-124">Query keys are identified by value, not by name.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="417fc-125">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="417fc-125">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="417fc-126">Löscht den Schlüssel für die angegebene Abfrage.</span><span class="sxs-lookup"><span data-stu-id="417fc-126">Deletes the specified query key.</span></span> <span data-ttu-id="417fc-127">Im Gegensatz zu Administratorschlüssel werden Abfrageschlüssel nicht neu generiert.</span><span class="sxs-lookup"><span data-stu-id="417fc-127">Unlike admin keys, query keys are not regenerated.</span></span> <span data-ttu-id="417fc-128">Für die Neugenerierung eines Abfrageschlüssels müssen Sie diesen löschen und neu erstellen.</span><span class="sxs-lookup"><span data-stu-id="417fc-128">The process for regenerating a query key is to delete and then recreate it.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, string key, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.DeleteAsync (operations, resourceGroupName, searchServiceName, key, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="417fc-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="417fc-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="417fc-130">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="417fc-130">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="417fc-131">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="417fc-131">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="417fc-132">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="417fc-132">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="417fc-133">Der Abfrageschlüssel gelöscht werden soll.</span><span class="sxs-lookup"><span data-stu-id="417fc-133">The query key to be deleted.</span></span> <span data-ttu-id="417fc-134">Abfrageschlüssel werden anhand des Werts nicht anhand des Namens identifiziert.</span><span class="sxs-lookup"><span data-stu-id="417fc-134">Query keys are identified by value, not by name.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="417fc-135">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="417fc-135">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="417fc-136">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="417fc-136">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="417fc-137">Löscht den Schlüssel für die angegebene Abfrage.</span><span class="sxs-lookup"><span data-stu-id="417fc-137">Deletes the specified query key.</span></span> <span data-ttu-id="417fc-138">Im Gegensatz zu Administratorschlüssel werden Abfrageschlüssel nicht neu generiert.</span><span class="sxs-lookup"><span data-stu-id="417fc-138">Unlike admin keys, query keys are not regenerated.</span></span> <span data-ttu-id="417fc-139">Für die Neugenerierung eines Abfrageschlüssels müssen Sie diesen löschen und neu erstellen.</span><span class="sxs-lookup"><span data-stu-id="417fc-139">The process for regenerating a query key is to delete and then recreate it.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchService">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt; ListBySearchService (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt; ListBySearchService(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchService(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListBySearchService : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchService (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="417fc-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="417fc-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="417fc-141">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="417fc-141">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="417fc-142">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="417fc-142">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="417fc-143">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="417fc-143">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="417fc-144">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="417fc-144">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="417fc-145">Gibt die Liste der Abfrage-API-Schlüssel für den angegebenen Azure-Suchdienst zurück.</span><span class="sxs-lookup"><span data-stu-id="417fc-145">Returns the list of query API keys for the given Azure Search service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySearchServiceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; ListBySearchServiceAsync (this Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt; ListBySearchServiceAsync(class Microsoft.Azure.Management.Search.IQueryKeysOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchServiceAsync(Microsoft.Azure.Management.Search.IQueryKeysOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySearchServiceAsync : Microsoft.Azure.Management.Search.IQueryKeysOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;" Usage="Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions.ListBySearchServiceAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.QueryKeysOperationsExtensions/&lt;ListBySearchServiceAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.QueryKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IQueryKeysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="417fc-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="417fc-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="417fc-147">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="417fc-147">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="417fc-148">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="417fc-148">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="417fc-149">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="417fc-149">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="417fc-150">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="417fc-150">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="417fc-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="417fc-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="417fc-152">Gibt die Liste der Abfrage-API-Schlüssel für den angegebenen Azure-Suchdienst zurück.</span><span class="sxs-lookup"><span data-stu-id="417fc-152">Returns the list of query API keys for the given Azure Search service.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>