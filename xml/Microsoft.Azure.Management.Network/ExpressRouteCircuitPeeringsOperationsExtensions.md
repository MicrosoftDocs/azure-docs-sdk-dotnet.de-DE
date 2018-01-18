<Type Name="ExpressRouteCircuitPeeringsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitPeeringsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitPeeringsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitPeeringsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitPeeringsOperationsExtensions = class" />
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
            <span data-ttu-id="c8aba-101">Erweiterungsmethoden für ExpressRouteCircuitPeeringsOperations.</span><span class="sxs-lookup"><span data-stu-id="c8aba-101">Extension methods for ExpressRouteCircuitPeeringsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IExpressRouteCircuitPeeringsOperations, resourceGroupName As String, circuitName As String, peeringName As String, peeringParameters As ExpressRouteCircuitPeering) As ExpressRouteCircuitPeering" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, circuitName, peeringName, peeringParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="peeringParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-104">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-104">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-105">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-105">The name of the peering.</span></span>
            </param>
        <param name="peeringParameters">
            <span data-ttu-id="c8aba-106">Parameter zum Erstellen oder aktualisieren express Route Circuit peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="c8aba-106">Parameters supplied to the create or update express route circuit peering operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-107">Erstellt oder aktualisiert ein peering in der angegebenen express-Route-Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="c8aba-107">Creates or updates a peering in the specified express route circuits.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, peeringName, peeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="peeringParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-109">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-110">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-110">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-111">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-111">The name of the peering.</span></span>
            </param>
        <param name="peeringParameters">
            <span data-ttu-id="c8aba-112">Parameter zum Erstellen oder aktualisieren express Route Circuit peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="c8aba-112">Parameters supplied to the create or update express route circuit peering operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-114">Erstellt oder aktualisiert ein peering in der angegebenen express-Route-Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="c8aba-114">Creates or updates a peering in the specified express route circuits.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IExpressRouteCircuitPeeringsOperations, resourceGroupName As String, circuitName As String, peeringName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginDelete (operations, resourceGroupName, circuitName, peeringName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-116">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-117">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-117">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-118">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-118">The name of the peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-119">Löscht das angegebene peering mit der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-119">Deletes the specified peering from the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-121">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-122">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-122">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-123">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-123">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-125">Löscht das angegebene peering mit der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-125">Deletes the specified peering from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering CreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering CreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IExpressRouteCircuitPeeringsOperations, resourceGroupName As String, circuitName As String, peeringName As String, peeringParameters As ExpressRouteCircuitPeering) As ExpressRouteCircuitPeering" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, circuitName, peeringName, peeringParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="peeringParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-127">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-128">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-128">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-129">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-129">The name of the peering.</span></span>
            </param>
        <param name="peeringParameters">
            <span data-ttu-id="c8aba-130">Parameter zum Erstellen oder aktualisieren express Route Circuit peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="c8aba-130">Parameters supplied to the create or update express route circuit peering operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-131">Erstellt oder aktualisiert ein peering in der angegebenen express-Route-Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="c8aba-131">Creates or updates a peering in the specified express route circuits.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering peeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, peeringName, peeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="peeringParameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-133">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-134">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-134">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-135">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-135">The name of the peering.</span></span>
            </param>
        <param name="peeringParameters">
            <span data-ttu-id="c8aba-136">Parameter zum Erstellen oder aktualisieren express Route Circuit peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="c8aba-136">Parameters supplied to the create or update express route circuit peering operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-138">Erstellt oder aktualisiert ein peering in der angegebenen express-Route-Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="c8aba-138">Creates or updates a peering in the specified express route circuits.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IExpressRouteCircuitPeeringsOperations, resourceGroupName As String, circuitName As String, peeringName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.Delete (operations, resourceGroupName, circuitName, peeringName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-140">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-141">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-141">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-142">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-142">The name of the peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-143">Löscht das angegebene peering mit der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-143">Deletes the specified peering from the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-145">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-146">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-146">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-147">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-147">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-149">Löscht das angegebene peering mit der angegebenen express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-149">Deletes the specified peering from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering Get (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering Get(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExpressRouteCircuitPeeringsOperations, resourceGroupName As String, circuitName As String, peeringName As String) As ExpressRouteCircuitPeering" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.Get (operations, resourceGroupName, circuitName, peeringName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-151">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-152">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-152">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-153">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-153">The name of the peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-154">Ruft die angegebene Autorisierung aus der angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="c8aba-154">Gets the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; GetAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; GetAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-156">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-157">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-157">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="c8aba-158">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="c8aba-158">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-160">Ruft die angegebene Autorisierung aus der angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="c8aba-160">Gets the specified authorization from the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; List (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; List(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.List(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IExpressRouteCircuitPeeringsOperations, resourceGroupName As String, circuitName As String) As IPage(Of ExpressRouteCircuitPeering)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.List (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-162">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-162">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-163">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-163">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-164">Ruft alle kann in einer angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="c8aba-164">Gets all peerings in a specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.ListAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c8aba-166">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="c8aba-166">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="c8aba-167">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="c8aba-167">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-169">Ruft alle kann in einer angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="c8aba-169">Gets all peerings in a specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; ListNext (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt; ListNext(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IExpressRouteCircuitPeeringsOperations, nextPageLink As String) As IPage(Of ExpressRouteCircuitPeering)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c8aba-171">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c8aba-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-172">Ruft alle kann in einer angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="c8aba-172">Gets all peerings in a specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitPeeringsOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitPeeringsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c8aba-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c8aba-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="c8aba-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="c8aba-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c8aba-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c8aba-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c8aba-176">Ruft alle kann in einer angegebenen express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="c8aba-176">Gets all peerings in a specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>