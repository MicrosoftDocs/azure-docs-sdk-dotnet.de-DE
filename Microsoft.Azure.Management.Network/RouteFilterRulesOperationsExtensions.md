<Type Name="RouteFilterRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFilterRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFilterRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFilterRulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3649c-101">Erweiterungsmethoden für RouteFilterRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="3649c-101">Extension methods for RouteFilterRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilterRule BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilterRule BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilterRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String, routeFilterRuleParameters As RouteFilterRule) As RouteFilterRule" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.RouteFilterRule -&gt; Microsoft.Azure.Management.Network.Models.RouteFilterRule" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilterRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilterRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-103">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-104">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-104">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-105">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-105">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-106">Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="3649c-106">Parameters supplied to the create or update route filter rule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-107">Erstellt oder aktualisiert eine Route im Routefilter angegebenen.</span><span class="sxs-lookup"><span data-stu-id="3649c-107">Creates or updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilterRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.RouteFilterRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilterRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-109">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-110">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-110">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-111">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-111">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-112">Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="3649c-112">Parameters supplied to the create or update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-114">Erstellt oder aktualisiert eine Route im Routefilter angegebenen.</span><span class="sxs-lookup"><span data-stu-id="3649c-114">Creates or updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginDelete (operations, resourceGroupName, routeFilterName, ruleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-116">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-117">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-117">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-118">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="3649c-118">The name of the rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-119">Löscht die angegebene Regel aus einem Routefilter an.</span><span class="sxs-lookup"><span data-stu-id="3649c-119">Deletes the specified rule from a route filter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-121">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-122">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-122">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-123">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="3649c-123">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-125">Löscht die angegebene Regel aus einem Routefilter an.</span><span class="sxs-lookup"><span data-stu-id="3649c-125">Deletes the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilterRule BeginUpdate (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilterRule BeginUpdate(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String, routeFilterRuleParameters As PatchRouteFilterRule) As RouteFilterRule" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule -&gt; Microsoft.Azure.Management.Network.Models.RouteFilterRule" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginUpdate (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilterRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-127">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-128">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-128">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-129">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-129">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-130">Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3649c-130">Parameters supplied to the update route filter rule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-131">Aktualisiert eine Route im Routefilter angegebenen an.</span><span class="sxs-lookup"><span data-stu-id="3649c-131">Updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;BeginUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-133">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-134">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-134">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-135">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-135">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-136">Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3649c-136">Parameters supplied to the update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-138">Aktualisiert eine Route im Routefilter angegebenen an.</span><span class="sxs-lookup"><span data-stu-id="3649c-138">Updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilterRule CreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilterRule CreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilterRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String, routeFilterRuleParameters As RouteFilterRule) As RouteFilterRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.RouteFilterRule -&gt; Microsoft.Azure.Management.Network.Models.RouteFilterRule" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilterRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilterRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-140">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-141">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-141">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-142">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-142">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-143">Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="3649c-143">Parameters supplied to the create or update route filter rule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-144">Erstellt oder aktualisiert eine Route im Routefilter angegebenen.</span><span class="sxs-lookup"><span data-stu-id="3649c-144">Creates or updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.RouteFilterRule routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilterRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.RouteFilterRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilterRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-146">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-146">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-147">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-147">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-148">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-148">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-149">Parameter für das Erstellen oder aktualisieren Route Regel Filtervorgang bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="3649c-149">Parameters supplied to the create or update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-150">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-150">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-151">Erstellt oder aktualisiert eine Route im Routefilter angegebenen.</span><span class="sxs-lookup"><span data-stu-id="3649c-151">Creates or updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.Delete (operations, resourceGroupName, routeFilterName, ruleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-152">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-152">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-153">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-153">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-154">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-154">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-155">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="3649c-155">The name of the rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-156">Löscht die angegebene Regel aus einem Routefilter an.</span><span class="sxs-lookup"><span data-stu-id="3649c-156">Deletes the specified rule from a route filter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-158">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-158">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-159">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-159">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-160">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="3649c-160">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-162">Löscht die angegebene Regel aus einem Routefilter an.</span><span class="sxs-lookup"><span data-stu-id="3649c-162">Deletes the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilterRule Get (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilterRule Get(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.Get(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String) As RouteFilterRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.RouteFilterRule" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.Get (operations, resourceGroupName, routeFilterName, ruleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilterRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-164">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-165">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-165">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-166">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="3649c-166">The name of the rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-167">Ruft die angegebene Regel aus einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="3649c-167">Gets the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; GetAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; GetAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-169">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-169">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-170">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-170">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-171">Der Name der Regel.</span><span class="sxs-lookup"><span data-stu-id="3649c-171">The name of the rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-173">Ruft die angegebene Regel aus einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="3649c-173">Gets the specified rule from a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilter">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; ListByRouteFilter (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; ListByRouteFilter(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilter(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByRouteFilter (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String) As IPage(Of RouteFilterRule)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilter : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilter (operations, resourceGroupName, routeFilterName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-174">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-175">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-175">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-176">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-176">The name of the route filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-177">Ruft alle RouteFilterRules in einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="3649c-177">Gets all RouteFilterRules in a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt; ListByRouteFilterAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt; ListByRouteFilterAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilterAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-179">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-179">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-180">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-180">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-182">Ruft alle RouteFilterRules in einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="3649c-182">Gets all RouteFilterRules in a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; ListByRouteFilterNext (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; ListByRouteFilterNext(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilterNext(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByRouteFilterNext (operations As IRouteFilterRulesOperations, nextPageLink As String) As IPage(Of RouteFilterRule)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterNext : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilterNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3649c-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3649c-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-185">Ruft alle RouteFilterRules in einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="3649c-185">Gets all RouteFilterRules in a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByRouteFilterNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt; ListByRouteFilterNextAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt; ListByRouteFilterNextAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByRouteFilterNextAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.ListByRouteFilterNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;ListByRouteFilterNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3649c-187">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3649c-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-189">Ruft alle RouteFilterRules in einem Routefilter ab.</span><span class="sxs-lookup"><span data-stu-id="3649c-189">Gets all RouteFilterRules in a route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilterRule Update (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilterRule Update(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.Update(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IRouteFilterRulesOperations, resourceGroupName As String, routeFilterName As String, ruleName As String, routeFilterRuleParameters As PatchRouteFilterRule) As RouteFilterRule" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule -&gt; Microsoft.Azure.Management.Network.Models.RouteFilterRule" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.Update (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilterRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-191">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-191">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-192">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-192">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-193">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-193">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-194">Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3649c-194">Parameters supplied to the update route filter rule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-195">Aktualisiert eine Route im Routefilter angegebenen an.</span><span class="sxs-lookup"><span data-stu-id="3649c-195">Updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; UpdateAsync (this Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt; UpdateAsync(class Microsoft.Azure.Management.Network.IRouteFilterRulesOperations operations, string resourceGroupName, string routeFilterName, string ruleName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule routeFilterRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.IRouteFilterRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.IRouteFilterRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;" Usage="Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, ruleName, routeFilterRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFilterRulesOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilterRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFilterRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="routeFilterRuleParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilterRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3649c-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3649c-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3649c-197">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3649c-197">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="3649c-198">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-198">The name of the route filter.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="3649c-199">Der Name der Filterregel für Route.</span><span class="sxs-lookup"><span data-stu-id="3649c-199">The name of the route filter rule.</span></span>
            </param>
        <param name="routeFilterRuleParameters">
            <span data-ttu-id="3649c-200">Parameter, die auf den Updatevorgang Route Filter Regel bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="3649c-200">Parameters supplied to the update route filter rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3649c-201">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3649c-201">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3649c-202">Aktualisiert eine Route im Routefilter angegebenen an.</span><span class="sxs-lookup"><span data-stu-id="3649c-202">Updates a route in the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>