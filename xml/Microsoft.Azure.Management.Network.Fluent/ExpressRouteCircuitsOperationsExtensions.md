<Type Name="ExpressRouteCircuitsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsOperationsExtensions = class" />
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
            <span data-ttu-id="fbaee-101">Erweiterungsmethoden für ExpressRouteCircuitsOperations.</span><span class="sxs-lookup"><span data-stu-id="fbaee-101">Extension methods for ExpressRouteCircuitsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-104">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-104">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbaee-105">Parameter zum Erstellen oder aktualisieren express Route Circuit Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="fbaee-105">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-107">Erstellt oder aktualisiert eine express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-107">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-109">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-110">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-110">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-112">Löscht die angegebene express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="fbaee-112">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; BeginListArpTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; BeginListArpTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListArpTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListArpTableAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-114">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-115">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-115">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-116">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-116">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fbaee-117">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="fbaee-117">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-118">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-118">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-119">Ruft die derzeit angekündigte ARP-Tabelle der express-Route-Verbindung in einer Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fbaee-119">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; BeginListRoutesTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; BeginListRoutesTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-121">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-122">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-122">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-123">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-123">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fbaee-124">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="fbaee-124">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-125">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-125">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-126">Ruft die derzeit angekündigte Routen-Tabelle, die die express-Route-Verbindung in einer Ressourcengruppe zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-126">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; BeginListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; BeginListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableSummaryAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-128">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-129">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-129">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-130">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-130">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fbaee-131">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="fbaee-131">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-133">Ruft die derzeit angekündigte Routen Zusammenfassung der express-Route-Verbindung in einer Ressourcengruppe zugeordnet Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-133">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-135">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-136">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-136">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="fbaee-137">Parameter zum Erstellen oder aktualisieren express Route Circuit Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="fbaee-137">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-139">Erstellt oder aktualisiert eine express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-139">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-141">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-141">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-142">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-142">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-144">Löscht die angegebene express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="fbaee-144">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-146">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-146">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-147">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-147">The name of express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-149">Ruft Informationen über die angegebene express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-149">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetPeeringStatsAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetPeeringStatsAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPeeringStatsAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;GetPeeringStatsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-151">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-152">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-152">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-153">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-153">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-155">Ruft alle Statistiken aus einer express-Route-Verbindung in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-155">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetStatsAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt; GetStatsAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatsAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;GetStatsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-157">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-157">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-158">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-158">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-160">Ruft alle Statistiken aus einer express-Route-Verbindung in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-160">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-161">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-163">Ruft die express-Route-Verbindungen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-163">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-164">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fbaee-165">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fbaee-165">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-167">Ruft die express-Route-Verbindungen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-167">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; ListArpTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt; ListArpTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListArpTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListArpTableAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsArpTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-169">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-169">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-170">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-170">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-171">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-171">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fbaee-172">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="fbaee-172">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-174">Ruft die derzeit angekündigte ARP-Tabelle der express-Route-Verbindung in einer Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fbaee-174">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-176">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-176">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-178">Ruft die express-Route-Verbindungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-178">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-179">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="fbaee-180">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="fbaee-180">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-182">Ruft die express-Route-Verbindungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-182">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; ListRoutesTableAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt; ListRoutesTableAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-184">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-184">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-185">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-185">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-186">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-186">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fbaee-187">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="fbaee-187">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-189">Ruft die derzeit angekündigte Routen-Tabelle, die die express-Route-Verbindung in einer Ressourcengruppe zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-189">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; ListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt; ListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableSummaryAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitsRoutesTableSummaryListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="fbaee-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="fbaee-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="fbaee-191">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="fbaee-191">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="fbaee-192">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="fbaee-192">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="fbaee-193">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="fbaee-193">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="fbaee-194">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="fbaee-194">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fbaee-195">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fbaee-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fbaee-196">Ruft die derzeit angekündigte Routen Zusammenfassung der express-Route-Verbindung in einer Ressourcengruppe zugeordnet Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="fbaee-196">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>