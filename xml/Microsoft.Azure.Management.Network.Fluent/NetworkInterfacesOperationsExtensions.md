<Type Name="NetworkInterfacesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class NetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit NetworkInterfacesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module NetworkInterfacesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type NetworkInterfacesOperationsExtensions = class" />
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
            <span data-ttu-id="3f103-101">Erweiterungsmethoden für NetworkInterfacesOperations.</span><span class="sxs-lookup"><span data-stu-id="3f103-101">Extension methods for NetworkInterfacesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, networkInterfaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-103">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-104">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-104">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3f103-105">Die Parameter des Vorgangs erstellen oder aktualisieren Netzwerk-Schnittstelle angegeben.</span><span class="sxs-lookup"><span data-stu-id="3f103-105">Parameters supplied to the create or update network interface operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-107">Erstellt oder aktualisiert eine Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-107">Creates or updates a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-109">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-110">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-110">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-112">Löscht die angegebene Netzwerkschnittstelle an.</span><span class="sxs-lookup"><span data-stu-id="3f103-112">Deletes the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetEffectiveRouteTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt; BeginGetEffectiveRouteTableAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt; BeginGetEffectiveRouteTableAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginGetEffectiveRouteTableAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginGetEffectiveRouteTableAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginGetEffectiveRouteTableAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;BeginGetEffectiveRouteTableAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-114">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-115">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-115">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-116">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-116">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-117">Ruft alle Routingtabellen mit einer Netzwerkschnittstelle angewendet.</span><span class="sxs-lookup"><span data-stu-id="3f103-117">Gets all route tables applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListEffectiveNetworkSecurityGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt; BeginListEffectiveNetworkSecurityGroupsAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt; BeginListEffectiveNetworkSecurityGroupsAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginListEffectiveNetworkSecurityGroupsAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginListEffectiveNetworkSecurityGroupsAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.BeginListEffectiveNetworkSecurityGroupsAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;BeginListEffectiveNetworkSecurityGroupsAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-118">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-118">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-119">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-119">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-120">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-120">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-122">Ruft alle netzwerksicherheitsgruppen, die mit einer Netzwerkschnittstelle angewendet.</span><span class="sxs-lookup"><span data-stu-id="3f103-122">Gets all network security groups applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, networkInterfaceName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-124">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-124">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-125">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-125">The name of the network interface.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3f103-126">Die Parameter des Vorgangs erstellen oder aktualisieren Netzwerk-Schnittstelle angegeben.</span><span class="sxs-lookup"><span data-stu-id="3f103-126">Parameters supplied to the create or update network interface operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-128">Erstellt oder aktualisiert eine Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-128">Creates or updates a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.DeleteAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;DeleteAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-129">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-130">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-130">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-131">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-131">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-133">Löscht die angegebene Netzwerkschnittstelle an.</span><span class="sxs-lookup"><span data-stu-id="3f103-133">Deletes the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; GetAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; GetAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.GetAsync (operations, resourceGroupName, networkInterfaceName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-135">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-135">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-136">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-136">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3f103-137">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="3f103-137">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-138">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-138">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-139">Ruft Informationen über die angegebene Netzwerkschnittstelle ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-139">Gets information about the specified network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEffectiveRouteTableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt; GetEffectiveRouteTableAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt; GetEffectiveRouteTableAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.GetEffectiveRouteTableAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetEffectiveRouteTableAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.GetEffectiveRouteTableAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;GetEffectiveRouteTableAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveRouteListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-140">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-141">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-141">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-142">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-142">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-144">Ruft alle Routingtabellen mit einer Netzwerkschnittstelle angewendet.</span><span class="sxs-lookup"><span data-stu-id="3f103-144">Gets all route tables applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetVirtualMachineScaleSetNetworkInterfaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; GetVirtualMachineScaleSetNetworkInterfaceAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt; GetVirtualMachineScaleSetNetworkInterfaceAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, string networkInterfaceName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetNetworkInterfaceAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetVirtualMachineScaleSetNetworkInterfaceAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.GetVirtualMachineScaleSetNetworkInterfaceAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, networkInterfaceName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;GetVirtualMachineScaleSetNetworkInterfaceAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-146">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-146">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="3f103-147">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-147">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="3f103-148">Der Index des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="3f103-148">The virtual machine index.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-149">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-149">The name of the network interface.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="3f103-150">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="3f103-150">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-152">Ruft die angegebene Netzwerkschnittstelle in einem VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-152">Get the specified network interface in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListAllAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-153">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-155">Ruft alle Netzwerkschnittstellen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-155">Gets all network interfaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListAllNextAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-156">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3f103-157">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3f103-157">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-158">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-158">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-159">Ruft alle Netzwerkschnittstellen in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-159">Gets all network interfaces in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-160">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-160">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-161">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-161">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-163">Ruft alle Netzwerkschnittstellen in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-163">Gets all network interfaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListEffectiveNetworkSecurityGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt; ListEffectiveNetworkSecurityGroupsAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt; ListEffectiveNetworkSecurityGroupsAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string networkInterfaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListEffectiveNetworkSecurityGroupsAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListEffectiveNetworkSecurityGroupsAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListEffectiveNetworkSecurityGroupsAsync (operations, resourceGroupName, networkInterfaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListEffectiveNetworkSecurityGroupsAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Fluent.Models.EffectiveNetworkSecurityGroupListResultInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="networkInterfaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-165">The name of the resource group.</span></span>
            </param>
        <param name="networkInterfaceName">
            <span data-ttu-id="3f103-166">Der Name der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="3f103-166">The name of the network interface.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-168">Ruft alle netzwerksicherheitsgruppen, die mit einer Netzwerkschnittstelle angewendet.</span><span class="sxs-lookup"><span data-stu-id="3f103-168">Gets all network security groups applied to a network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-169">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3f103-170">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3f103-170">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-172">Ruft alle Netzwerkschnittstellen in einer Ressourcengruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-172">Gets all network interfaces in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetNetworkInterfacesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetNetworkInterfacesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesAsync (operations, resourceGroupName, virtualMachineScaleSetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetNetworkInterfacesAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-174">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-174">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="3f103-175">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-175">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-177">Ruft alle Netzwerkschnittstellen auf einem VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-177">Gets all network interfaces in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetNetworkInterfacesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetNetworkInterfacesNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetNetworkInterfacesNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetNetworkInterfacesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetNetworkInterfacesNextAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-178">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3f103-179">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3f103-179">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-181">Ruft alle Netzwerkschnittstellen auf einem VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-181">Gets all network interfaces in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMNetworkInterfacesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string resourceGroupName, string virtualMachineScaleSetName, string virtualmachineIndex, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMNetworkInterfacesAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesAsync (operations, resourceGroupName, virtualMachineScaleSetName, virtualmachineIndex, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMNetworkInterfacesAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="virtualMachineScaleSetName" Type="System.String" />
        <Parameter Name="virtualmachineIndex" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-182">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f103-183">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-183">The name of the resource group.</span></span>
            </param>
        <param name="virtualMachineScaleSetName">
            <span data-ttu-id="3f103-184">Der Name des VM-Skalierungsgruppe.</span><span class="sxs-lookup"><span data-stu-id="3f103-184">The name of the virtual machine scale set.</span></span>
            </param>
        <param name="virtualmachineIndex">
            <span data-ttu-id="3f103-185">Der Index des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="3f103-185">The virtual machine index.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-187">Ruft Informationen über alle Netzwerkschnittstellen auf einem virtuellen Computer in einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-187">Gets information about all network interfaces in a virtual machine in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync (this Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt; ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync(class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync(Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync : Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions.ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.Fluent.NetworkInterfacesOperationsExtensions/&lt;ListVirtualMachineScaleSetVMNetworkInterfacesNextAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Fluent.Models.NetworkInterfaceInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f103-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f103-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3f103-189">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3f103-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f103-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f103-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f103-191">Ruft Informationen über alle Netzwerkschnittstellen auf einem virtuellen Computer in einer VM-Skalierungsgruppe ab.</span><span class="sxs-lookup"><span data-stu-id="3f103-191">Gets information about all network interfaces in a virtual machine in a virtual machine scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>