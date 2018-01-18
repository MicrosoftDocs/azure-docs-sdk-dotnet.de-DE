<Type Name="ExpressRouteCircuitAuthorizationsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitAuthorizationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitAuthorizationsOperationsExtensions = class" />
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
            <span data-ttu-id="23b86-101">Erweiterungsmethoden für ExpressRouteCircuitAuthorizationsOperations.</span><span class="sxs-lookup"><span data-stu-id="23b86-101">Extension methods for ExpressRouteCircuitAuthorizationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23b86-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="23b86-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="23b86-104">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-104">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="23b86-105">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="23b86-105">The name of the authorization.</span></span>
            </param>
        <param name="authorizationParameters">
            <span data-ttu-id="23b86-106">Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="23b86-106">Parameters supplied to the create or update express route circuit authorization operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-108">Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-108">Creates or updates an authorization in the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23b86-110">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="23b86-110">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="23b86-111">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-111">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="23b86-112">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="23b86-112">The name of the authorization.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-114">Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="23b86-114">Deletes the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner authorizationParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23b86-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="23b86-116">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="23b86-117">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-117">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="23b86-118">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="23b86-118">The name of the authorization.</span></span>
            </param>
        <param name="authorizationParameters">
            <span data-ttu-id="23b86-119">Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="23b86-119">Parameters supplied to the create or update express route circuit authorization operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-121">Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-121">Creates or updates an authorization in the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23b86-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="23b86-123">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="23b86-124">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-124">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="23b86-125">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="23b86-125">The name of the authorization.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-127">Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="23b86-127">Deletes the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23b86-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="23b86-129">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="23b86-130">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-130">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="23b86-131">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="23b86-131">The name of the authorization.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-133">Ruft die angegebene Autorisierung aus der angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="23b86-133">Gets the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="23b86-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="23b86-135">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="23b86-136">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="23b86-136">The name of the circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-138">Ruft alle autorisierungen in einer express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="23b86-138">Gets all authorizations in an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;ListNextAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitAuthorizationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="23b86-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="23b86-139">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="23b86-140">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="23b86-140">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="23b86-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="23b86-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="23b86-142">Ruft alle autorisierungen in einer express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="23b86-142">Gets all authorizations in an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>