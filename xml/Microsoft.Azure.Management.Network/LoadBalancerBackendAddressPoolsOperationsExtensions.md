<Type Name="LoadBalancerBackendAddressPoolsOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancerBackendAddressPoolsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancerBackendAddressPoolsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancerBackendAddressPoolsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancerBackendAddressPoolsOperationsExtensions = class" />
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
            <span data-ttu-id="7087f-101">Erweiterungsmethoden für LoadBalancerBackendAddressPoolsOperations.</span><span class="sxs-lookup"><span data-stu-id="7087f-101">Extension methods for LoadBalancerBackendAddressPoolsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.BackendAddressPool Get (this Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName, string backendAddressPoolName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.BackendAddressPool Get(class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName, string backendAddressPoolName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILoadBalancerBackendAddressPoolsOperations, resourceGroupName As String, loadBalancerName As String, backendAddressPoolName As String) As BackendAddressPool" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.BackendAddressPool" Usage="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, backendAddressPoolName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BackendAddressPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="backendAddressPoolName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7087f-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7087f-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7087f-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7087f-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="7087f-104">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="7087f-104">The name of the load balancer.</span></span>
            </param>
        <param name="backendAddressPoolName">
            <span data-ttu-id="7087f-105">Der Name des Back-End-Adresspool.</span><span class="sxs-lookup"><span data-stu-id="7087f-105">The name of the backend address pool.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7087f-106">Ruft Laden des Lastenausgleichsmoduls Back-End-Adresspool.</span><span class="sxs-lookup"><span data-stu-id="7087f-106">Gets load balancer backend address pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; GetAsync (this Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName, string backendAddressPoolName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; GetAsync(class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName, string backendAddressPoolName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, backendAddressPoolName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="backendAddressPoolName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7087f-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7087f-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7087f-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7087f-108">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="7087f-109">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="7087f-109">The name of the load balancer.</span></span>
            </param>
        <param name="backendAddressPoolName">
            <span data-ttu-id="7087f-110">Der Name des Back-End-Adresspool.</span><span class="sxs-lookup"><span data-stu-id="7087f-110">The name of the backend address pool.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7087f-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7087f-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7087f-112">Ruft Laden des Lastenausgleichsmoduls Back-End-Adresspool.</span><span class="sxs-lookup"><span data-stu-id="7087f-112">Gets load balancer backend address pool.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancerBackendAddressPoolsOperations, resourceGroupName As String, loadBalancerName As String) As IPage(Of BackendAddressPool)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.List (operations, resourceGroupName, loadBalancerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7087f-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7087f-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7087f-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7087f-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="7087f-115">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="7087f-115">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7087f-116">Ruft alle Load Balancer gesichert-Adresspools an.</span><span class="sxs-lookup"><span data-stu-id="7087f-116">Gets all the load balancer backed address pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.ListAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7087f-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7087f-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="7087f-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="7087f-118">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="7087f-119">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="7087f-119">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7087f-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7087f-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7087f-121">Ruft alle Load Balancer gesichert-Adresspools an.</span><span class="sxs-lookup"><span data-stu-id="7087f-121">Gets all the load balancer backed address pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancerBackendAddressPoolsOperations, nextPageLink As String) As IPage(Of BackendAddressPool)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7087f-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7087f-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7087f-123">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7087f-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7087f-124">Ruft alle Load Balancer gesichert-Adresspools an.</span><span class="sxs-lookup"><span data-stu-id="7087f-124">Gets all the load balancer backed address pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerBackendAddressPoolsOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerBackendAddressPoolsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7087f-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="7087f-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="7087f-126">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7087f-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7087f-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7087f-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7087f-128">Ruft alle Load Balancer gesichert-Adresspools an.</span><span class="sxs-lookup"><span data-stu-id="7087f-128">Gets all the load balancer backed address pools.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>