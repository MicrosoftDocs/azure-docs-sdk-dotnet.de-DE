<Type Name="RoutesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RoutesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RoutesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RoutesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RoutesOperationsExtensions = class" />
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
            <span data-ttu-id="757c3-101">Erweiterungsmethoden für RoutesOperations.</span><span class="sxs-lookup"><span data-stu-id="757c3-101">Extension methods for RoutesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, routeTableName, routeName, routeParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="routeParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757c3-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="757c3-103">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="757c3-104">Der Name der Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-104">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="757c3-105">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="757c3-105">The name of the route.</span></span>
            </param>
        <param name="routeParameters">
            <span data-ttu-id="757c3-106">Parameter für die Route erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="757c3-106">Parameters supplied to the create or update route operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-108">Erstellt oder aktualisiert eine Route in der angegebenen Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-108">Creates or updates a route in the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, routeTableName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757c3-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="757c3-110">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="757c3-111">Der Name der Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-111">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="757c3-112">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="757c3-112">The name of the route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-114">Löscht die angegebene Route aus einer Routentabelle an.</span><span class="sxs-lookup"><span data-stu-id="757c3-114">Deletes the specified route from a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner routeParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, routeTableName, routeName, routeParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="routeParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757c3-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="757c3-116">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="757c3-117">Der Name der Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-117">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="757c3-118">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="757c3-118">The name of the route.</span></span>
            </param>
        <param name="routeParameters">
            <span data-ttu-id="757c3-119">Parameter für die Route erstellen oder Aktualisieren zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="757c3-119">Parameters supplied to the create or update route operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-121">Erstellt oder aktualisiert eine Route in der angegebenen Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-121">Creates or updates a route in the specified route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.DeleteAsync (operations, resourceGroupName, routeTableName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757c3-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="757c3-123">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="757c3-124">Der Name der Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-124">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="757c3-125">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="757c3-125">The name of the route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-127">Löscht die angegebene Route aus einer Routentabelle an.</span><span class="sxs-lookup"><span data-stu-id="757c3-127">Deletes the specified route from a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, string routeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.GetAsync (operations, resourceGroupName, routeTableName, routeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="routeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757c3-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="757c3-129">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="757c3-130">Der Name der Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-130">The name of the route table.</span></span>
            </param>
        <param name="routeName">
            <span data-ttu-id="757c3-131">Der Name der Route.</span><span class="sxs-lookup"><span data-stu-id="757c3-131">The name of the route.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-133">Ruft die angegebene Route aus einer Routentabelle ab.</span><span class="sxs-lookup"><span data-stu-id="757c3-133">Gets the specified route from a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string resourceGroupName, string routeTableName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListAsync (operations, resourceGroupName, routeTableName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="routeTableName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="757c3-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="757c3-135">The name of the resource group.</span></span>
            </param>
        <param name="routeTableName">
            <span data-ttu-id="757c3-136">Der Name der Routentabelle.</span><span class="sxs-lookup"><span data-stu-id="757c3-136">The name of the route table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-138">Ruft alle Routen in einer Routentabelle ab.</span><span class="sxs-lookup"><span data-stu-id="757c3-138">Gets all routes in a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IRoutesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IRoutesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IRoutesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.RoutesOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.RouteInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IRoutesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="757c3-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="757c3-139">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="757c3-140">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="757c3-140">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="757c3-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="757c3-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="757c3-142">Ruft alle Routen in einer Routentabelle ab.</span><span class="sxs-lookup"><span data-stu-id="757c3-142">Gets all routes in a route table.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>