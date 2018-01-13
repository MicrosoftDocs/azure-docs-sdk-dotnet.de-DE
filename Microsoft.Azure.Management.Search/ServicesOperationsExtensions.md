<Type Name="ServicesOperationsExtensions" FullName="Microsoft.Azure.Management.Search.ServicesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServicesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServicesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Search.ServicesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServicesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServicesOperationsExtensions = class" />
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
            <span data-ttu-id="619ea-101">Erweiterungsmethoden für ServicesOperations.</span><span class="sxs-lookup"><span data-stu-id="619ea-101">Extension methods for ServicesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckNameAvailability">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput CheckNameAvailability (this Microsoft.Azure.Management.Search.IServicesOperations operations, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput CheckNameAvailability(class Microsoft.Azure.Management.Search.IServicesOperations operations, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailability(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailability : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailability (operations, name, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-102">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="619ea-103">Der Search-Dienst zu überprüfende Name.</span><span class="sxs-lookup"><span data-stu-id="619ea-103">The Search service name to validate.</span></span> <span data-ttu-id="619ea-104">Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="619ea-104">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-105">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-105">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-106">Überprüft, und zwar unabhängig davon, ob der angegebene Dienstname für die Verwendung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="619ea-106">Checks whether or not the given Search service name is available for use.</span></span>
            <span data-ttu-id="619ea-107">Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten).</span><span class="sxs-lookup"><span data-stu-id="619ea-107">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckNameAvailabilityAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabilityAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string name, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt; CheckNameAvailabilityAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string name, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailabilityAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CheckNameAvailabilityAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CheckNameAvailabilityAsync (operations, name, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;CheckNameAvailabilityAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.CheckNameAvailabilityOutput&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-108">The operations group for this extension method.</span></span>
            </param>
        <param name="name">
            <span data-ttu-id="619ea-109">Der Search-Dienst zu überprüfende Name.</span><span class="sxs-lookup"><span data-stu-id="619ea-109">The Search service name to validate.</span></span> <span data-ttu-id="619ea-110">Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="619ea-110">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-111">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-111">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="619ea-112">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="619ea-112">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-113">Überprüft, und zwar unabhängig davon, ob der angegebene Dienstname für die Verwendung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="619ea-113">Checks whether or not the given Search service name is available for use.</span></span>
            <span data-ttu-id="619ea-114">Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten).</span><span class="sxs-lookup"><span data-stu-id="619ea-114">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.SearchService CreateOrUpdate (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.SearchService CreateOrUpdate(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, searchServiceName, service, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.SearchService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-116">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-116">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-117">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-117">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="619ea-118">Der Name des Azure-Suchdienst erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="619ea-118">The name of the Azure Search service to create or update.</span></span> <span data-ttu-id="619ea-119">Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="619ea-119">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span> <span data-ttu-id="619ea-120">Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten).</span><span class="sxs-lookup"><span data-stu-id="619ea-120">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span> <span data-ttu-id="619ea-121">Der Dienstname kann nicht geändert werden, nachdem der Dienst erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="619ea-121">You cannot change the service name after the service is created.</span></span>
            </param>
        <param name="service">
            <span data-ttu-id="619ea-122">Die Definition der Search-Dienst erstellt oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="619ea-122">The definition of the Search service to create or update.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-123">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-123">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-124">Erstellt oder aktualisiert einen Search-Dienst in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="619ea-124">Creates or updates a Search service in the given resource group.</span></span> <span data-ttu-id="619ea-125">Wenn der Search-Dienst bereits vorhanden ist, werden alle Eigenschaften mit den angegebenen Werten aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-125">If the Search service already exists, all properties will be updated with the given values.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchService service, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchService service, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchService,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchService * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, searchServiceName, service, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="service" Type="Microsoft.Azure.Management.Search.Models.SearchService" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-127">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-127">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-128">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-128">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="619ea-129">Der Name des Azure-Suchdienst erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="619ea-129">The name of the Azure Search service to create or update.</span></span> <span data-ttu-id="619ea-130">Suchen von Dienstnamen darf nur Kleinbuchstaben, Ziffern oder Gedankenstriche enthalten, können keine Bindestrich als eines der ersten beiden oder als letztes Zeichen darf keine aufeinanderfolgenden Bindestriche enthalten und müssen zwischen 2 und 60 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="619ea-130">Search service names must only contain lowercase letters, digits or dashes, cannot use dash as the first two or last one characters, cannot contain consecutive dashes, and must be between 2 and 60 characters in length.</span></span> <span data-ttu-id="619ea-131">Suchen von Dienstnamen müssen global eindeutig sein, da sie Teil des Dienst-URIS sind (https://&lt;Namen&gt;..Search.Windows.NET"lauten).</span><span class="sxs-lookup"><span data-stu-id="619ea-131">Search service names must be globally unique since they are part of the service URI (https://&lt;name&gt;.search.windows.net).</span></span> <span data-ttu-id="619ea-132">Der Dienstname kann nicht geändert werden, nachdem der Dienst erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="619ea-132">You cannot change the service name after the service is created.</span></span>
            </param>
        <param name="service">
            <span data-ttu-id="619ea-133">Die Definition der Search-Dienst erstellt oder aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="619ea-133">The definition of the Search service to create or update.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-134">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-134">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="619ea-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="619ea-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-136">Erstellt oder aktualisiert einen Search-Dienst in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="619ea-136">Creates or updates a Search service in the given resource group.</span></span> <span data-ttu-id="619ea-137">Wenn der Search-Dienst bereits vorhanden ist, werden alle Eigenschaften mit den angegebenen Werten aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-137">If the Search service already exists, all properties will be updated with the given values.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Delete(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; unit" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Delete (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-139">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-139">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-140">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-140">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="619ea-141">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="619ea-141">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-142">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-142">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-143">Löscht einen Search-Dienst in der angegebenen Ressourcengruppe sowie die zugehörigen Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="619ea-143">Deletes a Search service in the given resource group, along with its associated resources.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.DeleteAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-145">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-145">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-146">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-146">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="619ea-147">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="619ea-147">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-148">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-148">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="619ea-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="619ea-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-150">Löscht einen Search-Dienst in der angegebenen Ressourcengruppe sowie die zugehörigen Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="619ea-150">Deletes a Search service in the given resource group, along with its associated resources.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Search.Models.SearchService Get (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Search.Models.SearchService Get(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Get(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; Microsoft.Azure.Management.Search.Models.SearchService" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.Get (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Search.Models.SearchService</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-152">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-152">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-153">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="619ea-154">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="619ea-154">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-155">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-155">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-156">Ruft die Search-Dienst mit dem angegebenen Namen in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="619ea-156">Gets the Search service with the given name in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; GetAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; GetAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, string searchServiceName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.GetAsync (operations, resourceGroupName, searchServiceName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchServiceName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-158">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-158">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-159">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchServiceName">
            <span data-ttu-id="619ea-160">Der Name des Azure-Suchdienst mit der angegebenen Ressourcengruppe verknüpft ist.</span><span class="sxs-lookup"><span data-stu-id="619ea-160">The name of the Azure Search service associated with the specified resource group.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-161">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-161">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="619ea-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="619ea-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-163">Ruft die Search-Dienst mit dem angegebenen Namen in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="619ea-163">Gets the Search service with the given name in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt; ListByResourceGroup (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt; ListByResourceGroup(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions -&gt; seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, searchManagementRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-165">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-165">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-166">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-167">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-168">Ruft eine Liste aller Suchdienste in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="619ea-168">Gets a list of all Search services in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Search.IServicesOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions searchManagementRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Search.IServicesOperations,System.String,Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Search.IServicesOperations * string * Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;" Usage="Microsoft.Azure.Management.Search.ServicesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, searchManagementRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Search</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Search.ServicesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Search.Models.SearchService&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Search.IServicesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="searchManagementRequestOptions" Type="Microsoft.Azure.Management.Search.Models.SearchManagementRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="619ea-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="619ea-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="619ea-170">Der Name der Ressourcengruppe innerhalb des aktuellen Abonnements.</span><span class="sxs-lookup"><span data-stu-id="619ea-170">The name of the resource group within the current subscription.</span></span> <span data-ttu-id="619ea-171">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="619ea-171">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="searchManagementRequestOptions">
            <span data-ttu-id="619ea-172">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="619ea-172">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="619ea-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="619ea-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="619ea-174">Ruft eine Liste aller Suchdienste in der angegebenen Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="619ea-174">Gets a list of all Search services in the given resource group.</span></span>
            <see href="https://aka.ms/search-manage" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>