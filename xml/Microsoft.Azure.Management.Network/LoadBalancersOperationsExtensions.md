<Type Name="LoadBalancersOperationsExtensions" FullName="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LoadBalancersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LoadBalancersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LoadBalancersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LoadBalancersOperationsExtensions = class" />
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
            <span data-ttu-id="2c2ed-101">Erweiterungsmethoden für LoadBalancersOperations.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-101">Extension methods for LoadBalancersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As LoadBalancer) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-104">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-104">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-105">Die Parameter des erstellen oder aktualisieren Load Balancer-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-105">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-106">Erstellt oder aktualisiert einen Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-106">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-107">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-108">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-108">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-109">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-109">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-110">Die Parameter des erstellen oder aktualisieren Load Balancer-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-110">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-112">Erstellt oder aktualisiert einen Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-112">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDelete (operations, resourceGroupName, loadBalancerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-113">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-114">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-114">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-115">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-115">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-116">Löscht das angegebene Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-116">Deletes the specified load balancer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-118">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-118">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-119">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-119">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-121">Löscht das angegebene Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-121">Deletes the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer BeginUpdateTags (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer BeginUpdateTags(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTags(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateTags (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As TagsObject) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTags : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTags (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-123">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-123">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-124">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-124">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-125">Parameter, die zum Aktualisieren der Load Balancer-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-125">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-126">Aktualisiert eine Load Balancer-Tags.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-126">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginUpdateTagsAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; BeginUpdateTagsAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTagsAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateTagsAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.BeginUpdateTagsAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;BeginUpdateTagsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-127">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-128">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-128">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-129">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-129">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-130">Parameter, die zum Aktualisieren der Load Balancer-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-130">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-131">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-131">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-132">Aktualisiert eine Load Balancer-Tags.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-132">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer CreateOrUpdate (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer CreateOrUpdate(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As LoadBalancer) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-133">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-133">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-134">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-134">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-135">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-135">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-136">Die Parameter des erstellen oder aktualisieren Load Balancer-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-136">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-137">Erstellt oder aktualisiert einen Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-137">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.LoadBalancer parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.LoadBalancer,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.LoadBalancer * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.LoadBalancer" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-138">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-139">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-139">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-140">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-140">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-141">Die Parameter des erstellen oder aktualisieren Load Balancer-Vorgangs angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-141">Parameters supplied to the create or update load balancer operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-143">Erstellt oder aktualisiert einen Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-143">Creates or updates a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Delete(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Delete (operations, resourceGroupName, loadBalancerName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-145">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-146">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-146">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-147">Löscht das angegebene Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-147">Deletes the specified load balancer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.DeleteAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;DeleteAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-148">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-149">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-149">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-150">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-150">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-152">Löscht das angegebene Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-152">Deletes the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer Get (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer Get(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Get(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, Optional expand As String = null) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-154">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-154">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-155">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-155">The name of the load balancer.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="2c2ed-156">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-156">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-157">Ruft das angegebene Lastenausgleichsmodul ab.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-157">Gets the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; GetAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; GetAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-159">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-159">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-160">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-160">The name of the load balancer.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="2c2ed-161">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-161">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-163">Ruft das angegebene Lastenausgleichsmodul ab.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-163">Gets the specified load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; List (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; List(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.List(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As ILoadBalancersOperations, resourceGroupName As String) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-165">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-165">The name of the resource group.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-166">Ruft alle Lastenausgleichsmodule in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-166">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAll (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAll(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAll(Microsoft.Azure.Management.Network.ILoadBalancersOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As ILoadBalancersOperations) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Network.ILoadBalancersOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-167">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-168">Ruft alle Lastenausgleichsmodule in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-168">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListAllAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-169">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-171">Ruft alle Lastenausgleichsmodule in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-171">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAllNext (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListAllNext(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As ILoadBalancersOperations, nextPageLink As String) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2c2ed-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-174">Ruft alle Lastenausgleichsmodule in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-174">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListAllNextAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2c2ed-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-178">Ruft alle Lastenausgleichsmodule in einem Abonnement ab.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-178">Gets all the load balancers in a subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-179">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-180">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-180">The name of the resource group.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-182">Ruft alle Lastenausgleichsmodule in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-182">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListNext (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; ListNext(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As ILoadBalancersOperations, nextPageLink As String) As IPage(Of LoadBalancer)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-183">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2c2ed-184">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-184">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-185">Ruft alle Lastenausgleichsmodule in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-185">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-186">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="2c2ed-187">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-187">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-189">Ruft alle Lastenausgleichsmodule in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-189">Gets all the load balancers in a resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTags">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.LoadBalancer UpdateTags (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.LoadBalancer UpdateTags(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTags(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateTags (operations As ILoadBalancersOperations, resourceGroupName As String, loadBalancerName As String, parameters As TagsObject) As LoadBalancer" />
      <MemberSignature Language="F#" Value="static member UpdateTags : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTags (operations, resourceGroupName, loadBalancerName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-190">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-190">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-191">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-191">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-192">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-192">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-193">Parameter, die zum Aktualisieren der Load Balancer-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-193">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-194">Aktualisiert eine Load Balancer-Tags.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-194">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTagsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; UpdateTagsAsync (this Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, Microsoft.Azure.Management.Network.Models.TagsObject parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancer&gt; UpdateTagsAsync(class Microsoft.Azure.Management.Network.ILoadBalancersOperations operations, string resourceGroupName, string loadBalancerName, class Microsoft.Azure.Management.Network.Models.TagsObject parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTagsAsync(Microsoft.Azure.Management.Network.ILoadBalancersOperations,System.String,System.String,Microsoft.Azure.Management.Network.Models.TagsObject,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateTagsAsync : Microsoft.Azure.Management.Network.ILoadBalancersOperations * string * string * Microsoft.Azure.Management.Network.Models.TagsObject * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;" Usage="Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions.UpdateTagsAsync (operations, resourceGroupName, loadBalancerName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.LoadBalancersOperationsExtensions/&lt;UpdateTagsAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.LoadBalancer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.ILoadBalancersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Network.Models.TagsObject" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2c2ed-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="2c2ed-196">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-196">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="2c2ed-197">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-197">The name of the load balancer.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="2c2ed-198">Parameter, die zum Aktualisieren der Load Balancer-Tags angegeben.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-198">Parameters supplied to update load balancer tags.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2c2ed-199">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-199">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2c2ed-200">Aktualisiert eine Load Balancer-Tags.</span><span class="sxs-lookup"><span data-stu-id="2c2ed-200">Updates a load balancer tags.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>