<Type Name="InboundNatRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class InboundNatRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit InboundNatRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module InboundNatRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type InboundNatRulesOperationsExtensions = class" />
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
            <span data-ttu-id="5d304-101">Erweiterungsmethoden für InboundNatRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="5d304-101">Extension methods for InboundNatRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.InboundNatRule BeginCreateOrUpdate (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.InboundNatRule BeginCreateOrUpdate(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, class Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.InboundNatRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IInboundNatRulesOperations, resourceGroupName As String, loadBalancerName As String, inboundNatRuleName As String, inboundNatRuleParameters As InboundNatRule) As InboundNatRule" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.InboundNatRule -&gt; Microsoft.Azure.Management.Network.Models.InboundNatRule" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, inboundNatRuleParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.InboundNatRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="inboundNatRuleParameters" Type="Microsoft.Azure.Management.Network.Models.InboundNatRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-103">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-103">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-104">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-104">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-105">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-105">The name of the inbound nat rule.</span></span>
            </param>
        <param name="inboundNatRuleParameters">
            <span data-ttu-id="5d304-106">So erstellen Sie den angegebenen Parametern oder Aktualisierungsvorgang für eingehende Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-106">Parameters supplied to the create or update inbound nat rule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-107">Erstellt oder aktualisiert eine eingehende Nat-Regel für Load Balancers.</span><span class="sxs-lookup"><span data-stu-id="5d304-107">Creates or updates a load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, class Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.InboundNatRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.InboundNatRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, inboundNatRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="inboundNatRuleParameters" Type="Microsoft.Azure.Management.Network.Models.InboundNatRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-109">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-109">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-110">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-110">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-111">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-111">The name of the inbound nat rule.</span></span>
            </param>
        <param name="inboundNatRuleParameters">
            <span data-ttu-id="5d304-112">So erstellen Sie den angegebenen Parametern oder Aktualisierungsvorgang für eingehende Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-112">Parameters supplied to the create or update inbound nat rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-114">Erstellt oder aktualisiert eine eingehende Nat-Regel für Load Balancers.</span><span class="sxs-lookup"><span data-stu-id="5d304-114">Creates or updates a load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IInboundNatRulesOperations, resourceGroupName As String, loadBalancerName As String, inboundNatRuleName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginDelete (operations, resourceGroupName, loadBalancerName, inboundNatRuleName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-116">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-116">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-117">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-117">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-118">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-118">The name of the inbound nat rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-119">Löscht das angegebene Lastenausgleichsmodul eingehende Nat-Regel an.</span><span class="sxs-lookup"><span data-stu-id="5d304-119">Deletes the specified load balancer inbound nat rule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-120">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-121">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-121">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-122">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-122">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-123">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-123">The name of the inbound nat rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-124">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-124">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-125">Löscht das angegebene Lastenausgleichsmodul eingehende Nat-Regel an.</span><span class="sxs-lookup"><span data-stu-id="5d304-125">Deletes the specified load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.InboundNatRule CreateOrUpdate (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.InboundNatRule CreateOrUpdate(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, class Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.InboundNatRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IInboundNatRulesOperations, resourceGroupName As String, loadBalancerName As String, inboundNatRuleName As String, inboundNatRuleParameters As InboundNatRule) As InboundNatRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.InboundNatRule -&gt; Microsoft.Azure.Management.Network.Models.InboundNatRule" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, inboundNatRuleParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.InboundNatRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="inboundNatRuleParameters" Type="Microsoft.Azure.Management.Network.Models.InboundNatRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-127">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-127">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-128">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-128">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-129">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-129">The name of the inbound nat rule.</span></span>
            </param>
        <param name="inboundNatRuleParameters">
            <span data-ttu-id="5d304-130">So erstellen Sie den angegebenen Parametern oder Aktualisierungsvorgang für eingehende Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-130">Parameters supplied to the create or update inbound nat rule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-131">Erstellt oder aktualisiert eine eingehende Nat-Regel für Load Balancers.</span><span class="sxs-lookup"><span data-stu-id="5d304-131">Creates or updates a load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, class Microsoft.Azure.Management.Network.Models.InboundNatRule inboundNatRuleParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.InboundNatRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * Microsoft.Azure.Management.Network.Models.InboundNatRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, inboundNatRuleParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="inboundNatRuleParameters" Type="Microsoft.Azure.Management.Network.Models.InboundNatRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-133">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-133">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-134">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-134">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-135">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-135">The name of the inbound nat rule.</span></span>
            </param>
        <param name="inboundNatRuleParameters">
            <span data-ttu-id="5d304-136">So erstellen Sie den angegebenen Parametern oder Aktualisierungsvorgang für eingehende Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-136">Parameters supplied to the create or update inbound nat rule operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-137">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-137">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-138">Erstellt oder aktualisiert eine eingehende Nat-Regel für Load Balancers.</span><span class="sxs-lookup"><span data-stu-id="5d304-138">Creates or updates a load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.Delete(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IInboundNatRulesOperations, resourceGroupName As String, loadBalancerName As String, inboundNatRuleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.Delete (operations, resourceGroupName, loadBalancerName, inboundNatRuleName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-139">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-140">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-140">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-141">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-141">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-142">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-142">The name of the inbound nat rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-143">Löscht das angegebene Lastenausgleichsmodul eingehende Nat-Regel an.</span><span class="sxs-lookup"><span data-stu-id="5d304-143">Deletes the specified load balancer inbound nat rule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-144">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-144">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-145">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-145">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-146">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-146">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-147">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-147">The name of the inbound nat rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-149">Löscht das angegebene Lastenausgleichsmodul eingehende Nat-Regel an.</span><span class="sxs-lookup"><span data-stu-id="5d304-149">Deletes the specified load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Models.InboundNatRule Get (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Models.InboundNatRule Get(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.Get(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IInboundNatRulesOperations, resourceGroupName As String, loadBalancerName As String, inboundNatRuleName As String, Optional expand As String = null) As InboundNatRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.InboundNatRule" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.Get (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.InboundNatRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-151">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-152">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-152">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-153">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-153">The name of the inbound nat rule.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="5d304-154">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="5d304-154">Expands referenced resources.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-155">Ruft ab, die das angegebene Lastenausgleichsmodul eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-155">Gets the specified load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; GetAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; GetAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, string inboundNatRuleName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.GetAsync (operations, resourceGroupName, loadBalancerName, inboundNatRuleName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-157">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-157">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-158">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-158">The name of the load balancer.</span></span>
            </param>
        <param name="inboundNatRuleName">
            <span data-ttu-id="5d304-159">Der Name der eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-159">The name of the inbound nat rule.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="5d304-160">Wird erweitert, referenzierte Ressourcen.</span><span class="sxs-lookup"><span data-stu-id="5d304-160">Expands referenced resources.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-162">Ruft ab, die das angegebene Lastenausgleichsmodul eingehenden Nat-Regel.</span><span class="sxs-lookup"><span data-stu-id="5d304-162">Gets the specified load balancer inbound nat rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; List (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; List(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.List(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IInboundNatRulesOperations, resourceGroupName As String, loadBalancerName As String) As IPage(Of InboundNatRule)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.List (operations, resourceGroupName, loadBalancerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-163">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-164">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-164">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-165">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-165">The name of the load balancer.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-166">Ruft die eingehende Nat-Regeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="5d304-166">Gets all the inbound nat rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt; ListAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt; ListAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string resourceGroupName, string loadBalancerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.ListAsync (operations, resourceGroupName, loadBalancerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="loadBalancerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5d304-168">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="5d304-168">The name of the resource group.</span></span>
            </param>
        <param name="loadBalancerName">
            <span data-ttu-id="5d304-169">Der Name des Lastenausgleichs.</span><span class="sxs-lookup"><span data-stu-id="5d304-169">The name of the load balancer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-171">Ruft die eingehende Nat-Regeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="5d304-171">Gets all the inbound nat rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; ListNext (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; ListNext(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.ListNext(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IInboundNatRulesOperations, nextPageLink As String) As IPage(Of InboundNatRule)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-172">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-172">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5d304-173">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5d304-173">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-174">Ruft die eingehende Nat-Regeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="5d304-174">Gets all the inbound nat rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Network.IInboundNatRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Network.IInboundNatRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Network.IInboundNatRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt;" Usage="Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Network.InboundNatRulesOperationsExtensions/&lt;ListNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Network.IInboundNatRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5d304-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="5d304-175">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="5d304-176">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="5d304-176">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5d304-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5d304-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5d304-178">Ruft die eingehende Nat-Regeln in einen Load Balancer ab.</span><span class="sxs-lookup"><span data-stu-id="5d304-178">Gets all the inbound nat rules in a load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>