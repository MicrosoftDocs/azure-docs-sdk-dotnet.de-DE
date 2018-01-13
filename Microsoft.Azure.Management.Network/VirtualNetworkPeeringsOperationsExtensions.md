<Type Name="VirtualNetworkPeeringsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkPeeringsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkPeeringsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkPeeringsOperationsExtensions = class" />
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
            <span data-ttu-id="68ee0-101">Erweiterungsmethoden für VirtualNetworkPeeringsOperations.</span><span class="sxs-lookup"><span data-stu-id="68ee0-101">Extension methods for VirtualNetworkPeeringsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualNetworkPeeringsOperations, resourceGroupName As String, virtualNetworkName As String, virtualNetworkPeeringName As String, virtualNetworkPeeringParameters As VirtualNetworkPeering) As VirtualNetworkPeering" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-103">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-104">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-104">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-105">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-105">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="68ee0-106">Parameter zum Erstellen oder aktualisieren virtuelles Netzwerk peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="68ee0-106">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-107">Erstellt oder aktualisiert ein peering im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="68ee0-107">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-109">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-110">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-110">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-111">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-111">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="68ee0-112">Parameter zum Erstellen oder aktualisieren virtuelles Netzwerk peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="68ee0-112">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-114">Erstellt oder aktualisiert ein peering im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="68ee0-114">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVirtualNetworkPeeringsOperations, resourceGroupName As String, virtualNetworkName As String, virtualNetworkPeeringName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginDelete (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-116">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-117">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-117">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-118">Der Name des virtuellen Netzwerks peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-118">The name of the virtual network peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-119">Löscht das angegebene virtuelle Netzwerk-peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-119">Deletes the specified virtual network peering.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-121">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-122">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-122">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-123">Der Name des virtuellen Netzwerks peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-123">The name of the virtual network peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-125">Löscht das angegebene virtuelle Netzwerk-peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-125">Deletes the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering CreateOrUpdate (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering CreateOrUpdate(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualNetworkPeeringsOperations, resourceGroupName As String, virtualNetworkName As String, virtualNetworkPeeringName As String, virtualNetworkPeeringParameters As VirtualNetworkPeering) As VirtualNetworkPeering" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-127">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-128">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-128">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-129">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-129">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="68ee0-130">Parameter zum Erstellen oder aktualisieren virtuelles Netzwerk peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="68ee0-130">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-131">Erstellt oder aktualisiert ein peering im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="68ee0-131">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering virtualNetworkPeeringParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, virtualNetworkPeeringParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringParameters" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-133">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-134">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-134">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-135">Der Name von peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-135">The name of the peering.</span></span>
            </param>
        <param name="virtualNetworkPeeringParameters">
            <span data-ttu-id="68ee0-136">Parameter zum Erstellen oder aktualisieren virtuelles Netzwerk peering Vorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="68ee0-136">Parameters supplied to the create or update virtual network peering operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-138">Erstellt oder aktualisiert ein peering im angegebenen virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="68ee0-138">Creates or updates a peering in the specified virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVirtualNetworkPeeringsOperations, resourceGroupName As String, virtualNetworkName As String, virtualNetworkPeeringName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.Delete (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-140">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-141">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-141">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-142">Der Name des virtuellen Netzwerks peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-142">The name of the virtual network peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-143">Löscht das angegebene virtuelle Netzwerk-peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-143">Deletes the specified virtual network peering.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.DeleteAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-145">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-146">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-146">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-147">Der Name des virtuellen Netzwerks peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-147">The name of the virtual network peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-149">Löscht das angegebene virtuelle Netzwerk-peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-149">Deletes the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering Get (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering Get(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.Get(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualNetworkPeeringsOperations, resourceGroupName As String, virtualNetworkName As String, virtualNetworkPeeringName As String) As VirtualNetworkPeering" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.Get (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-151">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-152">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-152">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-153">Der Name des virtuellen Netzwerks peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-153">The name of the virtual network peering.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-154">Ruft das angegebene virtuelle Netzwerk-peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-154">Gets the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; GetAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; GetAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, string virtualNetworkPeeringName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.GetAsync (operations, resourceGroupName, virtualNetworkName, virtualNetworkPeeringName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkPeeringName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-156">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-156">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-157">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-157">The name of the virtual network.</span></span>
            </param>
        <param name="virtualNetworkPeeringName">
            <span data-ttu-id="68ee0-158">Der Name des virtuellen Netzwerks peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-158">The name of the virtual network peering.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-159">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-159">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-160">Ruft das angegebene virtuelle Netzwerk-peering.</span><span class="sxs-lookup"><span data-stu-id="68ee0-160">Gets the specified virtual network peering.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; List (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; List(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.List(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualNetworkPeeringsOperations, resourceGroupName As String, virtualNetworkName As String) As IPage(Of VirtualNetworkPeering)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.List (operations, resourceGroupName, virtualNetworkName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-162">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-162">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-163">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-163">The name of the virtual network.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-164">Ruft alle virtuellen Netzwerk über Peerings in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="68ee0-164">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string resourceGroupName, string virtualNetworkName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.ListAsync (operations, resourceGroupName, virtualNetworkName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;ListAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="68ee0-166">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="68ee0-166">The name of the resource group.</span></span>
            </param>
        <param name="virtualNetworkName">
            <span data-ttu-id="68ee0-167">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="68ee0-167">The name of the virtual network.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-169">Ruft alle virtuellen Netzwerk über Peerings in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="68ee0-169">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; ListNext (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; ListNext(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualNetworkPeeringsOperations, nextPageLink As String) As IPage(Of VirtualNetworkPeering)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-170">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="68ee0-171">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="68ee0-171">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-172">Ruft alle virtuellen Netzwerk über Peerings in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="68ee0-172">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;" Usage="Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.VirtualNetworkPeeringsOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IVirtualNetworkPeeringsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="68ee0-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="68ee0-173">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="68ee0-174">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="68ee0-174">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="68ee0-175">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="68ee0-175">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="68ee0-176">Ruft alle virtuellen Netzwerk über Peerings in einem virtuellen Netzwerk an.</span><span class="sxs-lookup"><span data-stu-id="68ee0-176">Gets all virtual network peerings in a virtual network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>