<Type Name="EventSubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventSubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EventSubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="96217-101">Erweiterungsmethoden für EventSubscriptionsOperations.</span><span class="sxs-lookup"><span data-stu-id="96217-101">Extension methods for EventSubscriptionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginCreate (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginCreate(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String, eventSubscriptionInfo As EventSubscription) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreate (operations, scope, eventSubscriptionName, eventSubscriptionInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-102">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-103">Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss.</span><span class="sxs-lookup"><span data-stu-id="96217-103">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="96217-104">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-104">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-105">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-105">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-106">Name des Ereignisses Abonnements erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="96217-106">Name of the event subscription to be created.</span></span> <span data-ttu-id="96217-107">Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="96217-107">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="96217-108">Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter</span><span class="sxs-lookup"><span data-stu-id="96217-108">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-109">Ereignisabonnement erstellen</span><span class="sxs-lookup"><span data-stu-id="96217-109">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-110">Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.</span><span class="sxs-lookup"><span data-stu-id="96217-110">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="96217-111">Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="96217-111">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginCreateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginCreateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreateAsync (operations, scope, eventSubscriptionName, eventSubscriptionInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginCreateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-112">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-112">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-113">Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss.</span><span class="sxs-lookup"><span data-stu-id="96217-113">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="96217-114">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-114">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-115">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-115">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-116">Name des Ereignisses Abonnements erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="96217-116">Name of the event subscription to be created.</span></span> <span data-ttu-id="96217-117">Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="96217-117">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="96217-118">Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter</span><span class="sxs-lookup"><span data-stu-id="96217-118">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-120">Ereignisabonnement erstellen</span><span class="sxs-lookup"><span data-stu-id="96217-120">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-121">Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.</span><span class="sxs-lookup"><span data-stu-id="96217-121">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="96217-122">Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="96217-122">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDelete (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-123">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-124">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-124">The scope of the event subscription.</span></span> <span data-ttu-id="96217-125">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-125">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-126">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-126">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-127">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-127">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-128">Ereignisabonnement löschen</span><span class="sxs-lookup"><span data-stu-id="96217-128">Delete an event subscription</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="96217-129">Löschen Sie ein vorhandenes Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-129">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDeleteAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-130">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-131">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-131">The scope of the event subscription.</span></span> <span data-ttu-id="96217-132">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-132">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-133">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-133">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-134">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-134">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-136">Ereignisabonnement löschen</span><span class="sxs-lookup"><span data-stu-id="96217-136">Delete an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-137">Löschen Sie ein vorhandenes Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-137">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginUpdate (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginUpdate(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdate (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-138">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-139">Der Bereich der vorhandenen Ereignisabonnement.</span><span class="sxs-lookup"><span data-stu-id="96217-139">The scope of existing event subscription.</span></span> <span data-ttu-id="96217-140">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-140">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-141">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-141">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-142">Name des zu erstellenden das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-142">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="96217-143">Aktualisierte Ereignisinformationen für Abonnement</span><span class="sxs-lookup"><span data-stu-id="96217-143">Updated event subscription information</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-144">Ereignisabonnement aktualisieren</span><span class="sxs-lookup"><span data-stu-id="96217-144">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-145">Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.</span><span class="sxs-lookup"><span data-stu-id="96217-145">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginUpdateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginUpdateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdateAsync (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-146">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-147">Der Bereich der vorhandenen Ereignisabonnement.</span><span class="sxs-lookup"><span data-stu-id="96217-147">The scope of existing event subscription.</span></span> <span data-ttu-id="96217-148">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-148">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-149">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-149">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-150">Name des zu erstellenden das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-150">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="96217-151">Aktualisierte Ereignisinformationen für Abonnement</span><span class="sxs-lookup"><span data-stu-id="96217-151">Updated event subscription information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-152">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-152">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-153">Ereignisabonnement aktualisieren</span><span class="sxs-lookup"><span data-stu-id="96217-153">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-154">Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.</span><span class="sxs-lookup"><span data-stu-id="96217-154">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Create (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Create(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Create(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String, eventSubscriptionInfo As EventSubscription) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Create (operations, scope, eventSubscriptionName, eventSubscriptionInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-155">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-155">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-156">Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss.</span><span class="sxs-lookup"><span data-stu-id="96217-156">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="96217-157">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-157">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-158">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-158">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-159">Name des Ereignisses Abonnements erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="96217-159">Name of the event subscription to be created.</span></span> <span data-ttu-id="96217-160">Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="96217-160">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="96217-161">Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter</span><span class="sxs-lookup"><span data-stu-id="96217-161">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-162">Ereignisabonnement erstellen</span><span class="sxs-lookup"><span data-stu-id="96217-162">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-163">Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.</span><span class="sxs-lookup"><span data-stu-id="96217-163">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="96217-164">Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="96217-164">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; CreateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; CreateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.CreateAsync (operations, scope, eventSubscriptionName, eventSubscriptionInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-165">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-165">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-166">Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss.</span><span class="sxs-lookup"><span data-stu-id="96217-166">The scope of the resource to which the event subscription needs to be created.</span></span> <span data-ttu-id="96217-167">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-167">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-168">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-168">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-169">Name des Ereignisses Abonnements erstellt werden soll.</span><span class="sxs-lookup"><span data-stu-id="96217-169">Name of the event subscription to be created.</span></span> <span data-ttu-id="96217-170">Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.</span><span class="sxs-lookup"><span data-stu-id="96217-170">Event subscription names must be between 3 and 64 characters in length and use alphanumeric letters only.</span></span>
            </param>
        <param name="eventSubscriptionInfo">
            <span data-ttu-id="96217-171">Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter</span><span class="sxs-lookup"><span data-stu-id="96217-171">Event subscription properties containing the destination and filter information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-172">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-172">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-173">Ereignisabonnement erstellen</span><span class="sxs-lookup"><span data-stu-id="96217-173">Create an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-174">Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.</span><span class="sxs-lookup"><span data-stu-id="96217-174">Asynchronously creates a new event subscription to the specified scope.</span></span>
            <span data-ttu-id="96217-175">Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="96217-175">Existing event subscriptions cannot be updated with this API and should instead use the Update event subscription API.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Delete(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Delete (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-176">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-177">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-177">The scope of the event subscription.</span></span> <span data-ttu-id="96217-178">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-178">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-179">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-179">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-180">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-180">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-181">Ereignisabonnement löschen</span><span class="sxs-lookup"><span data-stu-id="96217-181">Delete an event subscription</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="96217-182">Löschen Sie ein vorhandenes Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-182">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.DeleteAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-183">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-183">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-184">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-184">The scope of the event subscription.</span></span> <span data-ttu-id="96217-185">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-185">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-186">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-186">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-187">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-187">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-188">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-188">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-189">Ereignisabonnement löschen</span><span class="sxs-lookup"><span data-stu-id="96217-189">Delete an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-190">Löschen Sie ein vorhandenes Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-190">Delete an existing event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Get (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Get(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Get(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Get (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-191">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-192">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-192">The scope of the event subscription.</span></span> <span data-ttu-id="96217-193">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-193">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-194">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-194">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-195">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-195">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-196">Ereignisabonnement abrufen</span><span class="sxs-lookup"><span data-stu-id="96217-196">Get an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-197">Abrufen von Eigenschaften von Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-197">Get properties of an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; GetAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; GetAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-198">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-199">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-199">The scope of the event subscription.</span></span> <span data-ttu-id="96217-200">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-200">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-201">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-201">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-202">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-202">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-204">Ereignisabonnement abrufen</span><span class="sxs-lookup"><span data-stu-id="96217-204">Get an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-205">Abrufen von Eigenschaften von Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-205">Get properties of an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl GetFullUrl (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl GetFullUrl(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrl(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFullUrl (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String) As EventSubscriptionFullUrl" />
      <MemberSignature Language="F#" Value="static member GetFullUrl : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrl (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-206">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-207">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-207">The scope of the event subscription.</span></span> <span data-ttu-id="96217-208">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-208">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-209">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-209">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-210">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-210">Name of the event subscription</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-211">Vollständige URL des Ereignisabonnement abrufen</span><span class="sxs-lookup"><span data-stu-id="96217-211">Get full URL of an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-212">Rufen Sie die vollständige Endpunkt-URL für Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-212">Get the full endpoint URL for an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt; GetFullUrlAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt; GetFullUrlAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrlAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFullUrlAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrlAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;GetFullUrlAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-213">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-213">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-214">Der Bereich der Abonnieren des Ereignisses.</span><span class="sxs-lookup"><span data-stu-id="96217-214">The scope of the event subscription.</span></span> <span data-ttu-id="96217-215">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-215">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-216">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-216">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-217">Name des das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-217">Name of the event subscription</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-219">Vollständige URL des Ereignisabonnement abrufen</span><span class="sxs-lookup"><span data-stu-id="96217-219">Get full URL of an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-220">Rufen Sie die vollständige Endpunkt-URL für Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-220">Get the full endpoint URL for an event subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResource">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListByResource (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListByResource(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResource(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResource (operations As IEventSubscriptionsOperations, resourceGroupName As String, providerNamespace As String, resourceTypeName As String, resourceName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByResource : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResource (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-222">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-222">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="96217-223">Namespace des Anbieters des Themas</span><span class="sxs-lookup"><span data-stu-id="96217-223">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="96217-224">Name des Ressourcentyps</span><span class="sxs-lookup"><span data-stu-id="96217-224">Name of the resource type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="96217-225">Name der Ressource</span><span class="sxs-lookup"><span data-stu-id="96217-225">Name of the resource</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-226">Listen Sie aller Ereignisabonnements, für ein bestimmtes Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-226">List all event subscriptions for a specific topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-227">Listen Sie aller Ereignisabonnements auf,, die für ein bestimmtes Thema erstellt wurden</span><span class="sxs-lookup"><span data-stu-id="96217-227">List all event subscriptions that have been created for a specific topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListByResourceAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListByResourceAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResourceAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResourceAsync (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListByResourceAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-228">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-229">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-229">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="providerNamespace">
            <span data-ttu-id="96217-230">Namespace des Anbieters des Themas</span><span class="sxs-lookup"><span data-stu-id="96217-230">Namespace of the provider of the topic</span></span>
            </param>
        <param name="resourceTypeName">
            <span data-ttu-id="96217-231">Name des Ressourcentyps</span><span class="sxs-lookup"><span data-stu-id="96217-231">Name of the resource type</span></span>
            </param>
        <param name="resourceName">
            <span data-ttu-id="96217-232">Name der Ressource</span><span class="sxs-lookup"><span data-stu-id="96217-232">Name of the resource</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-233">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-233">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-234">Listen Sie aller Ereignisabonnements, für ein bestimmtes Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-234">List all event subscriptions for a specific topic</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-235">Listen Sie aller Ereignisabonnements auf,, die für ein bestimmtes Thema erstellt wurden</span><span class="sxs-lookup"><span data-stu-id="96217-235">List all event subscriptions that have been created for a specific topic</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroup (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroup(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroup(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalByResourceGroup (operations As IEventSubscriptionsOperations, resourceGroupName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroup : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-237">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-237">The name of the resource group within the user's subscription.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-238">Listen Sie aller globalen Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe auf</span><span class="sxs-lookup"><span data-stu-id="96217-238">List all global event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-239">Listen Sie aller Abonnements, globale Ereignis unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf</span><span class="sxs-lookup"><span data-stu-id="96217-239">List all global event subscriptions under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalByResourceGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-240">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-241">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-241">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-242">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-242">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-243">Listen Sie aller globalen Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe auf</span><span class="sxs-lookup"><span data-stu-id="96217-243">List all global event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-244">Listen Sie aller Abonnements, globale Ereignis unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf</span><span class="sxs-lookup"><span data-stu-id="96217-244">List all global event subscriptions under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroupForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroupForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalByResourceGroupForTopicType (operations As IEventSubscriptionsOperations, resourceGroupName As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicType (operations, resourceGroupName, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-245">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-245">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-246">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-246">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-247">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-247">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-248">Listen Sie aller Abonnements, globale Ereignis unterhalb einer Ressourcengruppe für ein Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-248">List all global event subscriptions under a resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-249">Listen Sie aller globalen Ereignisabonnements unterhalb einer Ressourcengruppe für einen bestimmten Thema an auf.</span><span class="sxs-lookup"><span data-stu-id="96217-249">List all global event subscriptions under a resource group for a specific topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicTypeAsync (operations, resourceGroupName, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalByResourceGroupForTopicTypeAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-250">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-250">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-251">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-251">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-252">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-252">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-254">Listen Sie aller Abonnements, globale Ereignis unterhalb einer Ressourcengruppe für ein Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-254">List all global event subscriptions under a resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-255">Listen Sie aller globalen Ereignisabonnements unterhalb einer Ressourcengruppe für einen bestimmten Thema an auf.</span><span class="sxs-lookup"><span data-stu-id="96217-255">List all global event subscriptions under a resource group for a specific topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscription (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscription(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscription(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalBySubscription (operations As IEventSubscriptionsOperations) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscription : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-256">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-257">Eine aggregierte Liste aller globalen Ereignis Abonnements unter einem Azure-Abonnement abrufen</span><span class="sxs-lookup"><span data-stu-id="96217-257">Get an aggregated list of all global event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-258">Liste aller aggregiert globale Ereignisabonnements unter einem bestimmten Azure-Abonnement</span><span class="sxs-lookup"><span data-stu-id="96217-258">List all aggregated global event subscriptions under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalBySubscriptionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-259">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-259">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-260">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-260">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-261">Eine aggregierte Liste aller globalen Ereignis Abonnements unter einem Azure-Abonnement abrufen</span><span class="sxs-lookup"><span data-stu-id="96217-261">Get an aggregated list of all global event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-262">Liste aller aggregiert globale Ereignisabonnements unter einem bestimmten Azure-Abonnement</span><span class="sxs-lookup"><span data-stu-id="96217-262">List all aggregated global event subscriptions under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscriptionForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscriptionForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalBySubscriptionForTopicType (operations As IEventSubscriptionsOperations, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicType (operations, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-263">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-263">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-264">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-264">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-265">Listen Sie aller Abonnements, globale Ereignis für ein Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-265">List all global event subscriptions for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-266">Listen Sie aller globalen Ereignisabonnements unter einem Azure-Abonnement für ein Thema auf.</span><span class="sxs-lookup"><span data-stu-id="96217-266">List all global event subscriptions under an Azure subscription for a topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicTypeAsync (operations, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalBySubscriptionForTopicTypeAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-267">The operations group for this extension method.</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-268">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-268">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-269">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-269">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-270">Listen Sie aller Abonnements, globale Ereignis für ein Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-270">List all global event subscriptions for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-271">Listen Sie aller globalen Ereignisabonnements unter einem Azure-Abonnement für ein Thema auf.</span><span class="sxs-lookup"><span data-stu-id="96217-271">List all global event subscriptions under an Azure subscription for a topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroup (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroup(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroup(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalByResourceGroup (operations As IEventSubscriptionsOperations, resourceGroupName As String, location As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroup : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroup (operations, resourceGroupName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-272">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-272">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-273">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-273">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-274">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-274">Name of the location</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-275">Listen Sie aller Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe, Land/Region auf</span><span class="sxs-lookup"><span data-stu-id="96217-275">List all regional event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-276">Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf</span><span class="sxs-lookup"><span data-stu-id="96217-276">List all event subscriptions from the given location under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupAsync (operations, resourceGroupName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalByResourceGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-277">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-277">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-278">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-278">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-279">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-279">Name of the location</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-280">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-281">Listen Sie aller Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe, Land/Region auf</span><span class="sxs-lookup"><span data-stu-id="96217-281">List all regional event subscriptions under an Azure subscription and resource group</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-282">Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf</span><span class="sxs-lookup"><span data-stu-id="96217-282">List all event subscriptions from the given location under a specific Azure subscription and resource group</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroupForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroupForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalByResourceGroupForTopicType (operations As IEventSubscriptionsOperations, resourceGroupName As String, location As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicType (operations, resourceGroupName, location, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-283">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-283">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-284">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-284">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-285">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-285">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-286">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-286">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-287">Listen Sie aller Ereignisabonnements, Land/Region unter einer Azure Abonnement- und Ressourcenstatus-Gruppe für ein Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-287">List all regional event subscriptions under an Azure subscription and resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-288">Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einen bestimmten Azure Abonnement- und Ressourcenstatus Gruppen- und Thema Typ auf</span><span class="sxs-lookup"><span data-stu-id="96217-288">List all event subscriptions from the given location under a specific Azure subscription and resource group and topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicTypeAsync (operations, resourceGroupName, location, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalByResourceGroupForTopicTypeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-289">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-289">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96217-290">Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="96217-290">The name of the resource group within the user's subscription.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-291">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-291">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-292">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-292">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-293">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-293">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-294">Listen Sie aller Ereignisabonnements, Land/Region unter einer Azure Abonnement- und Ressourcenstatus-Gruppe für ein Thema auf</span><span class="sxs-lookup"><span data-stu-id="96217-294">List all regional event subscriptions under an Azure subscription and resource group for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-295">Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einen bestimmten Azure Abonnement- und Ressourcenstatus Gruppen- und Thema Typ auf</span><span class="sxs-lookup"><span data-stu-id="96217-295">List all event subscriptions from the given location under a specific Azure subscription and resource group and topic type</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscription (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscription(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscription(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalBySubscription (operations As IEventSubscriptionsOperations, location As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscription : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscription (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-296">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-297">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-297">Name of the location</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-298">Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement, Land/Region auf</span><span class="sxs-lookup"><span data-stu-id="96217-298">List all regional event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-299">Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Azure-Abonnement auf</span><span class="sxs-lookup"><span data-stu-id="96217-299">List all event subscriptions from the given location under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalBySubscriptionAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-300">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-300">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-301">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-301">Name of the location</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-302">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-302">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-303">Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement, Land/Region auf</span><span class="sxs-lookup"><span data-stu-id="96217-303">List all regional event subscriptions under an Azure subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-304">Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Azure-Abonnement auf</span><span class="sxs-lookup"><span data-stu-id="96217-304">List all event subscriptions from the given location under a specific Azure subscription</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscriptionForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscriptionForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalBySubscriptionForTopicType (operations As IEventSubscriptionsOperations, location As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicType (operations, location, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-305">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-305">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-306">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-306">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-307">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-307">Name of the topic type</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-308">Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement für eine Thementyp, Land/Region auf</span><span class="sxs-lookup"><span data-stu-id="96217-308">List all regional event subscriptions under an Azure subscription for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-309">Listen Sie aller Ereignisabonnements aus dem angegebenen Speicherort unter einen bestimmten Azure-Abonnement und Thema Typ an auf.</span><span class="sxs-lookup"><span data-stu-id="96217-309">List all event subscriptions from the given location under a specific Azure subscription and topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicTypeAsync (operations, location, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalBySubscriptionForTopicTypeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-310">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-310">The operations group for this extension method.</span></span>
            </param>
        <param name="location">
            <span data-ttu-id="96217-311">Der Name des Speicherorts</span><span class="sxs-lookup"><span data-stu-id="96217-311">Name of the location</span></span>
            </param>
        <param name="topicTypeName">
            <span data-ttu-id="96217-312">Name des Typs Thema</span><span class="sxs-lookup"><span data-stu-id="96217-312">Name of the topic type</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-313">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-313">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-314">Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement für eine Thementyp, Land/Region auf</span><span class="sxs-lookup"><span data-stu-id="96217-314">List all regional event subscriptions under an Azure subscription for a topic type</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-315">Listen Sie aller Ereignisabonnements aus dem angegebenen Speicherort unter einen bestimmten Azure-Abonnement und Thema Typ an auf.</span><span class="sxs-lookup"><span data-stu-id="96217-315">List all event subscriptions from the given location under a specific Azure subscription and topic type.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Update (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Update(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Update(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Update (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-316">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-316">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-317">Der Bereich der vorhandenen Ereignisabonnement.</span><span class="sxs-lookup"><span data-stu-id="96217-317">The scope of existing event subscription.</span></span> <span data-ttu-id="96217-318">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-318">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-319">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-319">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-320">Name des zu erstellenden das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-320">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="96217-321">Aktualisierte Ereignisinformationen für Abonnement</span><span class="sxs-lookup"><span data-stu-id="96217-321">Updated event subscription information</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-322">Ereignisabonnement aktualisieren</span><span class="sxs-lookup"><span data-stu-id="96217-322">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-323">Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.</span><span class="sxs-lookup"><span data-stu-id="96217-323">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; UpdateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; UpdateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.UpdateAsync (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96217-324">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="96217-324">The operations group for this extension method.</span></span>
            </param>
        <param name="scope">
            <span data-ttu-id="96217-325">Der Bereich der vorhandenen Ereignisabonnement.</span><span class="sxs-lookup"><span data-stu-id="96217-325">The scope of existing event subscription.</span></span> <span data-ttu-id="96217-326">Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein.</span><span class="sxs-lookup"><span data-stu-id="96217-326">The scope can be a subscription, or a resource group, or a top level resource belonging to a resource provider namespace, or an EventGrid topic.</span></span> <span data-ttu-id="96217-327">Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.</span><span class="sxs-lookup"><span data-stu-id="96217-327">For example, use '/subscriptions/{subscriptionId}/' for a subscription, '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}' for a resource group, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/{resourceProviderNamespace}/{resourceType}/{resourceName}' for a resource, and '/subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName}' for an EventGrid topic.</span></span>
            </param>
        <param name="eventSubscriptionName">
            <span data-ttu-id="96217-328">Name des zu erstellenden das Ereignisabonnement</span><span class="sxs-lookup"><span data-stu-id="96217-328">Name of the event subscription to be created</span></span>
            </param>
        <param name="eventSubscriptionUpdateParameters">
            <span data-ttu-id="96217-329">Aktualisierte Ereignisinformationen für Abonnement</span><span class="sxs-lookup"><span data-stu-id="96217-329">Updated event subscription information</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="96217-330">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="96217-330">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96217-331">Ereignisabonnement aktualisieren</span><span class="sxs-lookup"><span data-stu-id="96217-331">Update an event subscription</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="96217-332">Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.</span><span class="sxs-lookup"><span data-stu-id="96217-332">Asynchronously updates an existing event subscription.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>