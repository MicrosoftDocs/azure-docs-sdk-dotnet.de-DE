<Type Name="VirtualNetworkGatewayConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewayConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewayConnectionsOperationsExtensions = class" />
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
            <span data-ttu-id="545f1-101">Erweiterungsmethoden für VirtualNetworkGatewayConnectionsOperations.</span><span class="sxs-lookup"><span data-stu-id="545f1-101">Extension methods for VirtualNetworkGatewayConnectionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-104">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-104">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="545f1-105">Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="545f1-105">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-107">Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-107">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-109">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-110">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-110">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-112">Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="545f1-112">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; BeginResetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int keyLength, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; BeginResetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int32 keyLength, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, keyLength, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginResetSharedKeyAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="keyLength" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-114">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-115">Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.</span><span class="sxs-lookup"><span data-stu-id="545f1-115">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="keyLength">
            <span data-ttu-id="545f1-116">Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssellänge zurücksetzen, muss zwischen 1 und 128.</span><span class="sxs-lookup"><span data-stu-id="545f1-116">The virtual network connection reset shared key length, should between 1 and 128.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-118">Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.</span><span class="sxs-lookup"><span data-stu-id="545f1-118">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; BeginSetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; BeginSetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginSetSharedKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-120">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-121">Der Name der virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-121">The virtual network gateway connection name.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="545f1-122">Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssel-Wert.</span><span class="sxs-lookup"><span data-stu-id="545f1-122">The virtual network connection shared key value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-124">Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.</span><span class="sxs-lookup"><span data-stu-id="545f1-124">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-126">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-126">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-127">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-127">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="545f1-128">Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="545f1-128">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-130">Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-130">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-131">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-131">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-132">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-132">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-133">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-133">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-135">Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="545f1-135">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-137">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-137">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-138">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-138">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-140">Ruft die angegebene virtuelle Netzwerk-Gateway-Verbindung durch die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="545f1-140">Gets the specified virtual network gateway connection by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; GetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; GetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetSharedKeyAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-142">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-142">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-143">Die gatewayverbindung des virtuellen Netzwerks freigegeben Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="545f1-143">The virtual network gateway connection shared key name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-145">Der VirtualNetworkGatewayConnectionSharedKey Get-Vorgang ruft Informationen zu den angegebenen virtuellen Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel über dem netzwerkressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="545f1-145">The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-147">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-149">Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.</span><span class="sxs-lookup"><span data-stu-id="545f1-149">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListNextAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-150">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="545f1-151">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="545f1-151">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-153">Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.</span><span class="sxs-lookup"><span data-stu-id="545f1-153">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; ResetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int keyLength, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt; ResetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, int32 keyLength, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, keyLength, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ResetSharedKeyAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionResetSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="keyLength" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-155">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-155">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-156">Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.</span><span class="sxs-lookup"><span data-stu-id="545f1-156">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="keyLength">
            <span data-ttu-id="545f1-157">Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssellänge zurücksetzen, muss zwischen 1 und 128.</span><span class="sxs-lookup"><span data-stu-id="545f1-157">The virtual network connection reset shared key length, should between 1 and 128.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-159">Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.</span><span class="sxs-lookup"><span data-stu-id="545f1-159">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; SetSharedKeyAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt; SetSharedKeyAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, string value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSharedKeyAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;SetSharedKeyAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.ConnectionSharedKeyInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="545f1-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="545f1-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="545f1-161">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="545f1-161">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="545f1-162">Der Name der virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="545f1-162">The virtual network gateway connection name.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="545f1-163">Die Verbindung des virtuellen Netzwerks freigegebenen Schlüssel-Wert.</span><span class="sxs-lookup"><span data-stu-id="545f1-163">The virtual network connection shared key value.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="545f1-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="545f1-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="545f1-165">Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.</span><span class="sxs-lookup"><span data-stu-id="545f1-165">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>