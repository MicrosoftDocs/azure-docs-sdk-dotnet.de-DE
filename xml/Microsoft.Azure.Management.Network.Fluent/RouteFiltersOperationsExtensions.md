<Type Name="RouteFiltersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFiltersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFiltersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFiltersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFiltersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ee4e0-101">Erweiterungsmethoden für RouteFiltersOperations.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-101">Extension methods for RouteFiltersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-103">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-104">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-104">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="ee4e0-105">Parameter, die der Filtervorgang erstellen oder aktualisieren Route übergeben.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-105">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-107">Erstellt oder aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-107">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-109">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-110">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-110">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-112">Löscht die angegebene Route-Filter.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-112">Deletes the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-114">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-115">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-115">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="ee4e0-116">Parameter, die auf den Updatevorgang für Route Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-116">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-118">Aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-118">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-120">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-121">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-121">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="ee4e0-122">Parameter, die der Filtervorgang erstellen oder aktualisieren Route übergeben.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-122">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-124">Erstellt oder aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-124">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-126">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-126">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-127">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-127">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-129">Löscht die angegebene Route-Filter.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-129">Deletes the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-131">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-132">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-132">The name of the route filter.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="ee4e0-133">Wird erweitert, peering referenzierte express-Route-Bgp-Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-133">Expands referenced express route bgp peering resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-135">Ruft den Filter für die angegebene Route ab.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-135">Gets the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-136">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-138">Ruft alle weiterleitungsfilter in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-138">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-140">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-142">Ruft alle weiterleitungsfilter in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-142">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-143">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ee4e0-144">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-144">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-146">Ruft alle weiterleitungsfilter in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-146">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;ListNextAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-147">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="ee4e0-148">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-148">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-150">Ruft alle weiterleitungsfilter in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-150">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; UpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt; UpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFiltersOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ee4e0-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ee4e0-152">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-152">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="ee4e0-153">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-153">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="ee4e0-154">Parameter, die auf den Updatevorgang für Route Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-154">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="ee4e0-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ee4e0-156">Aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="ee4e0-156">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>