<Type Name="VirtualNetworkRulesOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualNetworkRulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualNetworkRulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualNetworkRulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualNetworkRulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e4993-101">Erweiterungsmethoden für VirtualNetworkRulesOperations.</span><span class="sxs-lookup"><span data-stu-id="e4993-101">Extension methods for VirtualNetworkRulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule BeginCreateOrUpdate (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule BeginCreateOrUpdate(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualNetworkRulesOperations, resourceGroupName As String, serverName As String, virtualNetworkRuleName As String, parameters As VirtualNetworkRule) As VirtualNetworkRule" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule -&gt; Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, serverName, virtualNetworkRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-105">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-105">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-106">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-106">The name of the virtual network rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4993-107">Der angeforderte virtuelle Regel Netzwerkressource-Status.</span><span class="sxs-lookup"><span data-stu-id="e4993-107">The requested virtual Network Rule Resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-108">Erstellt oder aktualisiert eine vorhandene virtuelle Netzwerk-Regel.</span><span class="sxs-lookup"><span data-stu-id="e4993-108">Creates or updates an existing virtual network rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, serverName, virtualNetworkRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-112">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-112">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-113">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-113">The name of the virtual network rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4993-114">Der angeforderte virtuelle Regel Netzwerkressource-Status.</span><span class="sxs-lookup"><span data-stu-id="e4993-114">The requested virtual Network Rule Resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-116">Erstellt oder aktualisiert eine vorhandene virtuelle Netzwerk-Regel.</span><span class="sxs-lookup"><span data-stu-id="e4993-116">Creates or updates an existing virtual network rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVirtualNetworkRulesOperations, resourceGroupName As String, serverName As String, virtualNetworkRuleName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginDelete (operations, resourceGroupName, serverName, virtualNetworkRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-120">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-120">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-121">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-121">The name of the virtual network rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-122">Löscht die virtuelle Netzwerkregel mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="e4993-122">Deletes the virtual network rule with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, serverName, virtualNetworkRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-126">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-126">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-127">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-127">The name of the virtual network rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-129">Löscht die virtuelle Netzwerkregel mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="e4993-129">Deletes the virtual network rule with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule CreateOrUpdate (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule CreateOrUpdate(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualNetworkRulesOperations, resourceGroupName As String, serverName As String, virtualNetworkRuleName As String, parameters As VirtualNetworkRule) As VirtualNetworkRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule -&gt; Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, serverName, virtualNetworkRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-133">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-133">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-134">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-134">The name of the virtual network rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4993-135">Der angeforderte virtuelle Regel Netzwerkressource-Status.</span><span class="sxs-lookup"><span data-stu-id="e4993-135">The requested virtual Network Rule Resource state.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-136">Erstellt oder aktualisiert eine vorhandene virtuelle Netzwerk-Regel.</span><span class="sxs-lookup"><span data-stu-id="e4993-136">Creates or updates an existing virtual network rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, virtualNetworkRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-138">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-138">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-139">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-139">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-140">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-140">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-141">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-141">The name of the virtual network rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="e4993-142">Der angeforderte virtuelle Regel Netzwerkressource-Status.</span><span class="sxs-lookup"><span data-stu-id="e4993-142">The requested virtual Network Rule Resource state.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-144">Erstellt oder aktualisiert eine vorhandene virtuelle Netzwerk-Regel.</span><span class="sxs-lookup"><span data-stu-id="e4993-144">Creates or updates an existing virtual network rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.Delete(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVirtualNetworkRulesOperations, resourceGroupName As String, serverName As String, virtualNetworkRuleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.Delete (operations, resourceGroupName, serverName, virtualNetworkRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-145">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-146">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-146">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-147">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-147">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-148">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-148">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-149">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-149">The name of the virtual network rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-150">Löscht die virtuelle Netzwerkregel mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="e4993-150">Deletes the virtual network rule with the given name.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, virtualNetworkRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-152">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-153">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-154">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-154">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-155">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-155">The name of the virtual network rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-157">Löscht die virtuelle Netzwerkregel mit dem angegebenen Namen.</span><span class="sxs-lookup"><span data-stu-id="e4993-157">Deletes the virtual network rule with the given name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule Get (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule Get(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.Get(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualNetworkRulesOperations, resourceGroupName As String, serverName As String, virtualNetworkRuleName As String) As VirtualNetworkRule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string -&gt; Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.Get (operations, resourceGroupName, serverName, virtualNetworkRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-159">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-160">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-161">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-161">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-162">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-162">The name of the virtual network rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-163">Ruft ein virtuelles Netzwerk-Regel ab.</span><span class="sxs-lookup"><span data-stu-id="e4993-163">Gets a virtual network rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; GetAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; GetAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, string virtualNetworkRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.GetAsync (operations, resourceGroupName, serverName, virtualNetworkRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="virtualNetworkRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-165">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-166">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-167">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-167">The name of the server.</span></span>
            </param>
        <param name="virtualNetworkRuleName">
            <span data-ttu-id="e4993-168">Der Name des virtuellen Netzwerkregel.</span><span class="sxs-lookup"><span data-stu-id="e4993-168">The name of the virtual network rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-170">Ruft ein virtuelles Netzwerk-Regel ab.</span><span class="sxs-lookup"><span data-stu-id="e4993-170">Gets a virtual network rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServer">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; ListByServer (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; ListByServer(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServer(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServer (operations As IVirtualNetworkRulesOperations, resourceGroupName As String, serverName As String) As IPage(Of VirtualNetworkRule)" />
      <MemberSignature Language="F#" Value="static member ListByServer : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServer (operations, resourceGroupName, serverName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-172">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-172">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-173">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-173">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-174">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-174">The name of the server.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-175">Ruft eine Liste von virtuellen Netzwerkregeln in einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="e4993-175">Gets a list of virtual network rules in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt; ListByServerAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt; ListByServerAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServerAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServerAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;ListByServerAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-176">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="e4993-177">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="e4993-177">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="e4993-178">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="e4993-178">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="e4993-179">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="e4993-179">The name of the server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-181">Ruft eine Liste von virtuellen Netzwerkregeln in einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="e4993-181">Gets a list of virtual network rules in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; ListByServerNext (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt; ListByServerNext(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServerNext(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByServerNext (operations As IVirtualNetworkRulesOperations, nextPageLink As String) As IPage(Of VirtualNetworkRule)" />
      <MemberSignature Language="F#" Value="static member ListByServerNext : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServerNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-182">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4993-183">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4993-183">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-184">Ruft eine Liste von virtuellen Netzwerkregeln in einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="e4993-184">Gets a list of virtual network rules in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByServerNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt; ListByServerNextAsync (this Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt; ListByServerNextAsync(class Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServerNextAsync(Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByServerNextAsync : Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions.ListByServerNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.VirtualNetworkRulesOperationsExtensions/&lt;ListByServerNextAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Sql.Models.VirtualNetworkRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.IVirtualNetworkRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="e4993-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="e4993-185">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="e4993-186">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="e4993-186">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="e4993-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="e4993-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="e4993-188">Ruft eine Liste von virtuellen Netzwerkregeln in einen Server ab.</span><span class="sxs-lookup"><span data-stu-id="e4993-188">Gets a list of virtual network rules in a server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>