<Type Name="RulesOperationsExtensions" FullName="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RulesOperationsExtensions = class" />
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
            <span data-ttu-id="57bd6-101">Erweiterungsmethoden für RulesOperations.</span><span class="sxs-lookup"><span data-stu-id="57bd6-101">Extension methods for RulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.Rule CreateOrUpdate (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, Microsoft.Azure.Management.ServiceBus.Models.Rule parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.Rule CreateOrUpdate(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, class Microsoft.Azure.Management.ServiceBus.Models.Rule parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.Rule)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRulesOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String, ruleName As String, parameters As Rule) As Rule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.Rule -&gt; Microsoft.Azure.Management.ServiceBus.Models.Rule" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.Rule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.Rule" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-103">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-103">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-104">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-104">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-105">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-105">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-106">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-106">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="57bd6-107">Der Regelname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-107">The rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="57bd6-108">Parameter zum Erstellen einer Regel angegeben.</span><span class="sxs-lookup"><span data-stu-id="57bd6-108">Parameters supplied to create a rule.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-109">Erstellt eine neue Regel, und aktualisiert eine vorhandene Regel</span><span class="sxs-lookup"><span data-stu-id="57bd6-109">Creates a new rule and updates an existing rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, Microsoft.Azure.Management.ServiceBus.Models.Rule parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, class Microsoft.Azure.Management.ServiceBus.Models.Rule parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.ServiceBus.Models.Rule,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * string * Microsoft.Azure.Management.ServiceBus.Models.Rule * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.ServiceBus.Models.Rule" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-110">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-111">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-111">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-112">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-112">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-113">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-113">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-114">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-114">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="57bd6-115">Der Regelname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-115">The rule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="57bd6-116">Parameter zum Erstellen einer Regel angegeben.</span><span class="sxs-lookup"><span data-stu-id="57bd6-116">Parameters supplied to create a rule.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57bd6-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57bd6-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-118">Erstellt eine neue Regel, und aktualisiert eine vorhandene Regel</span><span class="sxs-lookup"><span data-stu-id="57bd6-118">Creates a new rule and updates an existing rule</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.Delete(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IRulesOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String, ruleName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.Delete (operations, resourceGroupName, namespaceName, topicName, subscriptionName, ruleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-119">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-120">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-120">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-121">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-121">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-122">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-122">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-123">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-123">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="57bd6-124">Der Regelname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-124">The rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-125">Löscht eine vorhandene Regel.</span><span class="sxs-lookup"><span data-stu-id="57bd6-125">Deletes an existing rule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.DeleteAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-126">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-127">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-127">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-128">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-128">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-129">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-129">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-130">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-130">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="57bd6-131">Der Regelname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-131">The rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57bd6-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57bd6-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-133">Löscht eine vorhandene Regel.</span><span class="sxs-lookup"><span data-stu-id="57bd6-133">Deletes an existing rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ServiceBus.Models.Rule Get (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ServiceBus.Models.Rule Get(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.Get(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRulesOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String, ruleName As String) As Rule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.ServiceBus.Models.Rule" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.Get (operations, resourceGroupName, namespaceName, topicName, subscriptionName, ruleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.Rule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-134">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-135">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-135">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-136">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-136">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-137">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-137">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-138">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-138">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="57bd6-139">Der Regelname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-139">The rule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-140">Ruft die Beschreibung für die angegebene Regel ab.</span><span class="sxs-lookup"><span data-stu-id="57bd6-140">Retrieves the description for the specified rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; GetAsync (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; GetAsync(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, string ruleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.GetAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, ruleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="ruleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-141">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-141">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-142">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-142">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-143">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-143">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-144">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-144">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-145">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-145">The subscription name.</span></span>
            </param>
        <param name="ruleName">
            <span data-ttu-id="57bd6-146">Der Regelname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-146">The rule name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57bd6-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57bd6-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-148">Ruft die Beschreibung für die angegebene Regel ab.</span><span class="sxs-lookup"><span data-stu-id="57bd6-148">Retrieves the description for the specified rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptions">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; ListBySubscriptions (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; ListBySubscriptions(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptions(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptions (operations As IRulesOperations, resourceGroupName As String, namespaceName As String, topicName As String, subscriptionName As String) As IPage(Of Rule)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptions : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptions (operations, resourceGroupName, namespaceName, topicName, subscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-149">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-149">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-150">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-150">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-151">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-151">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-152">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-152">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-153">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-153">The subscription name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-154">Liste aller Regeln innerhalb eines bestimmten Thema-Abonnements</span><span class="sxs-lookup"><span data-stu-id="57bd6-154">List all the rules within given topic-subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; ListBySubscriptionsAsync (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; ListBySubscriptionsAsync(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string resourceGroupName, string namespaceName, string topicName, string subscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptionsAsync(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionsAsync : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptionsAsync (operations, resourceGroupName, namespaceName, topicName, subscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions/&lt;ListBySubscriptionsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="namespaceName" Type="System.String" />
        <Parameter Name="topicName" Type="System.String" />
        <Parameter Name="subscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-155">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="57bd6-156">Der Name der Ressourcengruppe innerhalb des Azure-Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-156">Name of the Resource group within the Azure subscription.</span></span>
            </param>
        <param name="namespaceName">
            <span data-ttu-id="57bd6-157">Der Name des Namespaces</span><span class="sxs-lookup"><span data-stu-id="57bd6-157">The namespace name</span></span>
            </param>
        <param name="topicName">
            <span data-ttu-id="57bd6-158">Der themaname.</span><span class="sxs-lookup"><span data-stu-id="57bd6-158">The topic name.</span></span>
            </param>
        <param name="subscriptionName">
            <span data-ttu-id="57bd6-159">Der Name des Abonnements.</span><span class="sxs-lookup"><span data-stu-id="57bd6-159">The subscription name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57bd6-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57bd6-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-161">Liste aller Regeln innerhalb eines bestimmten Thema-Abonnements</span><span class="sxs-lookup"><span data-stu-id="57bd6-161">List all the rules within given topic-subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionsNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; ListBySubscriptionsNext (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt; ListBySubscriptionsNext(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptionsNext(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListBySubscriptionsNext (operations As IRulesOperations, nextPageLink As String) As IPage(Of Rule)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionsNext : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptionsNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-162">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="57bd6-163">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="57bd6-163">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-164">Liste aller Regeln innerhalb eines bestimmten Thema-Abonnements</span><span class="sxs-lookup"><span data-stu-id="57bd6-164">List all the rules within given topic-subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListBySubscriptionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; ListBySubscriptionsNextAsync (this Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt; ListBySubscriptionsNextAsync(class Microsoft.Azure.Management.ServiceBus.IRulesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptionsNextAsync(Microsoft.Azure.Management.ServiceBus.IRulesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListBySubscriptionsNextAsync : Microsoft.Azure.Management.ServiceBus.IRulesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;" Usage="Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions.ListBySubscriptionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ServiceBus.RulesOperationsExtensions/&lt;ListBySubscriptionsNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Models.Rule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ServiceBus.IRulesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="57bd6-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="57bd6-165">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="57bd6-166">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="57bd6-166">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="57bd6-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="57bd6-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="57bd6-168">Liste aller Regeln innerhalb eines bestimmten Thema-Abonnements</span><span class="sxs-lookup"><span data-stu-id="57bd6-168">List all the rules within given topic-subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>