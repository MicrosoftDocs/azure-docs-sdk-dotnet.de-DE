<Type Name="RouteFilterRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFilterRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFilterRulesOperationsExtensions = class" />
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
            <span data-ttu-id="2e7fe-101">Erweiterungsmethoden für RouteFilterRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-101">Extension methods for RouteFilterRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-103">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-104">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-104">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-105">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-105">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="2e7fe-106">Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-106">Parameters supplied to the create or update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-108">Erstellt oder aktualisiert eine Route im Routefilter angegebenen.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-108">Creates or updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-110">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-111">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-111">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-112">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-112">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-114">Löscht die angegebene Regel aus einem Routefilter an.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-114">Deletes the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-116">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-117">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-117">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-118">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-118">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="2e7fe-119">Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-119">Parameters supplied to the update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-121">Aktualisiert eine Route im Routefilter angegebenen an.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-121">Updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-123">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-124">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-124">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-125">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-125">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="2e7fe-126">Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-126">Parameters supplied to the create or update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-128">Erstellt oder aktualisiert eine Route im Routefilter angegebenen.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-128">Creates or updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-130">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-130">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-131">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-131">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-132">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-132">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-134">Löscht die angegebene Regel aus einem Routefilter an.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-134">Deletes the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-136">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-137">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-137">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-138">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-138">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-140">Ruft die angegebene Regel aus einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-140">Gets the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-142">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-143">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-143">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-145">Ruft alle RouteFilterRules in einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-145">Gets all RouteFilterRules in a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt; ListByRouteFilterNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterNextAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterNextAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-146">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2e7fe-147">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-147">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-149">Ruft alle RouteFilterRules in einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-149">Gets all RouteFilterRules in a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; UpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt; UpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RouteFilterRulesOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.PatchRouteFilterRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2e7fe-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2e7fe-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-151">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="2e7fe-152">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-152">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="2e7fe-153">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-153">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="2e7fe-154">Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-154">Parameters supplied to the update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2e7fe-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2e7fe-156">Aktualisiert eine Route im Routefilter angegebenen an.</span><span class="sxs-lookup"><span data-stu-id="2e7fe-156">Updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>