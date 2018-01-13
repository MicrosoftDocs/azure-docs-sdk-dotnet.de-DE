<Type Name="VirtualNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewaysOperationsExtensions = class" />
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
            <span data-ttu-id="4dfc0-101">Erweiterungsmethoden für VirtualNetworkGatewaysOperations.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-101">Extension methods for VirtualNetworkGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-104">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-104">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4dfc0-105">Parameter zum Erstellen oder Aktualisieren des virtuellen Netzwerks Gatewayvorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-105">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-107">Erstellt oder aktualisiert ein Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-107">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-109">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-110">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-110">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-112">Löscht das angegebene virtuelle Netzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-112">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGeneratevpnclientpackageAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGenerateVpnProfileAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGenerateVpnProfileAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetAdvertisedRoutesAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-114">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-115">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-115">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="4dfc0-116">Die IP-Adresse des Peers</span><span class="sxs-lookup"><span data-stu-id="4dfc0-116">The IP address of the peer</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-118">Dieser Vorgang ruft eine Liste der Routen, die das Gateway des virtuellen Netzwerks für den angegebenen Peer ankündigt.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-118">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; BeginGetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; BeginGetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetBgpPeerStatusAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-120">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-120">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-121">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-121">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="4dfc0-122">Die IP-Adresse des Peers, der beim Abrufen des Status von.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-122">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-124">Der GetBgpPeerStatus-Vorgang wird der Status für alle BGP-Peers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-124">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; BeginGetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetLearnedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetLearnedRoutesAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-126">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-126">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-127">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-127">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-129">Dieser Vorgang eine Liste der Routen abruft, die das virtuelle Netzwerkgateway erfasst hat, haben gelernt einschließlich Routen aus der BGP-Peers.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-129">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginResetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; BeginResetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginResetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-131">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-131">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-132">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-132">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="4dfc0-133">Virtuelles Netzwerk-Gateway-Adresse Begin Zurücksetzen des aktiv / aktiv-Funktion aktiviert-Gateways bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-133">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-135">Setzt das primäre Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-135">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-137">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-137">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-138">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-138">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="4dfc0-139">Parameter zum Erstellen oder Aktualisieren des virtuellen Netzwerks Gatewayvorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-139">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-140">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-140">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-141">Erstellt oder aktualisiert ein Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-141">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-142">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-143">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-143">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-144">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-144">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-145">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-145">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-146">Löscht das angegebene virtuelle Netzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-146">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GeneratevpnclientpackageAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateVpnProfileAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GenerateVpnProfileAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.VpnClientParametersInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAdvertisedRoutesAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-148">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-148">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-149">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-149">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="4dfc0-150">Die IP-Adresse des Peers</span><span class="sxs-lookup"><span data-stu-id="4dfc0-150">The IP address of the peer</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-152">Dieser Vorgang ruft eine Liste der Routen, die das Gateway des virtuellen Netzwerks für den angegebenen Peer ankündigt.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-152">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-154">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-155">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-155">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-157">Ruft das angegebene virtuelle Netzwerk-Gateway durch die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-157">Gets the specified virtual network gateway by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; GetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt; GetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetBgpPeerStatusAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.BgpPeerStatusListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-159">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-160">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-160">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="4dfc0-161">Die IP-Adresse des Peers, der beim Abrufen des Status von.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-161">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-163">Der GetBgpPeerStatus-Vorgang wird der Status für alle BGP-Peers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-163">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt; GetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLearnedRoutesAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;GetLearnedRoutesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.GatewayRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-165">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-166">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-166">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-168">Dieser Vorgang eine Liste der Routen abruft, die das virtuelle Netzwerkgateway erfasst hat, haben gelernt einschließlich Routen aus der BGP-Peers.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-168">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-169">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-170">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-170">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-172">Ruft alle Gateways des virtuellen Netzwerks von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-172">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="resourceGroupName">To be added.</param>
        <param name="virtualNetworkGatewayName">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt; ListConnectionsNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsNextAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayConnectionListEntityInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="nextPageLink">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="4dfc0-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-176">Ruft alle Gateways des virtuellen Netzwerks von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-176">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; ResetAsync (this Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt; ResetAsync(class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ResetAsync(Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAsync : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions.ResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.VirtualNetworkGatewaysOperationsExtensions/&lt;ResetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewayInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="4dfc0-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="4dfc0-178">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-178">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="4dfc0-179">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-179">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="4dfc0-180">Virtuelles Netzwerk-Gateway-Adresse Begin Zurücksetzen des aktiv / aktiv-Funktion aktiviert-Gateways bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-180">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4dfc0-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4dfc0-182">Setzt das primäre Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="4dfc0-182">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>