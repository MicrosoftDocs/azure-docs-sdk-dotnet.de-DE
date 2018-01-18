<Type Name="TopicsOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class TopicsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TopicsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TopicsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type TopicsOperationsExtensions = class" />
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
            <span data-ttu-id="87666-101">Erweiterungsmethoden für TopicsOperations.</span><span class="sxs-lookup"><span data-stu-id="87666-101">Extension methods for TopicsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBTopic CreateOrUpdate (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, Microsoft.Azure.Management.ServiceBus.Models.SBTopic parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBTopic CreateOrUpdate(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, class Microsoft.Azure.Management.ServiceBus.Models.SBTopic parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBTopic)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String, parameters As SBTopic) As SBTopic" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBTopic -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBTopic" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, topicName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBTopic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBTopic" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-104">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-104">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-105">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-105">The topic name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87666-106">Parameter zum Erstellen einer Ressource Thema angegeben.</span><span class="sxs-lookup"><span data-stu-id="87666-106">Parameters supplied to create a topic resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-107">Erstellt ein Thema im angegebenen Namespace an.</span><span class="sxs-lookup"><span data-stu-id="87666-107">Creates a topic in the specified namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639409.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, Microsoft.Azure.Management.ServiceBus.Models.SBTopic parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, class Microsoft.Azure.Management.ServiceBus.Models.SBTopic parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBTopic,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBTopic * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, topicName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBTopic" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-108">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-108">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-109">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-109">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-110">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-110">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-111">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-111">The topic name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87666-112">Parameter zum Erstellen einer Ressource Thema angegeben.</span><span class="sxs-lookup"><span data-stu-id="87666-112">Parameters supplied to create a topic resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-113">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-113">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-114">Erstellt ein Thema im angegebenen Namespace an.</span><span class="sxs-lookup"><span data-stu-id="87666-114">Creates a topic in the specified namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639409.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule CreateOrUpdateAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule CreateOrUpdateAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdateAuthorizationRule(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAuthorizationRule (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String, authorizationRuleName As String, parameters As SBAuthorizationRule) As SBAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRule : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdateAuthorizationRule (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-115">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-116">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-116">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-117">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-117">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-118">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-118">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-119">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-119">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87666-120">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="87666-120">The shared access authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-121">Erstellt eine Regel Authorizatio für das angegebene Thema.</span><span class="sxs-lookup"><span data-stu-id="87666-121">Creates an authorizatio rule for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720678.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; CreateOrUpdateAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.CreateOrUpdateAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;CreateOrUpdateAuthorizationRuleAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-122">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-123">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-123">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-124">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-124">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-125">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-125">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-126">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-126">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87666-127">Die Autorisierungsregel für gemeinsamen Zugriff.</span><span class="sxs-lookup"><span data-stu-id="87666-127">The shared access authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-129">Erstellt eine Regel Authorizatio für das angegebene Thema.</span><span class="sxs-lookup"><span data-stu-id="87666-129">Creates an authorizatio rule for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720678.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-131">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-131">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-132">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-132">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-133">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-133">The topic name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-134">Löscht ein Thema aus der angegebenen Namespace und der Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="87666-134">Deletes a topic from the specified namespace and resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639404.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-135">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-136">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-136">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-137">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-137">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-138">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-138">The topic name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-140">Löscht ein Thema aus der angegebenen Namespace und der Gruppe an.</span><span class="sxs-lookup"><span data-stu-id="87666-140">Deletes a topic from the specified namespace and resource group.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639404.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRule">
      <MemberSignature Language="C#" Value="public static void DeleteAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void DeleteAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.DeleteAuthorizationRule(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub DeleteAuthorizationRule (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String, authorizationRuleName As String)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRule : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.DeleteAuthorizationRule (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-142">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-142">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-143">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-143">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-144">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-144">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-145">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-145">The authorizationrule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-146">Löscht eine Autorisierungsregel Thema.</span><span class="sxs-lookup"><span data-stu-id="87666-146">Deletes a topic authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720681.aspx" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.DeleteAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.DeleteAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;DeleteAuthorizationRuleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-147">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-147">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-148">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-148">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-149">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-149">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-150">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-150">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-151">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-151">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-153">Löscht eine Autorisierungsregel Thema.</span><span class="sxs-lookup"><span data-stu-id="87666-153">Deletes a topic authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720681.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBTopic Get (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBTopic Get(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.Get(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String) As SBTopic" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBTopic" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.Get (operations, resourceGroupName, namespaceName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBTopic</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-154">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-154">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-155">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-155">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-156">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-156">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-157">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-157">The topic name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-158">Gibt eine Beschreibung für das angegebene Thema an.</span><span class="sxs-lookup"><span data-stu-id="87666-158">Returns a description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639399.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-159">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-159">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-160">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-160">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-161">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-161">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-162">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-162">The topic name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-163">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-163">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-164">Gibt eine Beschreibung für das angegebene Thema an.</span><span class="sxs-lookup"><span data-stu-id="87666-164">Returns a description for the specified topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639399.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRule">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule GetAuthorizationRule (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule GetAuthorizationRule(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.GetAuthorizationRule(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAuthorizationRule (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String, authorizationRuleName As String) As SBAuthorizationRule" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRule : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.GetAuthorizationRule (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-165">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-166">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-166">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-167">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-167">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-168">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-168">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-169">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-169">The authorizationrule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-170">Gibt die angegebene Autorisierungsregel zurück.</span><span class="sxs-lookup"><span data-stu-id="87666-170">Returns the specified authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720676.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRuleAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; GetAuthorizationRuleAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; GetAuthorizationRuleAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.GetAuthorizationRuleAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAuthorizationRuleAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.GetAuthorizationRuleAsync (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;GetAuthorizationRuleAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-172">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-172">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-173">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-173">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-174">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-174">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-175">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-175">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-176">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-176">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-177">Gibt die angegebene Autorisierungsregel zurück.</span><span class="sxs-lookup"><span data-stu-id="87666-177">Returns the specified authorization rule.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720676.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRules">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRules (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRules(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRules(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRules (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String) As IPage(Of SBAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRules : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRules (operations, resourceGroupName, namespaceName, topicName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-178">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-179">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-179">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-180">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-180">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-181">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-181">The topic name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-182">Ruft die Autorisierungsregeln für ein Thema ab.</span><span class="sxs-lookup"><span data-stu-id="87666-182">Gets authorization rules for a topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720681.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRulesAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRulesAsync (operations, resourceGroupName, namespaceName, topicName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;ListAuthorizationRulesAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-183">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-184">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-184">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-185">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-185">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-186">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-186">The topic name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-188">Ruft die Autorisierungsregeln für ein Thema ab.</span><span class="sxs-lookup"><span data-stu-id="87666-188">Gets authorization rules for a topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720681.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRulesNext (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt; ListAuthorizationRulesNext(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRulesNext(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAuthorizationRulesNext (operations As ITopicsOperations, nextPageLink As String) As IPage(Of SBAuthorizationRule)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNext : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRulesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-189">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87666-190">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87666-190">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-191">Ruft die Autorisierungsregeln für ein Thema ab.</span><span class="sxs-lookup"><span data-stu-id="87666-191">Gets authorization rules for a topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720681.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAuthorizationRulesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt; ListAuthorizationRulesNextAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRulesNextAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAuthorizationRulesNextAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListAuthorizationRulesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;ListAuthorizationRulesNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBAuthorizationRule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-192">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87666-193">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87666-193">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-194">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-194">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-195">Ruft die Autorisierungsregeln für ein Thema ab.</span><span class="sxs-lookup"><span data-stu-id="87666-195">Gets authorization rules for a topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720681.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespace">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; ListByNamespace (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; ListByNamespace(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespace(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespace (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String) As IPage(Of SBTopic)" />
      <MemberSignature Language="F#" Value="static member ListByNamespace : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespace (operations, resourceGroupName, namespaceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-196">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-197">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-197">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-198">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-198">The namespace name</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-199">Ruft alle Themen in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="87666-199">Gets all the topics in a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639388.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt; ListByNamespaceAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt; ListByNamespaceAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespaceAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespaceAsync (operations, resourceGroupName, namespaceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;ListByNamespaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-200">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-201">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-201">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-202">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-202">The namespace name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-204">Ruft alle Themen in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="87666-204">Gets all the topics in a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639388.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; ListByNamespaceNext (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt; ListByNamespaceNext(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespaceNext(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByNamespaceNext (operations As ITopicsOperations, nextPageLink As String) As IPage(Of SBTopic)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNext : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespaceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-205">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87666-206">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87666-206">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-207">Ruft alle Themen in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="87666-207">Gets all the topics in a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639388.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByNamespaceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt; ListByNamespaceNextAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt; ListByNamespaceNextAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespaceNextAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByNamespaceNextAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListByNamespaceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;ListByNamespaceNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.SBTopic&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-208">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-208">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="87666-209">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="87666-209">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-210">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-210">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-211">Ruft alle Themen in einem Namespace.</span><span class="sxs-lookup"><span data-stu-id="87666-211">Gets all the topics in a namespace.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt639388.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.AccessKeys ListKeys (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys ListKeys(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListKeys(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListKeys (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String, authorizationRuleName As String) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member ListKeys : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListKeys (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-212">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-213">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-213">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-214">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-214">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-215">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-215">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-216">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-216">The authorizationrule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-217">Ruft die primären und sekundären Verbindungszeichenfolgen für das Thema an.</span><span class="sxs-lookup"><span data-stu-id="87666-217">Gets the primary and secondary connection strings for the topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720677.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; ListKeysAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; ListKeysAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListKeysAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListKeysAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.ListKeysAsync (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;ListKeysAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-218">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-218">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-219">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-219">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-220">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-220">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-221">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-221">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-222">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-222">The authorizationrule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-223">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-223">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-224">Ruft die primären und sekundären Verbindungszeichenfolgen für das Thema an.</span><span class="sxs-lookup"><span data-stu-id="87666-224">Gets the primary and secondary connection strings for the topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720677.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeys">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.AccessKeys RegenerateKeys (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys RegenerateKeys(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.RegenerateKeys(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RegenerateKeys (operations As ITopicsOperations, resourceGroupName As String, namespaceName As String, topicName As String, authorizationRuleName As String, parameters As RegenerateAccessKeyParameters) As AccessKeys" />
      <MemberSignature Language="F#" Value="static member RegenerateKeys : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters -&gt; Microsoft.Azure.Management.ServiceBus.Models.AccessKeys" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.RegenerateKeys (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.AccessKeys</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-225">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-225">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-226">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-226">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-227">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-227">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-228">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-228">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-229">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-229">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87666-230">Der Parameter angegeben wird, um die Autorisierungsregel erneut zu generieren.</span><span class="sxs-lookup"><span data-stu-id="87666-230">Parameters supplied to regenerate the authorization rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-231">Generiert einen neuen primären oder sekundären Verbindungszeichenfolgen für das Thema.</span><span class="sxs-lookup"><span data-stu-id="87666-231">Regenerates primary or secondary connection strings for the topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720679.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; RegenerateKeysAsync (this Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt; RegenerateKeysAsync(class Microsoft.Azure.Management.ServiceBus.ITopicsOperations operations, string resourceGroupName, string namespaceName, string topicName, string authorizationRuleName, class Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.RegenerateKeysAsync(Microsoft.Azure.Management.ServiceBus.ITopicsOperations,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateKeysAsync : Microsoft.Azure.Management.ServiceBus.ITopicsOperations * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;" Usage="Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions.RegenerateKeysAsync (operations, resourceGroupName, namespaceName, topicName, authorizationRuleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.TopicsOperationsExtensions/&lt;RegenerateKeysAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.AccessKeys&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.ITopicsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="authorizationRuleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.RegenerateAccessKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="87666-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="87666-232">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="87666-233">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="87666-233">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="87666-234">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="87666-234">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="87666-235">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="87666-235">The topic name.</span></span>
            </param>
        <param name="authorizationRuleName">
            <span data-ttu-id="87666-236">Der Name des Authorizationrule.</span><span class="sxs-lookup"><span data-stu-id="87666-236">The authorizationrule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="87666-237">Der Parameter angegeben wird, um die Autorisierungsregel erneut zu generieren.</span><span class="sxs-lookup"><span data-stu-id="87666-237">Parameters supplied to regenerate the authorization rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="87666-238">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="87666-238">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="87666-239">Generiert einen neuen primären oder sekundären Verbindungszeichenfolgen für das Thema.</span><span class="sxs-lookup"><span data-stu-id="87666-239">Regenerates primary or secondary connection strings for the topic.</span></span>
            <see href="https://msdn.microsoft.com/en-us/library/azure/mt720679.aspx" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>