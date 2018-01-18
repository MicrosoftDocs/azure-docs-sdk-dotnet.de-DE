<Type Name="ExpressRouteCircuitsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ExpressRouteCircuitsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ExpressRouteCircuitsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitsOperationsExtensions = class" />
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
            <span data-ttu-id="8a10f-101">Erweiterungsmethoden für ExpressRouteCircuitsOperations.</span><span class="sxs-lookup"><span data-stu-id="8a10f-101">Extension methods for ExpressRouteCircuitsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As ExpressRouteCircuit) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-103">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-104">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-104">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-105">Parameter zum Erstellen oder aktualisieren express Route Circuit Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-105">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-106">Erstellt oder aktualisiert eine express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-106">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-108">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-109">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-109">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-110">Parameter zum Erstellen oder aktualisieren express Route Circuit Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-110">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-112">Erstellt oder aktualisiert eine express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-112">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDelete (operations, resourceGroupName, circuitName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-114">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-115">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-115">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-116">Löscht die angegebene express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="8a10f-116">Deletes the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-118">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-119">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-119">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-121">Löscht die angegebene express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="8a10f-121">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult BeginListArpTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult BeginListArpTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListArpTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsArpTableListResult" />
      <MemberSignature Language="F#" Value="static member BeginListArpTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-123">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-124">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-124">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-125">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-125">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-126">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-126">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-127">Ruft die derzeit angekündigte ARP-Tabelle der express-Route-Verbindung in einer Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8a10f-127">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; BeginListArpTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; BeginListArpTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListArpTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListArpTableAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-128">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-129">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-129">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-130">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-130">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-131">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-131">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-132">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-132">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-134">Ruft die derzeit angekündigte ARP-Tabelle der express-Route-Verbindung in einer Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8a10f-134">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult BeginListRoutesTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult BeginListRoutesTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListRoutesTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableListResult" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-136">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-136">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-137">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-137">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-138">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-138">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-139">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-139">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-140">Ruft die derzeit angekündigte Routen-Tabelle, die die express-Route-Verbindung in einer Ressourcengruppe zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-140">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; BeginListRoutesTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; BeginListRoutesTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-142">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-143">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-143">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-144">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-144">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-145">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-145">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-147">Ruft die derzeit angekündigte Routen-Tabelle, die die express-Route-Verbindung in einer Ressourcengruppe zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-147">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult BeginListRoutesTableSummary (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult BeginListRoutesTableSummary(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummary(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginListRoutesTableSummary (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableSummaryListResult" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableSummary : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummary (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-149">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-150">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-150">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-151">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-151">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-152">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-152">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-153">Ruft die derzeit angekündigte Routen Zusammenfassung der express-Route-Verbindung in einer Ressourcengruppe zugeordnet Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-153">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; BeginListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; BeginListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginListRoutesTableSummaryAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-155">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-155">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-156">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-156">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-157">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-157">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-158">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-158">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-160">Ruft die derzeit angekündigte Routen Zusammenfassung der express-Route-Verbindung in einer Ressourcengruppe zugeordnet Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-160">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginUpdateTags (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit BeginUpdateTags(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As TagsObject) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-162">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-162">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-163">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-163">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-164">Parameter, die zum Aktualisieren der express-Route-Circuit-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-164">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-165">Aktualisiert eine express-Route-Circuit-Tags.</span><span class="sxs-lookup"><span data-stu-id="8a10f-165">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-167">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-167">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-168">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-168">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-169">Parameter, die zum Aktualisieren der express-Route-Circuit-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-169">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-171">Aktualisiert eine express-Route-Circuit-Tags.</span><span class="sxs-lookup"><span data-stu-id="8a10f-171">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit CreateOrUpdate (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit CreateOrUpdate(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As ExpressRouteCircuit) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-173">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-174">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-174">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-175">Parameter zum Erstellen oder aktualisieren express Route Circuit Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-175">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-176">Erstellt oder aktualisiert eine express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-176">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-178">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-178">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-179">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-179">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-180">Parameter zum Erstellen oder aktualisieren express Route Circuit Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-180">Parameters supplied to the create or update express route circuit operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-182">Erstellt oder aktualisiert eine express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-182">Creates or updates an express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Delete (operations, resourceGroupName, circuitName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-184">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-184">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-185">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-185">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-186">Löscht die angegebene express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="8a10f-186">Deletes the specified express route circuit.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.DeleteAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-188">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-188">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-189">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-189">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-191">Löscht die angegebene express-Route-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="8a10f-191">Deletes the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit Get (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit Get(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.Get (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-193">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-193">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-194">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-194">The name of express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-195">Ruft Informationen über die angegebene express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-195">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; GetAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; GetAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-197">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-197">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-198">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-198">The name of express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-200">Ruft Informationen über die angegebene express-Route-Verbindung ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-200">Gets information about the specified express route circuit.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetPeeringStats (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetPeeringStats(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStats(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetPeeringStats (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String) As ExpressRouteCircuitStats" />
      <MemberSignature Language="F#" Value="static member GetPeeringStats : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStats (operations, resourceGroupName, circuitName, peeringName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-201">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-202">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-202">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-203">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-203">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-204">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-204">The name of the peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-205">Ruft alle Statistiken aus einer express-Route-Verbindung in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-205">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPeeringStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetPeeringStatsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetPeeringStatsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPeeringStatsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetPeeringStatsAsync (operations, resourceGroupName, circuitName, peeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;GetPeeringStatsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-207">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-207">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-208">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-208">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-209">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-209">The name of the peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-211">Ruft alle Statistiken aus einer express-Route-Verbindung in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-211">Gets all stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStats">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetStats (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats GetStats(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStats(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetStats (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String) As ExpressRouteCircuitStats" />
      <MemberSignature Language="F#" Value="static member GetStats : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStats (operations, resourceGroupName, circuitName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-213">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-213">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-214">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-214">The name of the express route circuit.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-215">Ruft alle Statistiken aus einer express-Route-Verbindung in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-215">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetStatsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt; GetStatsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.GetStatsAsync (operations, resourceGroupName, circuitName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;GetStatsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-216">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-216">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-217">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-217">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-218">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-218">The name of the express route circuit.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-220">Ruft alle Statistiken aus einer express-Route-Verbindung in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-220">Gets all the stats from an express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; List (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; List(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.List(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IExpressRouteCircuitsOperations, resourceGroupName As String) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-222">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-222">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-223">Ruft die express-Route-Verbindungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-223">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAll (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAll(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IExpressRouteCircuitsOperations) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-224">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-224">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-225">Ruft die express-Route-Verbindungen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-225">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-226">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-228">Ruft die express-Route-Verbindungen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-228">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAllNext (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListAllNext(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IExpressRouteCircuitsOperations, nextPageLink As String) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-229">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8a10f-230">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8a10f-230">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-231">Ruft die express-Route-Verbindungen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-231">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListAllNextAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-232">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8a10f-233">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8a10f-233">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-234">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-235">Ruft die express-Route-Verbindungen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-235">Gets all the express route circuits in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListArpTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult ListArpTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult ListArpTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListArpTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsArpTableListResult" />
      <MemberSignature Language="F#" Value="static member ListArpTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-237">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-237">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-238">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-238">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-239">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-239">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-240">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-240">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-241">Ruft die derzeit angekündigte ARP-Tabelle der express-Route-Verbindung in einer Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8a10f-241">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListArpTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; ListArpTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt; ListArpTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListArpTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListArpTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListArpTableAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsArpTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-243">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-243">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-244">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-244">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-245">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-245">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-246">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-246">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-247">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-248">Ruft die derzeit angekündigte ARP-Tabelle der express-Route-Verbindung in einer Ressourcengruppe zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8a10f-248">Gets the currently advertised ARP table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-249">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-249">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-250">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-250">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-251">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-251">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-252">Ruft die express-Route-Verbindungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-252">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListNext (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; ListNext(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IExpressRouteCircuitsOperations, nextPageLink As String) As IPage(Of ExpressRouteCircuit)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-253">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-253">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8a10f-254">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8a10f-254">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-255">Ruft die express-Route-Verbindungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-255">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListNextAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-256">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="8a10f-257">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="8a10f-257">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-258">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-258">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-259">Ruft die express-Route-Verbindungen in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-259">Gets all the express route circuits in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult ListRoutesTable (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult ListRoutesTable(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTable(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRoutesTable (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableListResult" />
      <MemberSignature Language="F#" Value="static member ListRoutesTable : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTable (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-260">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-261">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-261">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-262">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-262">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-263">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-263">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-264">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-264">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-265">Ruft die derzeit angekündigte Routen-Tabelle, die die express-Route-Verbindung in einer Ressourcengruppe zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-265">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; ListRoutesTableAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt; ListRoutesTableAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-266">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-266">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-267">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-267">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-268">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-268">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-269">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-269">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-270">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-270">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-271">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-271">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-272">Ruft die derzeit angekündigte Routen-Tabelle, die die express-Route-Verbindung in einer Ressourcengruppe zugeordnet ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-272">Gets the currently advertised routes table associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummary">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult ListRoutesTableSummary (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult ListRoutesTableSummary(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummary(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRoutesTableSummary (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, peeringName As String, devicePath As String) As ExpressRouteCircuitsRoutesTableSummaryListResult" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableSummary : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummary (operations, resourceGroupName, circuitName, peeringName, devicePath)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-273">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-273">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-274">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-274">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-275">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-275">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-276">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-276">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-277">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-277">The path of the device.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-278">Ruft die derzeit angekündigte Routen Zusammenfassung der express-Route-Verbindung in einer Ressourcengruppe zugeordnet Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-278">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRoutesTableSummaryAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; ListRoutesTableSummaryAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt; ListRoutesTableSummaryAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, string peeringName, string devicePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRoutesTableSummaryAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.ListRoutesTableSummaryAsync (operations, resourceGroupName, circuitName, peeringName, devicePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;ListRoutesTableSummaryAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitsRoutesTableSummaryListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="peeringName" Type="System.String" />
        <Parameter Name="devicePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-279">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-279">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-280">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-280">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-281">Der Name der express-Route-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-281">The name of the express route circuit.</span></span>
            </param>
        <param name="peeringName">
            <span data-ttu-id="8a10f-282">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="8a10f-282">The name of the peering.</span></span>
            </param>
        <param name="devicePath">
            <span data-ttu-id="8a10f-283">Der Pfad des Geräts.</span><span class="sxs-lookup"><span data-stu-id="8a10f-283">The path of the device.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-284">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-284">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-285">Ruft die derzeit angekündigte Routen Zusammenfassung der express-Route-Verbindung in einer Ressourcengruppe zugeordnet Tabelle ab.</span><span class="sxs-lookup"><span data-stu-id="8a10f-285">Gets the currently advertised routes table summary associated with the express route circuit in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit UpdateTags (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit UpdateTags(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IExpressRouteCircuitsOperations, resourceGroupName As String, circuitName As String, parameters As TagsObject) As ExpressRouteCircuit" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTags (operations, resourceGroupName, circuitName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-286">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-286">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-287">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-287">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-288">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-288">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-289">Parameter, die zum Aktualisieren der express-Route-Circuit-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-289">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-290">Aktualisiert eine express-Route-Circuit-Tags.</span><span class="sxs-lookup"><span data-stu-id="8a10f-290">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations operations, string resourceGroupName, string circuitName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;" Usage="Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, circuitName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.ExpressRouteCircuitsOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ExpressRouteCircuit&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IExpressRouteCircuitsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="circuitName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8a10f-291">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="8a10f-291">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8a10f-292">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8a10f-292">The name of the resource group.</span></span>
            </param>
        <param name="circuitName">
            <span data-ttu-id="8a10f-293">Der Name der Verbindung.</span><span class="sxs-lookup"><span data-stu-id="8a10f-293">The name of the circuit.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8a10f-294">Parameter, die zum Aktualisieren der express-Route-Circuit-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="8a10f-294">Parameters supplied to update express route circuit tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8a10f-295">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8a10f-295">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8a10f-296">Aktualisiert eine express-Route-Circuit-Tags.</span><span class="sxs-lookup"><span data-stu-id="8a10f-296">Updates an express route circuit tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>