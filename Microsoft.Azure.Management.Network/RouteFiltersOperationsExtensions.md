<Type Name="RouteFiltersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RouteFiltersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RouteFiltersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RouteFiltersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RouteFiltersOperationsExtensions = class" />
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
            <span data-ttu-id="8039c-101">Erweiterungsmethoden für RouteFiltersOperations.</span><span class="sxs-lookup"><span data-stu-id="8039c-101">Extension methods for RouteFiltersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As RouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-103">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-104">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-104">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-105">Parameter, die der Filtervorgang erstellen oder aktualisieren Route übergeben.</span><span class="sxs-lookup"><span data-stu-id="8039c-105">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-106">Erstellt oder aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-106">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-108">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-109">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-109">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-110">Parameter, die der Filtervorgang erstellen oder aktualisieren Route übergeben.</span><span class="sxs-lookup"><span data-stu-id="8039c-110">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-112">Erstellt oder aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-112">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDelete (operations, resourceGroupName, routeFilterName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-114">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-115">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-115">The name of the route filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-116">Löscht die angegebene Route-Filter.</span><span class="sxs-lookup"><span data-stu-id="8039c-116">Deletes the specified route filter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-118">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-119">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-119">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-121">Löscht die angegebene Route-Filter.</span><span class="sxs-lookup"><span data-stu-id="8039c-121">Deletes the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter BeginUpdate (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter BeginUpdate(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As PatchRouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdate (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-123">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-124">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-124">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-125">Parameter, die auf den Updatevorgang für Route Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="8039c-125">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-126">Aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-126">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;BeginUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-128">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-129">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-129">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-130">Parameter, die auf den Updatevorgang für Route Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="8039c-130">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-132">Aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-132">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter CreateOrUpdate (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter CreateOrUpdate(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As RouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-134">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-135">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-135">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-136">Parameter, die der Filtervorgang erstellen oder aktualisieren Route übergeben.</span><span class="sxs-lookup"><span data-stu-id="8039c-136">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-137">Erstellt oder aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-137">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-139">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-140">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-140">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-141">Parameter, die der Filtervorgang erstellen oder aktualisieren Route übergeben.</span><span class="sxs-lookup"><span data-stu-id="8039c-141">Parameters supplied to the create or update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-143">Erstellt oder aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-143">Creates or updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Delete (operations, resourceGroupName, routeFilterName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-145">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-146">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-146">The name of the route filter.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-147">Löscht die angegebene Route-Filter.</span><span class="sxs-lookup"><span data-stu-id="8039c-147">Deletes the specified route filter.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeFilterName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-149">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-150">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-150">The name of the route filter.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-152">Löscht die angegebene Route-Filter.</span><span class="sxs-lookup"><span data-stu-id="8039c-152">Deletes the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter Get (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter Get(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Get(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, Optional expand As String = null) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Get (operations, resourceGroupName, routeFilterName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-154">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-155">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-155">The name of the route filter.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8039c-156">Wird erweitert, peering referenzierte express-Route-Bgp-Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="8039c-156">Expands referenced express route bgp peering resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-157">Ruft den Filter für die angegebene Route ab.</span><span class="sxs-lookup"><span data-stu-id="8039c-157">Gets the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; GetAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; GetAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.GetAsync (operations, resourceGroupName, routeFilterName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-159">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-160">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-160">The name of the route filter.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="8039c-161">Wird erweitert, peering referenzierte express-Route-Bgp-Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="8039c-161">Expands referenced express route bgp peering resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-163">Ruft den Filter für die angegebene Route ab.</span><span class="sxs-lookup"><span data-stu-id="8039c-163">Gets the specified route filter.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; List (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; List(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.List(Microsoft.Azure.Management.Network.IRouteFiltersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRouteFiltersOperations) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IRouteFiltersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-164">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-165">Ruft alle weiterleitungsfilter in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8039c-165">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-166">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-168">Ruft alle weiterleitungsfilter in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8039c-168">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroup (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroup(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IRouteFiltersOperations, resourceGroupName As String) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-170">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-170">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-171">Ruft alle weiterleitungsfilter in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-171">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-173">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-175">Ruft alle weiterleitungsfilter in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-175">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IRouteFiltersOperations, nextPageLink As String) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-176">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8039c-177">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8039c-177">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-178">Ruft alle weiterleitungsfilter in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-178">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8039c-180">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8039c-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-182">Ruft alle weiterleitungsfilter in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-182">Gets all route filters in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListNext (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; ListNext(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRouteFiltersOperations, nextPageLink As String) As IPage(Of RouteFilter)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8039c-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8039c-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-185">Ruft alle weiterleitungsfilter in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8039c-185">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8039c-187">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8039c-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-189">Ruft alle weiterleitungsfilter in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8039c-189">Gets all route filters in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.RouteFilter Update (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.RouteFilter Update(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Update(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IRouteFiltersOperations, resourceGroupName As String, routeFilterName As String, routeFilterParameters As PatchRouteFilter) As RouteFilter" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter -&gt; Microsoft.Azure.Management.Network.Models.RouteFilter" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.Update (operations, resourceGroupName, routeFilterName, routeFilterParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-191">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-191">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-192">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-192">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-193">Parameter, die auf den Updatevorgang für Route Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="8039c-193">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-194">Aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-194">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt; UpdateAsync (this Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.RouteFilter&gt; UpdateAsync(class Microsoft.Azure.Management.Network.IRouteFiltersOperations operations, string resourceGroupName, string routeFilterName, class Microsoft.Azure.Management.Network.Models.PatchRouteFilter routeFilterParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Network.IRouteFiltersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.PatchRouteFilter,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Network.IRouteFiltersOperations * string * string * Microsoft.Azure.Management.Network.Models.PatchRouteFilter * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;" Usage="Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions.UpdateAsync (operations, resourceGroupName, routeFilterName, routeFilterParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.RouteFiltersOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.RouteFilter&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IRouteFiltersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeFilterName" Type="System.String" />
        <Parameter Name="routeFilterParameters" Type="Microsoft.Azure.Management.Network.Models.PatchRouteFilter" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8039c-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8039c-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8039c-196">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-196">The name of the resource group.</span></span>
            </param>
        <param name="routeFilterName">
            <span data-ttu-id="8039c-197">Der Name des Filters Route.</span><span class="sxs-lookup"><span data-stu-id="8039c-197">The name of the route filter.</span></span>
            </param>
        <param name="routeFilterParameters">
            <span data-ttu-id="8039c-198">Parameter, die auf den Updatevorgang für Route Filter angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="8039c-198">Parameters supplied to the update route filter operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8039c-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8039c-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8039c-200">Aktualisiert einen Routefilter in einer angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8039c-200">Updates a route filter in a specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>