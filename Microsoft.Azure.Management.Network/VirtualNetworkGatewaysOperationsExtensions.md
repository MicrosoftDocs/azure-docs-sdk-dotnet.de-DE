<Type Name="VirtualNetworkGatewaysOperationsExtensions" FullName="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewaysOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewaysOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewaysOperationsExtensions = class" />
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
            <span data-ttu-id="bcae1-101">Erweiterungsmethoden für VirtualNetworkGatewaysOperations.</span><span class="sxs-lookup"><span data-stu-id="bcae1-101">Extension methods for VirtualNetworkGatewaysOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VirtualNetworkGateway) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-104">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-104">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-105">Parameter zum Erstellen oder Aktualisieren des virtuellen Netzwerks Gatewayvorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-105">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-106">Erstellt oder aktualisiert ein Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-106">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-108">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-109">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-109">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-110">Parameter zum Erstellen oder Aktualisieren des virtuellen Netzwerks Gatewayvorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-110">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-112">Erstellt oder aktualisiert ein Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-112">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-114">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-115">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-115">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-116">Löscht das angegebene virtuelle Netzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="bcae1-116">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginDeleteAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-118">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-119">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-119">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-121">Löscht das angegebene virtuelle Netzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="bcae1-121">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackage">
      <MemberSignature Language="C#" Value="public static string BeginGeneratevpnclientpackage (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string BeginGeneratevpnclientpackage(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackage(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGeneratevpnclientpackage (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member BeginGeneratevpnclientpackage : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackage (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-123">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-124">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-124">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-125">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-125">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-126">Generiert von VPN-Clientpaket für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-126">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGeneratevpnclientpackageAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-128">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-129">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-129">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-130">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-130">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-132">Generiert von VPN-Clientpaket für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-132">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfile">
      <MemberSignature Language="C#" Value="public static string BeginGenerateVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string BeginGenerateVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGenerateVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member BeginGenerateVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-134">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-135">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-135">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-136">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-136">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-137">Generiert von VPN-Profil für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-137">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-138">Für IKEV2- und RADIUS-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="bcae1-138">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGenerateVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGenerateVpnProfileAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-140">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-141">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-141">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-142">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-142">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-144">Generiert von VPN-Profil für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-144">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-145">Für IKEV2- und RADIUS-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="bcae1-145">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetAdvertisedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetAdvertisedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetAdvertisedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, peer As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetAdvertisedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutes (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-146">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-147">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-147">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-148">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-148">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-149">Die IP-Adresse des Peers</span><span class="sxs-lookup"><span data-stu-id="bcae1-149">The IP address of the peer</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-150">Dieser Vorgang ruft eine Liste der Routen, die das Gateway des virtuellen Netzwerks für den angegebenen Peer ankündigt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-150">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetAdvertisedRoutesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-152">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-152">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-153">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-153">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-154">Die IP-Adresse des Peers</span><span class="sxs-lookup"><span data-stu-id="bcae1-154">The IP address of the peer</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-156">Dieser Vorgang ruft eine Liste der Routen, die das Gateway des virtuellen Netzwerks für den angegebenen Peer ankündigt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-156">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult BeginGetBgpPeerStatus (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult BeginGetBgpPeerStatus(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatus(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetBgpPeerStatus (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional peer As String = null) As BgpPeerStatusListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetBgpPeerStatus : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatus (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-158">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-158">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-159">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-159">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-160">Die IP-Adresse des Peers, der beim Abrufen des Status von.</span><span class="sxs-lookup"><span data-stu-id="bcae1-160">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-161">Der GetBgpPeerStatus-Vorgang wird der Status für alle BGP-Peers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="bcae1-161">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; BeginGetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; BeginGetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetBgpPeerStatusAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-162">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-163">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-163">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-164">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-164">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-165">Die IP-Adresse des Peers, der beim Abrufen des Status von.</span><span class="sxs-lookup"><span data-stu-id="bcae1-165">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-166">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-166">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-167">Der GetBgpPeerStatus-Vorgang wird der Status für alle BGP-Peers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="bcae1-167">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetLearnedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult BeginGetLearnedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetLearnedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member BeginGetLearnedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutes (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-168">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-169">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-169">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-170">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-170">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-171">Dieser Vorgang eine Liste der Routen abruft, die das virtuelle Netzwerkgateway erfasst hat, haben gelernt einschließlich Routen aus der BGP-Peers.</span><span class="sxs-lookup"><span data-stu-id="bcae1-171">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; BeginGetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetLearnedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetLearnedRoutesAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-172">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-173">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-173">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-174">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-174">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-176">Dieser Vorgang eine Liste der Routen abruft, die das virtuelle Netzwerkgateway erfasst hat, haben gelernt einschließlich Routen aus der BGP-Peers.</span><span class="sxs-lookup"><span data-stu-id="bcae1-176">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVpnProfilePackageUrl">
      <MemberSignature Language="C#" Value="public static string BeginGetVpnProfilePackageUrl (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string BeginGetVpnProfilePackageUrl(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrl(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginGetVpnProfilePackageUrl (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member BeginGetVpnProfilePackageUrl : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrl (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-178">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-178">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-179">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-179">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-180">Ruft vorgenerierten VPN-Profil für das Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe P2S-Client.</span><span class="sxs-lookup"><span data-stu-id="bcae1-180">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-181">Das Profil muss generiert werden zuerst mit GenerateVpnProfile.</span><span class="sxs-lookup"><span data-stu-id="bcae1-181">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetVpnProfilePackageUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; BeginGetVpnProfilePackageUrlAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; BeginGetVpnProfilePackageUrlAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrlAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetVpnProfilePackageUrlAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginGetVpnProfilePackageUrlAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginGetVpnProfilePackageUrlAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-183">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-183">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-184">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-184">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-186">Ruft vorgenerierten VPN-Profil für das Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe P2S-Client.</span><span class="sxs-lookup"><span data-stu-id="bcae1-186">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-187">Das Profil muss generiert werden zuerst mit GenerateVpnProfile.</span><span class="sxs-lookup"><span data-stu-id="bcae1-187">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginReset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginReset (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginReset(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginReset(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginReset (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional gatewayVip As String = null) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginReset : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginReset (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-189">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-189">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-190">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-190">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="bcae1-191">Virtuelles Netzwerk-Gateway-Adresse Begin Zurücksetzen des aktiv / aktiv-Funktion aktiviert-Gateways bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-191">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-192">Setzt das primäre Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-192">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginResetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginResetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginResetAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-194">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-194">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-195">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-195">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="bcae1-196">Virtuelles Netzwerk-Gateway-Adresse Begin Zurücksetzen des aktiv / aktiv-Funktion aktiviert-Gateways bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-196">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-197">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-198">Setzt das primäre Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-198">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginUpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway BeginUpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As TagsObject) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-199">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-199">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-200">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-200">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-201">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-201">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-202">Parameter, die zum Aktualisieren des virtuellen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-202">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-203">Aktualisiert ein virtuelles Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="bcae1-203">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-204">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-205">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-205">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-206">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-206">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-207">Parameter, die zum Aktualisieren des virtuellen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-207">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-209">Aktualisiert ein virtuelles Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="bcae1-209">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway CreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway CreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VirtualNetworkGateway) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-210">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-211">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-211">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-212">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-212">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-213">Parameter zum Erstellen oder Aktualisieren des virtuellen Netzwerks Gatewayvorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-213">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-214">Erstellt oder aktualisiert ein Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-214">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-215">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-216">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-216">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-217">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-217">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-218">Parameter zum Erstellen oder Aktualisieren des virtuellen Netzwerks Gatewayvorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-218">Parameters supplied to create or update virtual network gateway operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-220">Erstellt oder aktualisiert ein Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-220">Creates or updates a virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkGatewayName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-222">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-222">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-223">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-223">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-224">Löscht das angegebene virtuelle Netzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="bcae1-224">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;DeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-226">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-226">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-227">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-227">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-228">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-228">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-229">Löscht das angegebene virtuelle Netzwerk-Gateway.</span><span class="sxs-lookup"><span data-stu-id="bcae1-229">Deletes the specified virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateGatewayVpnProfile">
      <MemberSignature Language="C#" Value="public static string GenerateGatewayVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateGatewayVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateGatewayVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member GenerateGatewayVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-230">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-230">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-231">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-231">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-232">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-232">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-233">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-233">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-234">Generiert von VPN-Profil für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-234">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-235">Für IKEV2- und RADIUS-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="bcae1-235">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateGatewayVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GenerateGatewayVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GenerateGatewayVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateGatewayVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateGatewayVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GenerateGatewayVpnProfileAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-237">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-237">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-238">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-238">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-239">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-239">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-240">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-241">Generiert von VPN-Profil für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-241">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-242">Für IKEV2- und RADIUS-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="bcae1-242">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Generatevpnclientpackage">
      <MemberSignature Language="C#" Value="public static string Generatevpnclientpackage (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string Generatevpnclientpackage(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Generatevpnclientpackage(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Generatevpnclientpackage (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member Generatevpnclientpackage : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Generatevpnclientpackage (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-243">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-243">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-244">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-244">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-245">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-245">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-246">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-246">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-247">Generiert von VPN-Clientpaket für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-247">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneratevpnclientpackageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GeneratevpnclientpackageAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GeneratevpnclientpackageAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneratevpnclientpackageAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GeneratevpnclientpackageAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GeneratevpnclientpackageAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-248">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-248">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-249">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-249">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-250">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-250">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-251">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-251">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-252">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-252">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-253">Generiert von VPN-Clientpaket für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-253">Generates VPN client package for P2S client of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfile">
      <MemberSignature Language="C#" Value="public static string GenerateVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As VpnClientParameters) As String" />
      <MemberSignature Language="F#" Value="static member GenerateVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-254">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-254">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-255">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-255">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-256">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-256">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-257">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-257">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-258">Generiert von VPN-Profil für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-258">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-259">Für IKEV2- und RADIUS-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="bcae1-259">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GenerateVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GenerateVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.VpnClientParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnClientParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GenerateVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnClientParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GenerateVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GenerateVpnProfileAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnClientParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-260">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-260">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-261">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-261">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-262">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-262">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-263">Parameter, die das Gateway des virtuellen Netzwerks generieren VPN-Paket Clientvorgang übergeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-263">Parameters supplied to the generate virtual network gateway VPN client package operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-264">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-264">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-265">Generiert von VPN-Profil für das virtuelle Netzwerkgateway P2S-Client in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-265">Generates VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-266">Für IKEV2- und RADIUS-Authentifizierung verwendet.</span><span class="sxs-lookup"><span data-stu-id="bcae1-266">Used for IKEV2 and radius based authentication.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Get (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Get(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Get(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-267">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-268">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-268">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-269">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-269">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-270">Ruft das angegebene virtuelle Netzwerk-Gateway durch die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-270">Gets the specified virtual network gateway by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetAdvertisedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetAdvertisedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAdvertisedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, peer As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member GetAdvertisedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutes (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-271">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-271">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-272">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-272">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-273">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-273">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-274">Die IP-Adresse des Peers</span><span class="sxs-lookup"><span data-stu-id="bcae1-274">The IP address of the peer</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-275">Dieser Vorgang ruft eine Liste der Routen, die das Gateway des virtuellen Netzwerks für den angegebenen Peer ankündigt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-275">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAdvertisedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetAdvertisedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetAdvertisedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAdvertisedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAdvertisedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAdvertisedRoutesAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-276">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-276">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-277">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-277">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-278">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-278">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-279">Die IP-Adresse des Peers</span><span class="sxs-lookup"><span data-stu-id="bcae1-279">The IP address of the peer</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-280">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-281">Dieser Vorgang ruft eine Liste der Routen, die das Gateway des virtuellen Netzwerks für den angegebenen Peer ankündigt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-281">This operation retrieves a list of routes the virtual network gateway is advertising to the specified peer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; GetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; GetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-282">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-282">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-283">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-283">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-284">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-284">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-285">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-285">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-286">Ruft das angegebene virtuelle Netzwerk-Gateway durch die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-286">Gets the specified virtual network gateway by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult GetBgpPeerStatus (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult GetBgpPeerStatus(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatus(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetBgpPeerStatus (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional peer As String = null) As BgpPeerStatusListResult" />
      <MemberSignature Language="F#" Value="static member GetBgpPeerStatus : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatus (operations, resourceGroupName, virtualNetworkGatewayName, peer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-287">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-287">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-288">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-288">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-289">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-289">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-290">Die IP-Adresse des Peers, der beim Abrufen des Status von.</span><span class="sxs-lookup"><span data-stu-id="bcae1-290">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-291">Der GetBgpPeerStatus-Vorgang wird der Status für alle BGP-Peers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="bcae1-291">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBgpPeerStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; GetBgpPeerStatusAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt; GetBgpPeerStatusAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string peer, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetBgpPeerStatusAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetBgpPeerStatusAsync (operations, resourceGroupName, virtualNetworkGatewayName, peer, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetBgpPeerStatusAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BgpPeerStatusListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="peer" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-292">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-292">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-293">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-293">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-294">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-294">The name of the virtual network gateway.</span></span>
            </param>
        <param name="peer">
            <span data-ttu-id="bcae1-295">Die IP-Adresse des Peers, der beim Abrufen des Status von.</span><span class="sxs-lookup"><span data-stu-id="bcae1-295">The IP address of the peer to retrieve the status of.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-296">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-296">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-297">Der GetBgpPeerStatus-Vorgang wird der Status für alle BGP-Peers abgerufen.</span><span class="sxs-lookup"><span data-stu-id="bcae1-297">The GetBgpPeerStatus operation retrieves the status of all BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayVpnProfile">
      <MemberSignature Language="C#" Value="public static string GetGatewayVpnProfile (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetGatewayVpnProfile(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfile(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetGatewayVpnProfile (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member GetGatewayVpnProfile : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfile (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-298">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-298">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-299">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-299">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-300">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-300">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-301">Ruft vorgenerierten VPN-Profil für das Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe P2S-Client.</span><span class="sxs-lookup"><span data-stu-id="bcae1-301">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-302">Das Profil muss generiert werden zuerst mit GenerateVpnProfile.</span><span class="sxs-lookup"><span data-stu-id="bcae1-302">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetGatewayVpnProfileAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetGatewayVpnProfileAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetGatewayVpnProfileAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfileAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetGatewayVpnProfileAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetGatewayVpnProfileAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetGatewayVpnProfileAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-303">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-303">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-304">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-304">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-305">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-305">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-306">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-307">Ruft vorgenerierten VPN-Profil für das Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe P2S-Client.</span><span class="sxs-lookup"><span data-stu-id="bcae1-307">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-308">Das Profil muss generiert werden zuerst mit GenerateVpnProfile.</span><span class="sxs-lookup"><span data-stu-id="bcae1-308">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutes">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetLearnedRoutes (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult GetLearnedRoutes(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutes(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLearnedRoutes (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As GatewayRouteListResult" />
      <MemberSignature Language="F#" Value="static member GetLearnedRoutes : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.GatewayRouteListResult" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutes (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.GatewayRouteListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-309">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-309">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-310">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-310">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-311">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-311">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-312">Dieser Vorgang eine Liste der Routen abruft, die das virtuelle Netzwerkgateway erfasst hat, haben gelernt einschließlich Routen aus der BGP-Peers.</span><span class="sxs-lookup"><span data-stu-id="bcae1-312">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLearnedRoutesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetLearnedRoutesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt; GetLearnedRoutesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetLearnedRoutesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetLearnedRoutesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetLearnedRoutesAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.GatewayRouteListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-313">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-313">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-314">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-314">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-315">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-315">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-316">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-317">Dieser Vorgang eine Liste der Routen abruft, die das virtuelle Netzwerkgateway erfasst hat, haben gelernt einschließlich Routen aus der BGP-Peers.</span><span class="sxs-lookup"><span data-stu-id="bcae1-317">This operation retrieves a list of routes the virtual network gateway has learned, including routes learned from BGP peers.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVpnProfilePackageUrl">
      <MemberSignature Language="C#" Value="public static string GetVpnProfilePackageUrl (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetVpnProfilePackageUrl(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrl(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetVpnProfilePackageUrl (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member GetVpnProfilePackageUrl : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrl (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-318">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-318">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-319">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-319">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-320">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-320">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-321">Ruft vorgenerierten VPN-Profil für das Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe P2S-Client.</span><span class="sxs-lookup"><span data-stu-id="bcae1-321">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-322">Das Profil muss generiert werden zuerst mit GenerateVpnProfile.</span><span class="sxs-lookup"><span data-stu-id="bcae1-322">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVpnProfilePackageUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetVpnProfilePackageUrlAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetVpnProfilePackageUrlAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrlAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVpnProfilePackageUrlAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.GetVpnProfilePackageUrlAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;GetVpnProfilePackageUrlAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-323">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-323">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-324">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-324">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-325">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-325">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-326">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-326">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-327">Ruft vorgenerierten VPN-Profil für das Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe P2S-Client.</span><span class="sxs-lookup"><span data-stu-id="bcae1-327">Gets pre-generated VPN profile for P2S client of the virtual network gateway in the specified resource group.</span></span> <span data-ttu-id="bcae1-328">Das Profil muss generiert werden zuerst mit GenerateVpnProfile.</span><span class="sxs-lookup"><span data-stu-id="bcae1-328">The profile needs to be generated first using generateVpnProfile.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; List (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; List(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.List(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String) As IPage(Of VirtualNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-329">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-329">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-330">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-330">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-331">Ruft alle Gateways des virtuellen Netzwerks von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-331">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-332">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-332">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-333">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-333">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-334">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-334">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-335">Ruft alle Gateways des virtuellen Netzwerks von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-335">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnections">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnections (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnections(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnections(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListConnections (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As IPage(Of VirtualNetworkGatewayConnectionListEntity)" />
      <MemberSignature Language="F#" Value="static member ListConnections : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnections (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-336">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-336">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-337">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-337">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-338">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-338">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-339">Ruft alle Verbindungen in einem Gateway des virtuellen Netzwerks ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-339">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-340">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-340">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-341">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-341">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-342">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-342">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-343">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-343">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-344">Ruft alle Verbindungen in einem Gateway des virtuellen Netzwerks ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-344">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnectionsNext (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; ListConnectionsNext(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNext(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListConnectionsNext (operations As IVirtualNetworkGatewaysOperations, nextPageLink As String) As IPage(Of VirtualNetworkGatewayConnectionListEntity)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsNext : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-345">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-345">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bcae1-346">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bcae1-346">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-347">Ruft alle Verbindungen in einem Gateway des virtuellen Netzwerks ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-347">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListConnectionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt; ListConnectionsNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListConnectionsNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListConnectionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListConnectionsNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-348">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-348">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bcae1-349">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bcae1-349">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-350">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-350">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-351">Ruft alle Verbindungen in einem Gateway des virtuellen Netzwerks ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-351">Gets all the connections in a virtual network gateway.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ListNext (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ListNext(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualNetworkGatewaysOperations, nextPageLink As String) As IPage(Of VirtualNetworkGateway)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-352">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-352">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bcae1-353">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bcae1-353">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-354">Ruft alle Gateways des virtuellen Netzwerks von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-354">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ListNextAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-355">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-355">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="bcae1-356">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="bcae1-356">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-357">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-357">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-358">Ruft alle Gateways des virtuellen Netzwerks von Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-358">Gets all virtual network gateways by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Reset (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway Reset(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Reset(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Reset (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, Optional gatewayVip As String = null) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member Reset : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.Reset (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-359">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-359">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-360">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-360">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-361">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-361">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="bcae1-362">Virtuelles Netzwerk-Gateway-Adresse Begin Zurücksetzen des aktiv / aktiv-Funktion aktiviert-Gateways bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-362">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-363">Setzt das primäre Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-363">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ResetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; ResetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, string gatewayVip, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ResetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.ResetAsync (operations, resourceGroupName, virtualNetworkGatewayName, gatewayVip, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;ResetAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="gatewayVip" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-364">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-364">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-365">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-365">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-366">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-366">The name of the virtual network gateway.</span></span>
            </param>
        <param name="gatewayVip">
            <span data-ttu-id="bcae1-367">Virtuelles Netzwerk-Gateway-Adresse Begin Zurücksetzen des aktiv / aktiv-Funktion aktiviert-Gateways bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="bcae1-367">Virtual network gateway vip address supplied to the begin reset of the active-active feature enabled gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-368">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-368">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-369">Setzt das primäre Gateway des virtuellen Netzwerks in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-369">Resets the primary of the virtual network gateway in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedVpnDevices">
      <MemberSignature Language="C#" Value="public static string SupportedVpnDevices (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string SupportedVpnDevices(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevices(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SupportedVpnDevices (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String) As String" />
      <MemberSignature Language="F#" Value="static member SupportedVpnDevices : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevices (operations, resourceGroupName, virtualNetworkGatewayName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-370">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-370">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-371">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-371">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-372">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-372">The name of the virtual network gateway.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-373">Ruft eine XML-Format Darstellung für unterstützte VPN-Geräten ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-373">Gets a xml format representation for supported vpn devices.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SupportedVpnDevicesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; SupportedVpnDevicesAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; SupportedVpnDevicesAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevicesAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SupportedVpnDevicesAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.SupportedVpnDevicesAsync (operations, resourceGroupName, virtualNetworkGatewayName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;SupportedVpnDevicesAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-374">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-374">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-375">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-375">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-376">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-376">The name of the virtual network gateway.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-377">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-377">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-378">Ruft eine XML-Format Darstellung für unterstützte VPN-Geräten ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-378">Gets a xml format representation for supported vpn devices.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway UpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway UpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayName As String, parameters As TagsObject) As VirtualNetworkGateway" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTags (operations, resourceGroupName, virtualNetworkGatewayName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-379">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-379">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-380">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-380">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-381">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-381">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-382">Parameter, die zum Aktualisieren des virtuellen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-382">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-383">Aktualisiert ein virtuelles Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="bcae1-383">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;UpdateTagsAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-384">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-384">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-385">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-385">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayName">
            <span data-ttu-id="bcae1-386">Der Name des Gateways des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="bcae1-386">The name of the virtual network gateway.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-387">Parameter, die zum Aktualisieren des virtuellen Netzwerk-Gateway-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="bcae1-387">Parameters supplied to update virtual network gateway tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-388">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-388">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-389">Aktualisiert ein virtuelles Netzwerk-Gateway-Tags.</span><span class="sxs-lookup"><span data-stu-id="bcae1-389">Updates a virtual network gateway tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnDeviceConfigurationScript">
      <MemberSignature Language="C#" Value="public static string VpnDeviceConfigurationScript (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string VpnDeviceConfigurationScript(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScript(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function VpnDeviceConfigurationScript (operations As IVirtualNetworkGatewaysOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As VpnDeviceScriptParameters) As String" />
      <MemberSignature Language="F#" Value="static member VpnDeviceConfigurationScript : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters -&gt; string" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScript (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-390">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-390">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-391">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-391">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="bcae1-392">Der Name des virtuellen Netzwerk-Gateway-Verbindung für die das Skript generiert wird.</span><span class="sxs-lookup"><span data-stu-id="bcae1-392">The name of the virtual network gateway connection for which the configuration script is generated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-393">Parameter, die auf den Skriptvorgang generieren VPN-Gerät bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="bcae1-393">Parameters supplied to the generate vpn device script operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-394">Ruft eine Darstellung des Xml-Format für VPN-gerätekonfigurationsskript ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-394">Gets a xml format representation for vpn device configuration script.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnDeviceConfigurationScriptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; VpnDeviceConfigurationScriptAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; VpnDeviceConfigurationScriptAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScriptAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VpnDeviceConfigurationScriptAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations * string * string * Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions.VpnDeviceConfigurationScriptAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewaysOperationsExtensions/&lt;VpnDeviceConfigurationScriptAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewaysOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VpnDeviceScriptParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="bcae1-395">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bcae1-395">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="bcae1-396">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="bcae1-396">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="bcae1-397">Der Name des virtuellen Netzwerk-Gateway-Verbindung für die das Skript generiert wird.</span><span class="sxs-lookup"><span data-stu-id="bcae1-397">The name of the virtual network gateway connection for which the configuration script is generated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="bcae1-398">Parameter, die auf den Skriptvorgang generieren VPN-Gerät bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="bcae1-398">Parameters supplied to the generate vpn device script operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="bcae1-399">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="bcae1-399">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="bcae1-400">Ruft eine Darstellung des Xml-Format für VPN-gerätekonfigurationsskript ab.</span><span class="sxs-lookup"><span data-stu-id="bcae1-400">Gets a xml format representation for vpn device configuration script.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>