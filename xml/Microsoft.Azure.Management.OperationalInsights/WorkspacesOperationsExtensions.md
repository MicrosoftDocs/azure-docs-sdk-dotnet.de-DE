<Type Name="WorkspacesOperationsExtensions" FullName="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WorkspacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WorkspacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WorkspacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WorkspacesOperationsExtensions = class" />
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
            <span data-ttu-id="ac6a1-101">Erweiterungsmethoden für WorkspacesOperations.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-101">Extension methods for WorkspacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace BeginCreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace BeginCreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As Workspace) As Workspace" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-103">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-103">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-104">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-104">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-105">Die Parameter zum Erstellen oder Aktualisieren eines Arbeitsbereichs erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-105">The parameters required to create or update a workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-106">Erstellen oder Aktualisieren eines Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-106">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-108">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-108">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-109">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-109">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-110">Die Parameter zum Erstellen oder Aktualisieren eines Arbeitsbereichs erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-110">The parameters required to create or update a workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-112">Erstellen oder Aktualisieren eines Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-112">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse BeginGetSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse BeginGetSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As SearchParameters) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member BeginGetSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResults (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-114">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-114">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-115">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-115">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-116">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-116">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-117">Die Parameter erforderlich, um eine Suchabfrage auszuführen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-117">The parameters required to execute a search query.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-118">Senden Sie eine Suche nach einem bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-118">Submit a search for a given workspace.</span></span> <span data-ttu-id="ac6a1-119">Die Antwort enthält eine Id, um die Suche zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-119">The response will contain an id to track the search.</span></span> <span data-ttu-id="ac6a1-120">Benutzer können die Id des Suchstatus abrufen und das vollständige Suchergebnis später abrufen, wenn die Suche viel Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-120">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; BeginGetSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; BeginGetSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.BeginGetSearchResultsAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;BeginGetSearchResultsAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-121">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-121">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-122">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-122">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-123">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-123">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-124">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-124">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-125">Die Parameter erforderlich, um eine Suchabfrage auszuführen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-125">The parameters required to execute a search query.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-127">Senden Sie eine Suche nach einem bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-127">Submit a search for a given workspace.</span></span> <span data-ttu-id="ac6a1-128">Die Antwort enthält eine Id, um die Suche zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-128">The response will contain an id to track the search.</span></span> <span data-ttu-id="ac6a1-129">Benutzer können die Id des Suchstatus abrufen und das vollständige Suchergebnis später abrufen, wenn die Suche viel Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-129">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace CreateOrUpdate (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace CreateOrUpdate(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As Workspace) As Workspace" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-131">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-131">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-132">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-132">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-133">Die Parameter zum Erstellen oder Aktualisieren eines Arbeitsbereichs erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-133">The parameters required to create or update a workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-134">Erstellen oder Aktualisieren eines Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-134">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.Workspace parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.Workspace,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.Workspace * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.Workspace" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-136">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-136">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-137">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-137">The name of the workspace.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-138">Die Parameter zum Erstellen oder Aktualisieren eines Arbeitsbereichs erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-138">The parameters required to create or update a workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-140">Erstellen oder Aktualisieren eines Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-140">Create or update a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Delete(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Delete (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-142">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-142">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-143">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-143">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-144">Löscht eine-Instanz des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-144">Deletes a workspace instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;DeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-146">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-146">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-147">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-147">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-149">Löscht eine-Instanz des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-149">Deletes a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePack">
      <MemberSignature Language="C#" Value="public static void DisableIntelligencePack (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DisableIntelligencePack(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePack(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DisableIntelligencePack (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, intelligencePackName As String)" />
      <MemberSignature Language="F#" Value="static member DisableIntelligencePack : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePack (operations, resourceGroupName, workspaceName, intelligencePackName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-151">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-151">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-152">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-152">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-153">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-153">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="ac6a1-154">Der Name des Intelligence Packs deaktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-154">The name of the intelligence pack to be disabled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-155">Deaktiviert ein Intelligence Pack für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-155">Disables an intelligence pack for a given workspace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableIntelligencePackAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableIntelligencePackAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableIntelligencePackAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePackAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableIntelligencePackAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.DisableIntelligencePackAsync (operations, resourceGroupName, workspaceName, intelligencePackName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;DisableIntelligencePackAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-157">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-157">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-158">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-158">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-159">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-159">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="ac6a1-160">Der Name des Intelligence Packs deaktiviert werden soll.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-160">The name of the intelligence pack to be disabled.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-162">Deaktiviert ein Intelligence Pack für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-162">Disables an intelligence pack for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePack">
      <MemberSignature Language="C#" Value="public static void EnableIntelligencePack (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void EnableIntelligencePack(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePack(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub EnableIntelligencePack (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, intelligencePackName As String)" />
      <MemberSignature Language="F#" Value="static member EnableIntelligencePack : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePack (operations, resourceGroupName, workspaceName, intelligencePackName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-164">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-164">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-165">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-165">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-166">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-166">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="ac6a1-167">Der Name des Intelligence Packs aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-167">The name of the intelligence pack to be enabled.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-168">Aktiviert ein Intelligence Pack für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-168">Enables an intelligence pack for a given workspace.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIntelligencePackAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task EnableIntelligencePackAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task EnableIntelligencePackAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string intelligencePackName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePackAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableIntelligencePackAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.EnableIntelligencePackAsync (operations, resourceGroupName, workspaceName, intelligencePackName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;EnableIntelligencePackAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="intelligencePackName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-170">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-170">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-171">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-171">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-172">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-172">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="intelligencePackName">
            <span data-ttu-id="ac6a1-173">Der Name des Intelligence Packs aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-173">The name of the intelligence pack to be enabled.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-175">Aktiviert ein Intelligence Pack für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-175">Enables an intelligence pack for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.Workspace Get (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.Workspace Get(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Get(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As Workspace" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.Workspace" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.Get (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.Workspace</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-177">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-177">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-178">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-178">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-179">Ruft eine Instanz des Arbeitsbereichs ab.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-179">Gets a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; GetAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; GetAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-181">Der Ressourcengruppenname des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-181">The resource group name of the workspace.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-182">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-182">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-184">Ruft eine Instanz des Arbeitsbereichs ab.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-184">Gets a workspace instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchema">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse GetSchema (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse GetSchema(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchema(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSchema (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As SearchGetSchemaResponse" />
      <MemberSignature Language="F#" Value="static member GetSchema : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchema (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-186">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-186">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-187">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-187">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-188">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-188">Log Analytics workspace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-189">Ruft das Schema für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-189">Gets the schema for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSchemaAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt; GetSchemaAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt; GetSchemaAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchemaAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSchemaAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSchemaAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSchemaAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchGetSchemaResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-191">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-191">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-192">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-192">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-193">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-193">Log Analytics workspace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-195">Ruft das Schema für einen bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-195">Gets the schema for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse GetSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, parameters As SearchParameters) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member GetSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResults (operations, resourceGroupName, workspaceName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-197">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-197">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-198">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-198">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-199">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-199">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-200">Die Parameter erforderlich, um eine Suchabfrage auszuführen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-200">The parameters required to execute a search query.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-201">Senden Sie eine Suche nach einem bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-201">Submit a search for a given workspace.</span></span> <span data-ttu-id="ac6a1-202">Die Antwort enthält eine Id, um die Suche zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-202">The response will contain an id to track the search.</span></span> <span data-ttu-id="ac6a1-203">Benutzer können die Id des Suchstatus abrufen und das vollständige Suchergebnis später abrufen, wenn die Suche viel Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-203">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; GetSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, class Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSearchResultsAsync (operations, resourceGroupName, workspaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSearchResultsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.OperationalInsights.Models.SearchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-205">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-205">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-206">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-206">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-207">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-207">Log Analytics workspace name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ac6a1-208">Die Parameter erforderlich, um eine Suchabfrage auszuführen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-208">The parameters required to execute a search query.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-210">Senden Sie eine Suche nach einem bestimmten Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-210">Submit a search for a given workspace.</span></span> <span data-ttu-id="ac6a1-211">Die Antwort enthält eine Id, um die Suche zu verfolgen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-211">The response will contain an id to track the search.</span></span> <span data-ttu-id="ac6a1-212">Benutzer können die Id des Suchstatus abrufen und das vollständige Suchergebnis später abrufen, wenn die Suche viel Zeit in Anspruch nimmt.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-212">User can use the id to poll the search status and get the full search result later if the search takes long time to finish.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys GetSharedKeys (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys GetSharedKeys(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeys(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSharedKeys (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As SharedKeys" />
      <MemberSignature Language="F#" Value="static member GetSharedKeys : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeys (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-213">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-214">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-214">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-215">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-215">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-216">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-216">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-217">Ruft den gemeinsam verwendeten Schlüssel für einen Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-217">Gets the shared keys for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt; GetSharedKeysAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt; GetSharedKeysAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeysAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeysAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.GetSharedKeysAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;GetSharedKeysAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SharedKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-219">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-219">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-220">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-220">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-221">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-221">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-223">Ruft den gemeinsam verwendeten Schlüssel für einen Arbeitsbereich ab.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-223">Gets the shared keys for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; List (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; List(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.List(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWorkspacesOperations) As IEnumerable(Of Workspace)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-224">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-225">Ruft die Arbeitsbereiche in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-225">Gets the workspaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-226">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-228">Ruft die Arbeitsbereiche in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-228">Gets the workspaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; ListByResourceGroup (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt; ListByResourceGroup(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IWorkspacesOperations, resourceGroupName As String) As IEnumerable(Of Workspace)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-230">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-230">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-231">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-231">The name is case insensitive.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-232">Ruft die Arbeitsbereiche in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-232">Gets workspaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.Workspace&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-234">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-234">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-235">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-235">The name is case insensitive.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-236">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-237">Ruft die Arbeitsbereiche in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-237">Gets workspaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacks">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt; ListIntelligencePacks (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt; ListIntelligencePacks(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacks(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListIntelligencePacks (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IList(Of IntelligencePack)" />
      <MemberSignature Language="F#" Value="static member ListIntelligencePacks : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacks (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-238">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-238">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-239">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-239">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-240">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-240">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-241">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-241">Name of the Log Analytics Workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-242">Listen alle Intelligence packs, möglich und gibt an, ob sie aktiviert oder für einen bestimmten Arbeitsbereich angezeigt deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-242">Lists all the intelligence packs possible and whether they are enabled or disabled for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListIntelligencePacksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt; ListIntelligencePacksAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt; ListIntelligencePacksAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacksAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListIntelligencePacksAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListIntelligencePacksAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListIntelligencePacksAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.IntelligencePack&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-244">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-244">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-245">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-245">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-246">Der Name des der Protokollanalyse-Arbeitsbereich.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-246">Name of the Log Analytics Workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-247">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-248">Listen alle Intelligence packs, möglich und gibt an, ob sie aktiviert oder für einen bestimmten Arbeitsbereich angezeigt deaktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-248">Lists all the intelligence packs possible and whether they are enabled or disabled for a given workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargets">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt; ListLinkTargets (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt; ListLinkTargets(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargets(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListLinkTargets (operations As IWorkspacesOperations) As IList(Of LinkTarget)" />
      <MemberSignature Language="F#" Value="static member ListLinkTargets : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargets operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-249">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-249">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-250">Abrufen einer Liste der Arbeitsbereiche, die der aktuelle Benutzer hat und über Administratorrechte und sind nicht mit einem Azure-Abonnement verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-250">Get a list of workspaces which the current user has administrator privileges and are not associated with an Azure Subscription.</span></span> <span data-ttu-id="ac6a1-251">Der Parameter "subscriptionId" in der Url wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-251">The subscriptionId parameter in the Url is ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListLinkTargetsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt; ListLinkTargetsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt; ListLinkTargetsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargetsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListLinkTargetsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListLinkTargetsAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListLinkTargetsAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.OperationalInsights.Models.LinkTarget&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-252">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-254">Abrufen einer Liste der Arbeitsbereiche, die der aktuelle Benutzer hat und über Administratorrechte und sind nicht mit einem Azure-Abonnement verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-254">Get a list of workspaces which the current user has administrator privileges and are not associated with an Azure Subscription.</span></span> <span data-ttu-id="ac6a1-255">Der Parameter "subscriptionId" in der Url wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-255">The subscriptionId parameter in the Url is ignored.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroups">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt; ListManagementGroups (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt; ListManagementGroups(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroups(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListManagementGroups (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of ManagementGroup)" />
      <MemberSignature Language="F#" Value="static member ListManagementGroups : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroups (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-257">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-257">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-258">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-258">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-259">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-259">The name of the workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-260">Ruft eine Liste der Verwaltungsgruppen, die mit einem Arbeitsbereich verbunden.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-260">Gets a list of management groups connected to a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListManagementGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt; ListManagementGroupsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt; ListManagementGroupsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroupsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListManagementGroupsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListManagementGroupsAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListManagementGroupsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.ManagementGroup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-261">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-261">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-262">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-262">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-263">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-263">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-264">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-264">The name of the workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-265">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-265">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-266">Ruft eine Liste der Verwaltungsgruppen, die mit einem Arbeitsbereich verbunden.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-266">Gets a list of management groups connected to a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsages">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt; ListUsages (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt; ListUsages(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsages(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListUsages (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String) As IEnumerable(Of UsageMetric)" />
      <MemberSignature Language="F#" Value="static member ListUsages : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsages (operations, resourceGroupName, workspaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-268">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-268">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-269">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-269">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-270">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-270">The name of the workspace.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-271">Ruft eine Liste von nutzungsmetriken für einen Arbeitsbereich angezeigt.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-271">Gets a list of usage metrics for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, workspaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;ListUsagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.OperationalInsights.Models.UsageMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-272">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-273">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-273">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-274">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-274">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-275">Der Name des Arbeitsbereichs.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-275">The name of the workspace.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-276">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-276">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-277">Ruft eine Liste von nutzungsmetriken für einen Arbeitsbereich angezeigt.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-277">Gets a list of usage metrics for a workspace.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResults">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse UpdateSearchResults (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse UpdateSearchResults(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResults(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateSearchResults (operations As IWorkspacesOperations, resourceGroupName As String, workspaceName As String, id As String) As SearchResultsResponse" />
      <MemberSignature Language="F#" Value="static member UpdateSearchResults : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string -&gt; Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResults (operations, resourceGroupName, workspaceName, id)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-278">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-278">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-279">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-279">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-280">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-280">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-281">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-281">Log Analytics workspace name</span></span>
            </param>
        <param name="id">
            <span data-ttu-id="ac6a1-282">Die Id der Suche, die Ergebnisse aktualisiert hat.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-282">The id of the search that will have results updated.</span></span> <span data-ttu-id="ac6a1-283">Sie können die Id aus der Antwort des Aufrufs GetResults abrufen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-283">You can get the id from the response of the GetResults call.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-284">Suchergebnisse für eine gegebene Suchabfrage aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-284">Gets updated search results for a given search query.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSearchResultsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; UpdateSearchResultsAsync (this Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt; UpdateSearchResultsAsync(class Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations operations, string resourceGroupName, string workspaceName, string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResultsAsync(Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSearchResultsAsync : Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;" Usage="Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions.UpdateSearchResultsAsync (operations, resourceGroupName, workspaceName, id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.OperationalInsights</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.OperationalInsights.WorkspacesOperationsExtensions/&lt;UpdateSearchResultsAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.OperationalInsights.Models.SearchResultsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.OperationalInsights.IWorkspacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="workspaceName" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ac6a1-285">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-285">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ac6a1-286">Der Name der abzurufenden Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-286">The name of the resource group to get.</span></span> <span data-ttu-id="ac6a1-287">Der Name wird Groß-/Kleinschreibung nicht beachtet.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-287">The name is case insensitive.</span></span>
            </param>
        <param name="workspaceName">
            <span data-ttu-id="ac6a1-288">Log Analytics Arbeitsbereichsname</span><span class="sxs-lookup"><span data-stu-id="ac6a1-288">Log Analytics workspace name</span></span>
            </param>
        <param name="id">
            <span data-ttu-id="ac6a1-289">Die Id der Suche, die Ergebnisse aktualisiert hat.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-289">The id of the search that will have results updated.</span></span> <span data-ttu-id="ac6a1-290">Sie können die Id aus der Antwort des Aufrufs GetResults abrufen.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-290">You can get the id from the response of the GetResults call.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ac6a1-291">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-291">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ac6a1-292">Suchergebnisse für eine gegebene Suchabfrage aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="ac6a1-292">Gets updated search results for a given search query.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>