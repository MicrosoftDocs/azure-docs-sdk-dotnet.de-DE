<Type Name="ServersOperationsExtensions" FullName="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ServersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ServersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ServersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ServersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c2f5c-101">Erweiterungsmethoden für ServersOperations.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-101">Extension methods for ServersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, serverName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-103">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-103">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-104">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-104">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-105">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-105">The name of the Azure SQL server.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c2f5c-106">Die erforderlichen Parameter zum Erstellen oder Aktualisieren eines Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-106">The required parameters for creating or updating a server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-108">Erstellt einen neuen Azure SQL-Server an.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-108">Creates a new Azure SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateFirewallRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; CreateOrUpdateFirewallRuleAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; CreateOrUpdateFirewallRuleAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateFirewallRuleAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateFirewallRuleAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.CreateOrUpdateFirewallRuleAsync (operations, resourceGroupName, serverName, firewallRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;CreateOrUpdateFirewallRuleAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-110">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-110">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-111">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-111">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-112">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-112">The name of the Azure SQL server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="c2f5c-113">Der Name der Firewallregel für Azure SQL-Server.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-113">The name of the Azure SQL server firewall rule.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c2f5c-114">Die erforderlichen Parameter zum Erstellen oder Aktualisieren einer Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-114">The required parameters for creating or updating a firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-116">Erstellt oder aktualisiert eine Firewallregel für Azure SQL-Server.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-116">Creates or updates an Azure SQL server firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;DeleteAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-118">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-118">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-119">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-119">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-120">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-120">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-121">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-121">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-122">Löscht eine SQL Server-Instanz.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-122">Deletes a SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteFirewallRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteFirewallRuleAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteFirewallRuleAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteFirewallRuleAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteFirewallRuleAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.DeleteFirewallRuleAsync (operations, resourceGroupName, serverName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;DeleteFirewallRuleAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-124">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-124">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-125">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-125">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-126">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-126">The name of the Azure SQL server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="c2f5c-127">Der Name der Firewallregel für Azure SQL-Server.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-127">The name of the Azure SQL server firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-129">Löscht eine Firewallregel für Azure SQL-Server an.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-129">Deletes an Azure SQL server firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; GetByResourceGroupAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt; GetByResourceGroupAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetByResourceGroupAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetByResourceGroupAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetByResourceGroupAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;GetByResourceGroupAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-133">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-133">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-135">Ruft Informationen zu einer Azure SQL-Server ab.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-135">Gets information about an Azure SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFirewallRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; GetFirewallRuleAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt; GetFirewallRuleAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string firewallRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetFirewallRuleAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFirewallRuleAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetFirewallRuleAsync (operations, resourceGroupName, serverName, firewallRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;GetFirewallRuleAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-137">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-138">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-139">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-139">The name of the Azure SQL server.</span></span>
            </param>
        <param name="firewallRuleName">
            <span data-ttu-id="c2f5c-140">Der Name der Firewallregel für Azure SQL-Server.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-140">The name of the Azure SQL server firewall rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-142">Gibt eine Azure SQL-Server-Firewallregel zurück.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-142">Returns an Azure SQL server firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceObjectiveAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt; GetServiceObjectiveAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string serviceObjectiveName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt; GetServiceObjectiveAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, string serviceObjectiveName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetServiceObjectiveAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetServiceObjectiveAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.GetServiceObjectiveAsync (operations, resourceGroupName, serverName, serviceObjectiveName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;GetServiceObjectiveAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="serviceObjectiveName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-144">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-145">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-146">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-146">The name of the Azure SQL server.</span></span>
            </param>
        <param name="serviceObjectiveName">
            <span data-ttu-id="c2f5c-147">Der Name des dienstziels, das abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-147">The name of the service objective to retrieve.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-149">Ruft Informationen zu einer Azure SQL-Datenbank Dienstziel ab.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-149">Gets information about an Azure SQL database Service Objective.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-150">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-151">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-151">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-152">Informationen zu einer Azure SQL Server zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-152">Returns information about an Azure SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-153">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-154">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-154">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-155">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-155">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-157">Informationen zu einer Azure SQL Server zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-157">Returns information about an Azure SQL server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListFirewallRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt; ListFirewallRulesAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt; ListFirewallRulesAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListFirewallRulesAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListFirewallRulesAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListFirewallRulesAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListFirewallRulesAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-159">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-159">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-160">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-160">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-161">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-161">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-163">Gibt eine Liste von Firewallregeln für Azure SQL-Server zurück.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-163">Returns a list of Azure SQL server firewall rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListServiceObjectivesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt; ListServiceObjectivesAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt; ListServiceObjectivesAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListServiceObjectivesAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListServiceObjectivesAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListServiceObjectivesAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListServiceObjectivesAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServiceObjectiveInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-165">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-165">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-166">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-166">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-167">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-167">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-169">Gibt Informationen zu Azure SQL-Datenbank Dienstziele zurück.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-169">Returns information about Azure SQL database Service Objectives.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListUsagesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt; ListUsagesAsync (this Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt; ListUsagesAsync(class Microsoft.Azure.Management.Sql.Fluent.IServersOperations operations, string resourceGroupName, string serverName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListUsagesAsync(Microsoft.Azure.Management.Sql.Fluent.IServersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListUsagesAsync : Microsoft.Azure.Management.Sql.Fluent.IServersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt;" Usage="Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions.ListUsagesAsync (operations, resourceGroupName, serverName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Sql.Fluent.ServersOperationsExtensions/&lt;ListUsagesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerMetric&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Sql.Fluent.IServersOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c2f5c-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-170">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c2f5c-171">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-171">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="c2f5c-172">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-172">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="c2f5c-173">Der Name des Azure SQL-Servers.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-173">The name of the Azure SQL server.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c2f5c-174">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-174">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c2f5c-175">Informationen zur Verwendung von Azure SQL-Server zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c2f5c-175">Returns information about Azure SQL server usage.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>