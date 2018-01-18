<Type Name="SavedSearchesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class SavedSearchesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit SavedSearchesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module SavedSearchesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type SavedSearchesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="cea44-101">Erweiterungsmethoden für SavedSearchesOperations.</span><span class="sxs-lookup"><span data-stu-id="cea44-101">Extension methods for SavedSearchesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ISavedSearchesOperations, resourceGroupName As String, workspaceName As String, savedSearchName As String, parameters As SavedSearch) As SavedSearch" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, savedSearchName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-103">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-103">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-104">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-104">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-105">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-105">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-106">Die Id der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-106">The id of the saved search.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cea44-107">Die Parameter erforderlich, um eine Suche zu speichern.</span><span class="sxs-lookup"><span data-stu-id="cea44-107">The parameters required to save a search.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-108">Erstellt oder aktualisiert eine gespeicherte Suche für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="cea44-108">Creates or updates a saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, savedSearchName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-110">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-110">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-111">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-111">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-112">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-112">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-113">Die Id der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-113">The id of the saved search.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="cea44-114">Die Parameter erforderlich, um eine Suche zu speichern.</span><span class="sxs-lookup"><span data-stu-id="cea44-114">The parameters required to save a search.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cea44-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cea44-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-116">Erstellt oder aktualisiert eine gespeicherte Suche für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="cea44-116">Creates or updates a saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ISavedSearchesOperations, resourceGroupName As String, workspaceName As String, savedSearchName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName, savedSearchName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-118">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-118">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-119">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-119">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-120">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-120">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-121">Der Name der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-121">Name of the saved search.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-122">Löscht die angegebene gespeicherte Suche in einem bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="cea44-122">Deletes the specified saved search in a given workspace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, savedSearchName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-124">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-124">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-125">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-125">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-126">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-126">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-127">Der Name der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-127">Name of the saved search.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cea44-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cea44-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-129">Löscht die angegebene gespeicherte Suche in einem bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="cea44-129">Deletes the specified saved search in a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch Get (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch Get(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ISavedSearchesOperations, resourceGroupName As String, workspaceName As String, savedSearchName As String) As SavedSearch" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.Get (operations, resourceGroupName, workspaceName, savedSearchName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-131">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-131">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-132">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-132">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-133">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-133">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-134">Die Id der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-134">The id of the saved search.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-135">Ruft die angegebene gespeicherte Suche für einen bestimmten Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="cea44-135">Gets the specified saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, savedSearchName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearch&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-137">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-137">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-138">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-138">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-139">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-139">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-140">Die Id der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-140">The id of the saved search.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cea44-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cea44-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-142">Ruft die angegebene gespeicherte Suche für einen bestimmten Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="cea44-142">Gets the specified saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetResults (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetResults(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.GetResults(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetResults (operations As ISavedSearchesOperations, resourceGroupName As String, workspaceName As String, savedSearchName As String) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member GetResults : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.GetResults (operations, resourceGroupName, workspaceName, savedSearchName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-144">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-144">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-145">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-145">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-146">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-146">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-147">Der Name der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-147">The name of the saved search.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-148">Ruft die Ergebnisse aus einer gespeicherten Suche für einen bestimmten Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="cea44-148">Gets the results from a saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetResultsAsync (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetResultsAsync(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, string savedSearchName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.GetResultsAsync(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetResultsAsync : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.GetResultsAsync (operations, resourceGroupName, workspaceName, savedSearchName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions/&lt;GetResultsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="savedSearchName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-150">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-150">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-151">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-151">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-152">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-152">Log Analytics workspace name</span></span>
            </param>
        <param name="savedSearchName">
            <span data-ttu-id="cea44-153">Der Name der gespeicherten Suche.</span><span class="sxs-lookup"><span data-stu-id="cea44-153">The name of the saved search.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cea44-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cea44-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-155">Ruft die Ergebnisse aus einer gespeicherten Suche für einen bestimmten Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="cea44-155">Gets the results from a saved search for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult ListByWorkspace (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult ListByWorkspace(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.ListByWorkspace(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByWorkspace (operations As ISavedSearchesOperations, resourceGroupName As String, workspaceName As String) As SavedSearchesListResult" />
      <MemberSignature Language="F#" Value="static member ListByWorkspace : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.ListByWorkspace (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-157">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-157">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-158">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-158">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-159">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-159">Log Analytics workspace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-160">Ruft das gespeicherte Suchvorgänge für einen bestimmten Protokollanalyse-Arbeitsbereich</span><span class="sxs-lookup"><span data-stu-id="cea44-160">Gets the saved searches for a given Log Analytics Workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByWorkspaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt; ListByWorkspaceAsync (this Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt; ListByWorkspaceAsync(class Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.ListByWorkspaceAsync(Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByWorkspaceAsync : Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions.ListByWorkspaceAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.SavedSearchesOperationsExtensions/&lt;ListByWorkspaceAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SavedSearchesListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.ISavedSearchesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="cea44-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="cea44-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="cea44-162">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="cea44-162">The name of the resource group to get.</span></span> <span data-ttu-id="cea44-163">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="cea44-163">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="cea44-164">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="cea44-164">Log Analytics workspace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="cea44-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="cea44-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="cea44-166">Ruft das gespeicherte Suchvorgänge für einen bestimmten Protokollanalyse-Arbeitsbereich</span><span class="sxs-lookup"><span data-stu-id="cea44-166">Gets the saved searches for a given Log Analytics Workspace</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>