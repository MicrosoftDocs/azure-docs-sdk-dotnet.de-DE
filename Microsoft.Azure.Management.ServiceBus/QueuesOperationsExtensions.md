<Type Name="QueuesOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class QueuesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit QueuesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module QueuesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type QueuesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="62d20-101">Erweiterungsmethoden für QueuesOperations.</span><span class="sxs-lookup"><span data-stu-id="62d20-101">Extension methods for QueuesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBQueue CreateOrUpdate (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, Microsoft.Azure.Management.ServiceBus.Models.SBQueue parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBQueue CreateOrUpdate(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, class Microsoft.Azure.Management.ServiceBus.Models.SBQueue parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBQueue)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String, parameters As SBQueue) As SBQueue" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBQueue -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBQueue" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, queueName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBQueue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBQueue" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-104">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-104">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-105">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-105">The queue name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d20-106">Parameter, die zum Erstellen oder Aktualisieren einer Warteschlangenressource angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="62d20-106">Parameters supplied to create or update a queue resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-107">Erstellt oder aktualisiert eine Service Bus-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-107">Creates or updates a Service Bus queue.</span></span> <span data-ttu-id="62d20-108">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="62d20-108">This operation is idempotent.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639395.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, Microsoft.Azure.Management.ServiceBus.Models.SBQueue parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, class Microsoft.Azure.Management.ServiceBus.Models.SBQueue parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBQueue,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBQueue * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, queueName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBQueue" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-110">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-110">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-111">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-111">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-112">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-112">The queue name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d20-113">Parameter, die zum Erstellen oder Aktualisieren einer Warteschlangenressource angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="62d20-113">Parameters supplied to create or update a queue resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-114">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-114">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-115">Erstellt oder aktualisiert eine Service Bus-Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-115">Creates or updates a Service Bus queue.</span></span> <span data-ttu-id="62d20-116">Dieser Vorgang ist Idempotent.</span><span class="sxs-lookup"><span data-stu-id="62d20-116">This operation is idempotent.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639395.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String, authorizationRuleName As String, parameters As SBAuthorizationRule) As SBAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-118">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-118">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-119">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-119">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-120">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-120">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-121">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-121">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d20-122">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="62d20-122">The shared access authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-123">Erstellt eine Autorisierungsregel für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-123">Creates an authorization rule for a queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-124">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-124">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-125">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-125">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-126">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-126">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-127">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-127">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-128">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-128">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d20-129">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="62d20-129">The shared access authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-131">Erstellt eine Autorisierungsregel für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-131">Creates an authorization rule for a queue.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, queueName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-132">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-133">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-133">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-134">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-134">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-135">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-135">The queue name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-136">Löscht eine Warteschlange aus dem angegebenen Namespace in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="62d20-136">Deletes a queue from the specified namespace in a resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639411.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, queueName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-137">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-138">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-138">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-139">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-139">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-140">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-140">The queue name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-142">Löscht eine Warteschlange aus dem angegebenen Namespace in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="62d20-142">Deletes a queue from the specified namespace in a resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639411.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-144">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-144">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-145">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-145">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-146">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-146">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-147">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-147">The authorizationrule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-148">Löscht eine Autorisierungsregel für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="62d20-148">Deletes a queue authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705609.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-150">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-150">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-151">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-151">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-152">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-152">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-153">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-153">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-155">Löscht eine Autorisierungsregel für die Warteschlange an.</span><span class="sxs-lookup"><span data-stu-id="62d20-155">Deletes a queue authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705609.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBQueue Get (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBQueue Get(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.Get(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String) As SBQueue" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBQueue" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.Get (operations, resourceGroupName, namespaceName, queueName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBQueue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-156">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-156">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-157">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-157">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-158">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-158">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-159">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-159">The queue name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-160">Gibt eine Beschreibung für die angegebene Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="62d20-160">Returns a description for the specified queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639380.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, queueName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-161">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-162">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-162">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-163">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-163">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-164">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-164">The queue name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-165">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-165">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-166">Gibt eine Beschreibung für die angegebene Warteschlange zurück.</span><span class="sxs-lookup"><span data-stu-id="62d20-166">Returns a description for the specified queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639380.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule GetAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule GetAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String, authorizationRuleName As String) As SBAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-167">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-167">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-168">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-168">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-169">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-169">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-170">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-170">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-171">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-171">The authorizationrule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-172">Ruft eine Autorisierungsregel für eine Warteschlange nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="62d20-172">Gets an authorization rule for a queue by rule name.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705611.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-173">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-174">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-174">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-175">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-175">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-176">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-176">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-177">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-177">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-178">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-178">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-179">Ruft eine Autorisierungsregel für eine Warteschlange nach Regelname ab.</span><span class="sxs-lookup"><span data-stu-id="62d20-179">Gets an authorization rule for a queue by rule name.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705611.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRules (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRules(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String) As IPage(Of SBAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, queueName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-180">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-181">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-181">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-182">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-182">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-183">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-183">The queue name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-184">Ruft alle Autorisierungsregeln für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-184">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, queueName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-185">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-186">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-186">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-187">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-187">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-188">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-188">The queue name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-190">Ruft alle Autorisierungsregeln für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-190">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As IQueuesOperations, nextPageLink As String) As IPage(Of SBAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="62d20-192">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="62d20-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-193">Ruft alle Autorisierungsregeln für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-193">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-194">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-194">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="62d20-195">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="62d20-195">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-197">Ruft alle Autorisierungsregeln für eine Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-197">Gets all authorization rules for a queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705607.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; ListByNamespace (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; ListByNamespace(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespace(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespace (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String) As IPage(Of SBQueue)" />
      <MemberSignature Language="F#" Value="static member ListByNamespace : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespace (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-199">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-199">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-200">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-200">The namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-201">Ruft die Warteschlangen in einem Namespace an.</span><span class="sxs-lookup"><span data-stu-id="62d20-201">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; ListByNamespaceAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; ListByNamespaceAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespaceAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespaceAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;ListByNamespaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-202">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-203">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-203">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-204">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-204">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-205">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-206">Ruft die Warteschlangen in einem Namespace an.</span><span class="sxs-lookup"><span data-stu-id="62d20-206">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; ListByNamespaceNext (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt; ListByNamespaceNext(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespaceNext(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespaceNext (operations As IQueuesOperations, nextPageLink As String) As IPage(Of SBQueue)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNext : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="62d20-208">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="62d20-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-209">Ruft die Warteschlangen in einem Namespace an.</span><span class="sxs-lookup"><span data-stu-id="62d20-209">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; ListByNamespaceNextAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt; ListByNamespaceNextAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespaceNextAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNextAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListByNamespaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;ListByNamespaceNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBQueue&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-210">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="62d20-211">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="62d20-211">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-213">Ruft die Warteschlangen in einem Namespace an.</span><span class="sxs-lookup"><span data-stu-id="62d20-213">Gets the queues within a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639415.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.AccessKeys ListKeys (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys ListKeys(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListKeys(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String, authorizationRuleName As String) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-215">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-215">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-216">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-216">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-217">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-217">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-218">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-218">The authorizationrule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-219">Primäre und sekundäre Verbindungszeichenfolgen an die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-219">Primary and secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705608.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;ListKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-220">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-221">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-221">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-222">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-222">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-223">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-223">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-224">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-224">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-226">Primäre und sekundäre Verbindungszeichenfolgen an die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-226">Primary and secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705608.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.AccessKeys RegenerateKeys (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys RegenerateKeys(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As IQueuesOperations, resourceGroupName As String, namespaceName As String, queueName As String, authorizationRuleName As String, parameters As RegenerateAccessKeyParameters) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters -&gt; Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-227">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-227">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-228">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-228">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-229">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-229">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-230">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-230">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-231">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-231">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d20-232">Der Parameter angegeben wird, um die Autorisierungsregel erneut zu generieren.</span><span class="sxs-lookup"><span data-stu-id="62d20-232">Parameters supplied to regenerate the authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-233">Generiert den primären oder sekundären Verbindungszeichenfolgen an die Warteschlange erneut.</span><span class="sxs-lookup"><span data-stu-id="62d20-233">Regenerates the primary or secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705606.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.ServiceBus.IQueuesOperations operations, string resourceGroupName, string namespaceName, string queueName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.ServiceBus.IQueuesOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.ServiceBus.IQueuesOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, queueName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.QueuesOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IQueuesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="queueName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="62d20-234">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="62d20-234">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="62d20-235">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="62d20-235">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="62d20-236">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="62d20-236">The namespace name</span></span>
            </param>
        <param name="queueName">
            <span data-ttu-id="62d20-237">Den Namen der Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="62d20-237">The queue name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="62d20-238">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="62d20-238">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="62d20-239">Der Parameter angegeben wird, um die Autorisierungsregel erneut zu generieren.</span><span class="sxs-lookup"><span data-stu-id="62d20-239">Parameters supplied to regenerate the authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="62d20-240">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="62d20-240">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="62d20-241">Generiert den primären oder sekundären Verbindungszeichenfolgen an die Warteschlange erneut.</span><span class="sxs-lookup"><span data-stu-id="62d20-241">Regenerates the primary or secondary connection strings to the queue.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt705606.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>