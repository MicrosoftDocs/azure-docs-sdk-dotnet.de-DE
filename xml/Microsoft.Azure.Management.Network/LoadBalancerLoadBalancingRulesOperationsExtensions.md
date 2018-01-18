<Type Name="LoadBalancerLoadBalancingRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancerLoadBalancingRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancerLoadBalancingRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancerLoadBalancingRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancerLoadBalancingRulesOperationsExtensions = class" />
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
            <span data-ttu-id="1734d-101">Erweiterungsmethoden für LoadBalancerLoadBalancingRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="1734d-101">Extension methods for LoadBalancerLoadBalancingRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancingRule Get (this Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName, string loadBalancingRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancingRule Get(class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName, string loadBalancingRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILoadBalancerLoadBalancingRulesOperations, resourceGroupName As String, loadBalancerName As String, loadBalancingRuleName As String) As LoadBalancingRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancingRule" Usage="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, loadBalancingRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancingRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="loadBalancingRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1734d-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1734d-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1734d-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1734d-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="1734d-104">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="1734d-104">The name of the load balancer.</span></span>
            </param>
        <param name="loadBalancingRuleName">
            <span data-ttu-id="1734d-105">Der Name des der lastenausgleichsregel.</span><span class="sxs-lookup"><span data-stu-id="1734d-105">The name of the load balancing rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1734d-106">Ruft die angegebene lastenausgleichsregel ab.</span><span class="sxs-lookup"><span data-stu-id="1734d-106">Gets the specified load balancer load balancing rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; GetAsync (this Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName, string loadBalancingRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; GetAsync(class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName, string loadBalancingRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, loadBalancingRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="loadBalancingRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1734d-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1734d-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1734d-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1734d-108">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="1734d-109">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="1734d-109">The name of the load balancer.</span></span>
            </param>
        <param name="loadBalancingRuleName">
            <span data-ttu-id="1734d-110">Der Name des der lastenausgleichsregel.</span><span class="sxs-lookup"><span data-stu-id="1734d-110">The name of the load balancing rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1734d-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1734d-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1734d-112">Ruft die angegebene lastenausgleichsregel ab.</span><span class="sxs-lookup"><span data-stu-id="1734d-112">Gets the specified load balancer load balancing rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancerLoadBalancingRulesOperations, resourceGroupName As String, loadBalancerName As String) As IPage(Of LoadBalancingRule)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.List (operations, resourceGroupName, loadBalancerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1734d-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1734d-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1734d-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1734d-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="1734d-115">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="1734d-115">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1734d-116">Ruft alle lastenausgleichsregeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="1734d-116">Gets all the load balancing rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.ListAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1734d-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1734d-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1734d-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="1734d-118">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="1734d-119">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="1734d-119">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1734d-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1734d-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1734d-121">Ruft alle lastenausgleichsregeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="1734d-121">Gets all the load balancing rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancerLoadBalancingRulesOperations, nextPageLink As String) As IPage(Of LoadBalancingRule)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1734d-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1734d-122">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1734d-123">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1734d-123">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1734d-124">Ruft alle lastenausgleichsregeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="1734d-124">Gets all the load balancing rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancerLoadBalancingRulesOperationsExtensions/&lt;ListNextAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancerLoadBalancingRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1734d-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="1734d-125">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="1734d-126">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="1734d-126">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1734d-127">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1734d-127">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1734d-128">Ruft alle lastenausgleichsregeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="1734d-128">Gets all the load balancing rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>