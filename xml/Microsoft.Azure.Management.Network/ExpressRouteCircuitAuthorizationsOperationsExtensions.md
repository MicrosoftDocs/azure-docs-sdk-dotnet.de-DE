<Type Name="ExpressRouteCircuitAuthorizationsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitAuthorizationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitAuthorizationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitAuthorizationsOperationsExtensions = class" />
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
            <span data-ttu-id="32407-101">Erweiterungsmethoden für ExpressRouteCircuitAuthorizationsOperations.</span><span class="sxs-lookup"><span data-stu-id="32407-101">Extension methods for ExpressRouteCircuitAuthorizationsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IExpressRouteCircuitAuthorizationsOperations, resourceGroupName As String, circuitName As String, authorizationName As String, authorizationParameters As ExpressRouteCircuitAuthorization) As ExpressRouteCircuitAuthorization" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-104">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-104">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-105">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-105">The name of the authorization.</span></span>
            </param>
        <param name="authorizationParameters">
            <span data-ttu-id="32407-106">Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="32407-106">Parameters supplied to the create or update express route circuit authorization operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-107">Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-107">Creates or updates an authorization in the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-109">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-110">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-110">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-111">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-111">The name of the authorization.</span></span>
            </param>
        <param name="authorizationParameters">
            <span data-ttu-id="32407-112">Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="32407-112">Parameters supplied to the create or update express route circuit authorization operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-114">Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-114">Creates or updates an authorization in the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IExpressRouteCircuitAuthorizationsOperations, resourceGroupName As String, circuitName As String, authorizationName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDelete (operations, resourceGroupName, circuitName, authorizationName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-116">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-117">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-117">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-118">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-118">The name of the authorization.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-119">Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="32407-119">Deletes the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-121">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-122">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-122">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-123">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-123">The name of the authorization.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-125">Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="32407-125">Deletes the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization CreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization CreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IExpressRouteCircuitAuthorizationsOperations, resourceGroupName As String, circuitName As String, authorizationName As String, authorizationParameters As ExpressRouteCircuitAuthorization) As ExpressRouteCircuitAuthorization" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-127">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-128">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-128">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-129">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-129">The name of the authorization.</span></span>
            </param>
        <param name="authorizationParameters">
            <span data-ttu-id="32407-130">Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="32407-130">Parameters supplied to the create or update express route circuit authorization operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-131">Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-131">Creates or updates an authorization in the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization authorizationParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, authorizationName, authorizationParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="authorizationParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-133">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-134">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-134">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-135">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-135">The name of the authorization.</span></span>
            </param>
        <param name="authorizationParameters">
            <span data-ttu-id="32407-136">Parameter zum Erstellen oder aktualisieren express Route Circuit Autorisierung Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="32407-136">Parameters supplied to the create or update express route circuit authorization operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-138">Erstellt oder aktualisiert eine Autorisierung in der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-138">Creates or updates an authorization in the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IExpressRouteCircuitAuthorizationsOperations, resourceGroupName As String, circuitName As String, authorizationName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.Delete (operations, resourceGroupName, circuitName, authorizationName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-140">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-141">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-141">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-142">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-142">The name of the authorization.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-143">Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="32407-143">Deletes the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-145">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-146">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-146">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-147">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-147">The name of the authorization.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-149">Löscht die angegebene Autorisierung mit der angegebenen express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="32407-149">Deletes the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization Get (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization Get(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExpressRouteCircuitAuthorizationsOperations, resourceGroupName As String, circuitName As String, authorizationName As String) As ExpressRouteCircuitAuthorization" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.Get (operations, resourceGroupName, circuitName, authorizationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-151">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-152">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-152">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-153">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-153">The name of the authorization.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-154">Ruft die angegebene Autorisierung aus der angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="32407-154">Gets the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; GetAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; GetAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, string authorizationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, authorizationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="authorizationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-156">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-157">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-157">The name of the express route circuit.</span></span>
            </param>
        <param name="authorizationName">
            <span data-ttu-id="32407-158">Der Name der Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="32407-158">The name of the authorization.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-160">Ruft die angegebene Autorisierung aus der angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="32407-160">Gets the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; List (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; List(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.List(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IExpressRouteCircuitAuthorizationsOperations, resourceGroupName As String, circuitName As String) As IPage(Of ExpressRouteCircuitAuthorization)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.List (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-162">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-162">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-163">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-163">The name of the circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-164">Ruft alle autorisierungen in einer express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="32407-164">Gets all authorizations in an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="32407-166">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="32407-166">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="32407-167">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="32407-167">The name of the circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-169">Ruft alle autorisierungen in einer express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="32407-169">Gets all authorizations in an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; ListNext (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt; ListNext(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IExpressRouteCircuitAuthorizationsOperations, nextPageLink As String) As IPage(Of ExpressRouteCircuitAuthorization)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="32407-171">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="32407-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-172">Ruft alle autorisierungen in einer express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="32407-172">Gets all authorizations in an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitAuthorizationsOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitAuthorization&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitAuthorizationsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="32407-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="32407-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="32407-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="32407-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="32407-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="32407-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="32407-176">Ruft alle autorisierungen in einer express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="32407-176">Gets all authorizations in an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>