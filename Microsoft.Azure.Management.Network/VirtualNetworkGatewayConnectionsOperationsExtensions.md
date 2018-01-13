<Type Name="VirtualNetworkGatewayConnectionsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkGatewayConnectionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkGatewayConnectionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewayConnectionsOperationsExtensions = class" />
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
            <span data-ttu-id="532db-101">Erweiterungsmethoden für VirtualNetworkGatewayConnectionsOperations.</span><span class="sxs-lookup"><span data-stu-id="532db-101">Extension methods for VirtualNetworkGatewayConnectionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As VirtualNetworkGatewayConnection) As VirtualNetworkGatewayConnection" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-104">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-104">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-105">Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="532db-105">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-106">Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-106">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-108">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-109">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-109">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-110">Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="532db-110">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-112">Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-112">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-114">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-115">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-115">The name of the virtual network gateway connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-116">Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="532db-116">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-118">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-119">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-119">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-121">Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="532db-121">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey BeginResetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey BeginResetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginResetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionResetSharedKey) As ConnectionResetSharedKey" />
      <MemberSignature Language="F#" Value="static member BeginResetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-123">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-124">Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.</span><span class="sxs-lookup"><span data-stu-id="532db-124">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-125">Parameter für die Begin angegebene zurücksetzen virtuelles Netzwerk-Gateway freigegebene Verbindung Schlüsselvorgang über dem netzwerkressourcenanbieter.</span><span class="sxs-lookup"><span data-stu-id="532db-125">Parameters supplied to the begin reset virtual network gateway connection shared key operation through network resource provider.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-126">Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.</span><span class="sxs-lookup"><span data-stu-id="532db-126">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; BeginResetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; BeginResetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginResetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginResetSharedKeyAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-128">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-129">Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.</span><span class="sxs-lookup"><span data-stu-id="532db-129">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-130">Parameter für die Begin angegebene zurücksetzen virtuelles Netzwerk-Gateway freigegebene Verbindung Schlüsselvorgang über dem netzwerkressourcenanbieter.</span><span class="sxs-lookup"><span data-stu-id="532db-130">Parameters supplied to the begin reset virtual network gateway connection shared key operation through network resource provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-132">Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.</span><span class="sxs-lookup"><span data-stu-id="532db-132">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionSharedKey BeginSetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey BeginSetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginSetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionSharedKey) As ConnectionSharedKey" />
      <MemberSignature Language="F#" Value="static member BeginSetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-134">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-135">Der Name der virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-135">The virtual network gateway connection name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-136">Parameter, die auf den Ressourcenanbieter für beginnen festgelegt Gateway des virtuellen Netzwerks Verbindung Shared Schlüsselvorgang ThroughNetwork angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="532db-136">Parameters supplied to the Begin Set Virtual Network Gateway connection Shared key operation throughNetwork resource provider.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-137">Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.</span><span class="sxs-lookup"><span data-stu-id="532db-137">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; BeginSetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; BeginSetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginSetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginSetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginSetSharedKeyAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-139">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-140">Der Name der virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-140">The virtual network gateway connection name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-141">Parameter, die auf den Ressourcenanbieter für beginnen festgelegt Gateway des virtuellen Netzwerks Verbindung Shared Schlüsselvorgang ThroughNetwork angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="532db-141">Parameters supplied to the Begin Set Virtual Network Gateway connection Shared key operation throughNetwork resource provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-143">Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.</span><span class="sxs-lookup"><span data-stu-id="532db-143">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity BeginUpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity BeginUpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As TagsObject) As VirtualNetworkGatewayConnectionListEntity" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-145">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-146">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-146">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-147">Der Parameter angegeben, um das virtuelle Netzwerk-Gateway-Verbindung Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="532db-147">Parameters supplied to update virtual network gateway connection tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-148">Aktualisiert ein virtuelles Netzwerk-Gateway-Verbindung Tags an.</span><span class="sxs-lookup"><span data-stu-id="532db-148">Updates a virtual network gateway connection tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-150">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-150">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-151">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-151">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-152">Der Parameter angegeben, um das virtuelle Netzwerk-Gateway-Verbindung Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="532db-152">Parameters supplied to update virtual network gateway connection tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-153">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-153">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-154">Aktualisiert ein virtuelles Netzwerk-Gateway-Verbindung Tags an.</span><span class="sxs-lookup"><span data-stu-id="532db-154">Updates a virtual network gateway connection tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection CreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection CreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As VirtualNetworkGatewayConnection) As VirtualNetworkGatewayConnection" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-156">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-157">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-157">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-158">Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="532db-158">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-159">Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-159">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-161">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-161">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-162">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-162">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-163">Parameter für den Vorgang erstellen oder aktualisieren virtuelles Netzwerk-Gateway, Verbindung bereitgestellte.</span><span class="sxs-lookup"><span data-stu-id="532db-163">Parameters supplied to the create or update virtual network gateway connection operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-165">Erstellt oder aktualisiert eine virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-165">Creates or updates a virtual network gateway connection in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-166">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-167">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-167">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-168">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-168">The name of the virtual network gateway connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-169">Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="532db-169">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-171">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-171">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-172">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-172">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-174">Löscht das angegebene virtuelle Netzwerk-Gateway-Verbindung an.</span><span class="sxs-lookup"><span data-stu-id="532db-174">Deletes the specified virtual network Gateway connection.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection Get (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection Get(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String) As VirtualNetworkGatewayConnection" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-175">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-176">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-176">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-177">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-177">The name of the virtual network gateway connection.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-178">Ruft die angegebene virtuelle Netzwerk-Gateway-Verbindung durch die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="532db-178">Gets the specified virtual network gateway connection by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; GetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; GetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-180">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-180">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-181">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-181">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-183">Ruft die angegebene virtuelle Netzwerk-Gateway-Verbindung durch die Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="532db-183">Gets the specified virtual network gateway connection by resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionSharedKey GetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey GetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String) As ConnectionSharedKey" />
      <MemberSignature Language="F#" Value="static member GetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string -&gt; Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-184">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-185">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-185">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-186">Die gatewayverbindung des virtuellen Netzwerks freigegeben Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="532db-186">The virtual network gateway connection shared key name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-187">Der VirtualNetworkGatewayConnectionSharedKey Get-Vorgang ruft Informationen zu den angegebenen virtuellen Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel über dem netzwerkressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="532db-187">The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; GetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; GetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.GetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;GetSharedKeyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-188">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-189">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-189">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-190">Die gatewayverbindung des virtuellen Netzwerks freigegeben Schlüsselnamen.</span><span class="sxs-lookup"><span data-stu-id="532db-190">The virtual network gateway connection shared key name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-191">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-191">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-192">Der VirtualNetworkGatewayConnectionSharedKey Get-Vorgang ruft Informationen zu den angegebenen virtuellen Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel über dem netzwerkressourcenanbieter ab.</span><span class="sxs-lookup"><span data-stu-id="532db-192">The Get VirtualNetworkGatewayConnectionSharedKey operation retrieves information about the specified virtual network gateway connection shared key through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; List (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; List(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.List(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String) As IPage(Of VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-193">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-194">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-194">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-195">Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.</span><span class="sxs-lookup"><span data-stu-id="532db-195">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-197">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-197">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-199">Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.</span><span class="sxs-lookup"><span data-stu-id="532db-199">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; ListNext (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt; ListNext(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualNetworkGatewayConnectionsOperations, nextPageLink As String) As IPage(Of VirtualNetworkGatewayConnection)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-200">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="532db-201">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="532db-201">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-202">Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.</span><span class="sxs-lookup"><span data-stu-id="532db-202">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnection&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-203">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-203">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="532db-204">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="532db-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-205">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-206">Die Liste VirtualNetworkGatewayConnections Vorgang ruft alle virtuellen Netzwerk-Gateways Verbindungen erstellt.</span><span class="sxs-lookup"><span data-stu-id="532db-206">The List VirtualNetworkGatewayConnections operation retrieves all the virtual network gateways connections created.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey ResetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey ResetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionResetSharedKey) As ConnectionResetSharedKey" />
      <MemberSignature Language="F#" Value="static member ResetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-207">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-208">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-208">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-209">Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.</span><span class="sxs-lookup"><span data-stu-id="532db-209">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-210">Parameter für die Begin angegebene zurücksetzen virtuelles Netzwerk-Gateway freigegebene Verbindung Schlüsselvorgang über dem netzwerkressourcenanbieter.</span><span class="sxs-lookup"><span data-stu-id="532db-210">Parameters supplied to the begin reset virtual network gateway connection shared key operation through network resource provider.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-211">Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.</span><span class="sxs-lookup"><span data-stu-id="532db-211">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; ResetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt; ResetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.ResetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;ResetSharedKeyAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionResetSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-213">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-213">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-214">Die gatewayverbindung des virtuellen Netzwerks zurücksetzen gemeinsam verwendeten Schlüssel Name.</span><span class="sxs-lookup"><span data-stu-id="532db-214">The virtual network gateway connection reset shared key Name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-215">Parameter für die Begin angegebene zurücksetzen virtuelles Netzwerk-Gateway freigegebene Verbindung Schlüsselvorgang über dem netzwerkressourcenanbieter.</span><span class="sxs-lookup"><span data-stu-id="532db-215">Parameters supplied to the begin reset virtual network gateway connection shared key operation through network resource provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-216">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-216">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-217">Der Vorgang VirtualNetworkGatewayConnectionResetSharedKey setzt die virtuelles Netzwerk-Gateway-Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter zurück.</span><span class="sxs-lookup"><span data-stu-id="532db-217">The VirtualNetworkGatewayConnectionResetSharedKey operation resets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKey">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.ConnectionSharedKey SetSharedKey (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey SetSharedKey(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKey(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetSharedKey (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As ConnectionSharedKey) As ConnectionSharedKey" />
      <MemberSignature Language="F#" Value="static member SetSharedKey : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey -&gt; Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKey (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ConnectionSharedKey</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-219">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-219">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-220">Der Name der virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-220">The virtual network gateway connection name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-221">Parameter, die auf den Ressourcenanbieter für beginnen festgelegt Gateway des virtuellen Netzwerks Verbindung Shared Schlüsselvorgang ThroughNetwork angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="532db-221">Parameters supplied to the Begin Set Virtual Network Gateway connection Shared key operation throughNetwork resource provider.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-222">Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.</span><span class="sxs-lookup"><span data-stu-id="532db-222">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSharedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; SetSharedKeyAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt; SetSharedKeyAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.ConnectionSharedKey parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.ConnectionSharedKey,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSharedKeyAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.ConnectionSharedKey * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.SetSharedKeyAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;SetSharedKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.ConnectionSharedKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.ConnectionSharedKey" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-223">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-223">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-224">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-224">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-225">Der Name der virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-225">The virtual network gateway connection name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-226">Parameter, die auf den Ressourcenanbieter für beginnen festgelegt Gateway des virtuellen Netzwerks Verbindung Shared Schlüsselvorgang ThroughNetwork angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="532db-226">Parameters supplied to the Begin Set Virtual Network Gateway connection Shared key operation throughNetwork resource provider.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-228">Der VirtualNetworkGatewayConnectionSharedKey Put-Vorgang legt das virtuelle Netzwerk-Gateway Verbindung gemeinsam verwendeten Schlüssel für übergebene virtuelles Netzwerk-Gateway-Verbindung in der angegebenen Ressourcengruppe über dem netzwerkressourcenanbieter fest.</span><span class="sxs-lookup"><span data-stu-id="532db-228">The Put VirtualNetworkGatewayConnectionSharedKey operation sets the virtual network gateway connection shared key for passed virtual network gateway connection in the specified resource group through Network resource provider.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity UpdateTags (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity UpdateTags(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As IVirtualNetworkGatewayConnectionsOperations, resourceGroupName As String, virtualNetworkGatewayConnectionName As String, parameters As TagsObject) As VirtualNetworkGatewayConnectionListEntity" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTags (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-229">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-230">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-230">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-231">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-231">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-232">Der Parameter angegeben, um das virtuelle Netzwerk-Gateway-Verbindung Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="532db-232">Parameters supplied to update virtual network gateway connection tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-233">Aktualisiert ein virtuelles Netzwerk-Gateway-Verbindung Tags an.</span><span class="sxs-lookup"><span data-stu-id="532db-233">Updates a virtual network gateway connection tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations operations, string resourceGroupName, string virtualNetworkGatewayConnectionName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, virtualNetworkGatewayConnectionName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkGatewayConnectionsOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayConnectionListEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkGatewayConnectionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkGatewayConnectionName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="532db-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="532db-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="532db-235">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="532db-235">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkGatewayConnectionName">
            <span data-ttu-id="532db-236">Der Name des virtuellen Netzwerk-Gateway-Verbindung.</span><span class="sxs-lookup"><span data-stu-id="532db-236">The name of the virtual network gateway connection.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="532db-237">Der Parameter angegeben, um das virtuelle Netzwerk-Gateway-Verbindung Tags zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="532db-237">Parameters supplied to update virtual network gateway connection tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="532db-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="532db-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="532db-239">Aktualisiert ein virtuelles Netzwerk-Gateway-Verbindung Tags an.</span><span class="sxs-lookup"><span data-stu-id="532db-239">Updates a virtual network gateway connection tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>